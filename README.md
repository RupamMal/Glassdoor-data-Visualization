# Glassdoor-data-Visualization

## About Glassdoor

![glass](https://upload.wikimedia.org/wikipedia/commons/e/e1/Glassdoor_logo.svg)

Glassdoor is a website where current and former employees anonymously review companies. Glassdoor also allows users to anonymously submit and view salaries as well as search and apply for jobs on its platform.Glassdoor launched its site in 2008 , as a site that “collects company reviews and real salaries from employees of large companies and displays them anonymously for all members to see,” according to TechCrunch. The company then averaged the reported salaries, posting these averages alongside the reviews employees made of the management and culture of the companies they worked for—including some of the larger tech companies like Google and Yahoo. The site also allows the posting of office photographs and other company-relevant media.

## Dataset description

This dataset contains job postings from Glassdoor.com from 2017-2018. It includes features such as job title, salary estimate, job description, rating, company name, location, headquarters, size, founded, type of ownership, industry, sector, revenue, competitors compile a list of the most important features in this dataset. 

```
job_id: The unique identifier for the job posting (Numeric)
job_state: The state where the job is located (String)
same_state: A binary indicator of whether the job is in the same state as the person looking at the job (String)
age: The age of the person looking at the job (Numeric)
python_yn: A binary indicator of whether the person looking at the job knows Python (String)
R_yn: A binary indicator of whether the person looking at the job knows R (String)
spark: A binary indicator of whether the person looking at the job knows Spark (String)
aws: A binary indicator of whether the person looking at the job knows AWS (String)
excel: A binary indicator of whether the person looking at the job knows Excel (String)
job_simp: A simplified job title (String)
seniority: The seniority of the job (String)
desc_len: The length of the job description (Numeric)
num_comp: The number of competitors for the job (Numeric)
```

---

# Project Repository: Data Analysis & Data Visualization

## Table of Contents
- [Overview](#overview)
- [Data Analysis](#data-analysis)
  - [Introduction](#introduction)
  - [File Description](#file-description)
  - [Usage](#usage)
- [Data Visualization](#data-visualization)
  - [Introduction](#introduction-1)
  - [File Description](#file-description-1)
  - [Usage](#usage-1)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

This repository contains two distinct projects: a data analysis project using Power BI and a data visualization project implemented in a Jupyter Notebook. These projects aim to provide insightful data visualizations and predictive analytics in the domain of job salaries.

## Data Analysis

### Introduction

The data analysis project is created using Power BI to visualize and analyze job market data obtained from Glassdoor. This interactive dashboard provides valuable insights into salary trends, job availability, and other key metrics.

### File Description

- `Glassdoor Dashboard.pbix`: The Power BI file containing the data analysis project.

### Usage

1. Download the `Glassdoor Dashboard.pbix` file.
2. Open the file using Power BI Desktop.
3. Explore the various visualizations and insights provided in the dashboard.

## Data Visualization

### Introduction

The data visualization project uses machine learning techniques to predict salaries based on various job-related features. The model is built and evaluated in a Jupyter Notebook.

### File Description

- `Salary prediction.ipynb`: The Jupyter Notebook containing the code for data preprocessing, model building, evaluation, and prediction.

### Usage

1. Ensure you have Jupyter Notebook installed in your Python environment.
2. Download the `Salary prediction.ipynb` file.
3. Open the file using Jupyter Notebook.
4. Run the notebook cells to execute the code and see the predictions.

## Installation

For the data visualization project, you need to have the following Python packages installed:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- Jupyter Notebook

You can install these packages using pip:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn notebook
```

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to create a pull request or open an issue.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or inquiries, please contact:
- **Name**: Rupam Mal
- **LinkedIn**: [Rupam Mal](https://www.linkedin.com/in/rupam-mal-9ba31721a/)

---
