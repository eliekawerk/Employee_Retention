# Employee Retention

This repo contains jupyter notebooks for a data science classification project. We aim at building a machine learning model that can predict the employee retention rate for the HR department of a company.

The code in the notebooks was executed using python 2.7; the following python libraries were used throughout the project:

* numpy
* pandas
* matplotlib
* seaborn
* sklearn

[Data-Dictionary](Data-Dictionary.pdf) contains the description for each feature present in the employee retention dataset.

## Project Structure

- **Section 1**: [Exploratory Data Analysis](1_Exploratory_Data_Analysis.ipynb)
- **Section 2**: [ABT Construction](2_ABT_Construction.ipynb)
- **Section 3**: [Model Training](3_Model_Training.ipynb)
- **Section 4**: [Project Delivery](4_Project_Delivery.ipynb)

## Project Context

Our client is the HR department at a large software company.

* They are rolling out a new initiative that they call "Proactive Retention."
* The idea is to use data to predict whether and employee is likely to leave.
* Once these employees are identified, HR can be more proactive in reaching out to them before it's too late.
*For this initiative, they only care about permanent (non-temp) employees.

## Our Role

The HR department has hired us as data science consultants. They want to supplement their exit interviews with a more proactive approach.

* They've asked their business intelligence analysts to provide us a dataset of past employees and their status (still employed or already left).
* Our task is to build a classification model using that dataset.
* Because our solution will be complementary to the existing one, and because there's no precedent, we do not have a quantifiable win condition. Just build the best model possible.

## Current Solution

Currently, their employee retention process is very retroactive. Once an employee leaves, he or she takes an "exit interview" and shares reasons for leaving. HR then tries to learn insights from that interview and make changes around the company accordingly.

This suffers from 3 main problems:

* The first problem with this approach is that it's too haphazard. The quality of insight gained from an interview depends heavily on the skill of the interviewer.
* The second problem is that they can't systematically aggregate insights across all employees who have left.
* The third problem is that they can't be proactive because they are using exit interviews to drive policy changes.


## Problem Specifics

It's always helpful to explicitly lay out the problem specifics before starting.

```
Deliverable: Executable model script
Machine learning task: Classification
Target variable: Status (Employed/Left)
Win condition: N/A (best possible model)
```


