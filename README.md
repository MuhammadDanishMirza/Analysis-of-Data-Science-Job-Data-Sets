# Analysis of Data Science Salaries 2024

## Description
This Jupyter Notebook analyzes the dataset "Data Science Salaries 2024," which contains information on jobs in the data science field, including salary data. The analysis aims to explore trends and insights related to data science salaries, such as the impact of factors like experience level, employment type, company size, and location on compensation.

## Dataset
The dataset used in this analysis is downloaded from the following [https://www.kaggle.com/datasets/hummaamqaasim/jobs-in-data]. It comprises anonymized data on data science jobs collected from various sources, including surveys, job postings, and public records.

## Features
The dataset includes the following features:

| Column Name        | Description                                                             |
|--------------------|-------------------------------------------------------------------------|
| `work_year`        | The year the data related to the job salary was collected.              |
| `job_title`        | The employee's title or role within the data science field.             |
| `job_category`     | The category of the data science job.                                   |
| `salary_currency`  | The currency in which the salary is denoted.                           |
| `salary`           | The employee's salary.                                                  |
| `salary_in_usd`    | The salary converted to US dollars for standardization.                |
| `employee_residence` | The employee's residence location.                                     |
| `experience_level` | The employee's experience level (e.g., Junior, Mid-Level).            |
| `employment_type`  | The type of employment (e.g., Full-Time, Part-Time).                   |
| `work_setting`     | The work setting (e.g., In-person, Hybrid).                            |
| `company_location` | The location of the company.                                           |
| `company_size`     | The size of the company based on employee count or revenue.            |

## Libraries Used
The following libraries are used in this analysis:

- **NumPy**: For numerical operations and data manipulation.
- **Pandas**: For data analysis and manipulation.
- **Matplotlib**: For data visualization.
- **Seaborn**: For statistical data visualization.

## Installation
To install the required libraries, you can use the following pip commands:

```bash
pip install numpy pandas matplotlib seaborn
