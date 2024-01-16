# Data-Science-Job-Posting-on-Glassdoor

## Overview
This respository contains the code and documentation for a data cleaning project . The goal of this project is to process and clean raw data to make it suitable for analysis and visualization.

## Table of Contents
- [Background](#background)
- [Data Cleaning Process](#data-cleaning-process)
- [Features](#features)
- [Requirments](#requirements)
- [Usage](#usage)
- [License](#license)



## Background
Data cleaning is a crucial step in the data analysis pipeline. This project focuses on cleaning and preprocessing raw data obtained from **Data File :**[ Job Posting on Glassdoor](https://github.com/AbdallahOdeh2/Data-Science-Job-Posting-on-Glassdoor/blob/9e979937162c74817f1522be1cad2a592d1bc18f/Uncleaned_DS_jobs.csv). The dataset contains columns explanation are as follows,
Job Title: Title of the job posting
Salary Estimation: Salary range for that particular job
Job Description: This contains the full description of that job
Rating: Rating of that post
Company: Name of company
Location: Location of the company
Headquarter: Location of the headquater
Size: Total employee in that company
Type of ownership: Describes the company type i.e non-profit/public/private farm etc
Industry, Sector: Field applicant will work in
Revenue: Total revenue of the compan
, and the goal is to prepare it for further analysis by addressing issues such as missing values, outliers, and inconsistencies.

## Data Cleaning Process
- **Data Extraction:** Raw data is obtained from [Kaggle](https://www.kaggle.com/datasets/rashikrahmanpritom/data-science-job-posting-on-glassdoor/data?select=Uncleaned_DS_jobs.csv)
- **Handling Missing Values:** You can consider this initial phase as the first step when starting to clean any dataset, as it provides an overview of what you will encounter later in the process. Fortunately, in our dataset, there are no missing values, simplifying the initial cleaning steps.
- **Duplicates:** certainly you may find any duplicates in many datasets and that may cause a wrong vision to your data especially when you want to make viz or apply some ML on it , Feel good because our data also not having any duplicates
- **Extract the main points:** In our data you will find some colummns contain `number + string` like `company name` so IF you are doing ur cleaning on `Excel` so u may use `left` or `right` function to extract the name of the company that depnd on company name but if ur using `Python` so you can split the name of comapny then specify the position of comapny name , also in `job title` you will find that many jobs related to the same position but it named differently so, in `excel` apply filter on column then see the unique title then use `formula` or u can make a small table contains 2 columns `title,shortcut` then use `VLOOKUP` but I go with `formula` to increase my knowlwdge on it `believe me the formula will be to long :)` on the other hand `python` u can make small `function` to replace the title with another or using nested `if` last but not least you will find columns with datatype `object` but it must be `numeric` but because it contains many characters , so u will apply the `split` method and `replace` to remove some char after that u will detect the position of the number the extract them.

## Features
The project data came as a `CSV` file [Data](https://github.com/AbdallahOdeh2/Data-Science-Job-Posting-on-Glassdoor/blob/c7af098beb6ad1b3ab350fa3801c1d0b11c409a6/Uncleaned_DS_jobs.csv) to execute and document the cleaning process.\

## Requirments
To run the data cleaning scripts, ensure you have the following software and libraries installed:
* Python
* Numpy
* Pandas
* Excel or Spreadsheet
  
## Usage
To clean the data, run the [Python Code](https://github.com/AbdallahOdeh2/Data-Science-Job-Posting-on-Glassdoor/blob/4915975c207ade761423c8a5b7c2fc24cfca604b/Cleaned_data.ipynb) or explore the step-by-step process in Excel file [Excel File](https://github.com/AbdallahOdeh2/Data-Science-Job-Posting-on-Glassdoor/blob/4915975c207ade761423c8a5b7c2fc24cfca604b/Uncleaned_DS_jobs.csv)

## License
This project is licensed under the MIT License.

Feel free to contact me `Abdallah` `abdallahodeh13@email.com` for any questions or feedback.

Happy cleaning!
    
