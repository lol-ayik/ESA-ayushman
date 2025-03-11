# Employee Salary Analysis

Python tool analyzing employee compensation data by departments, experience, and age. Features statistical analysis, visualization, and custom metrics for identifying salary trends and top talent.

## Overview

This project provides a comprehensive analysis of employee salary data to help HR departments and managers understand compensation patterns within their organization. The script performs statistical analysis on salary distribution across different departments, experience levels, and age groups.

## Features

- **Basic Statistics**: Calculate mean, median, min, max, and standard deviation of salaries
- **Department Analysis**: Compare compensation metrics across different departments
- **Age Group Segmentation**: Analyze how age correlates with compensation
- **Experience Correlation**: Measure the relationship between years of experience and salary
- **Top Earners Identification**: List the highest-paid employees in the organization
- **Custom Metrics**:
  - Experience-to-age ratio for identifying fast climbers
  - Salary per year of experience for value assessment
- **Visualizations**:
  - Salary distribution by department (box plots)
  - Salary vs. experience (scatter plot with regression)
  - Average salary by age group and department (bar charts)

## Requirements

- Python 3.6+
- pandas
- matplotlib
- seaborn
- numpy

## Installation

```bash
git clone https://github.com/yourusername/employee-salary-analysis.git
cd employee-salary-analysis
pip install -r requirements.txt
```

## Usage

```python
python salary_analysis.py
```

Alternatively, import the functions into your own script:

```python
from salary_analysis import analyze_employee_data, create_visualizations

# Your data loading code here
df = pd.DataFrame(your_data)

# Run analysis
analyzed_df = analyze_employee_data(df)

# Generate visualizations
create_visualizations(analyzed_df)
```

## Sample Output

The script outputs detailed statistics to the console and generates three visualization files:
- salary_by_department.png
- salary_vs_experience.png
- salary_by_age_department.png

## License

MIT

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
