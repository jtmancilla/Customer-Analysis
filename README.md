# Project: Arvato Bertelsmann Customer Analysis


## Project Motivation

The goal of this project is to predict which individuals are most likely to convert into becoming customers for a mail-order sales company in Germany.

There is a blog post for this project hosted in [Medium](). In this blog, we dive into:

1. **Customer Segmentation Report** - This analyzed demographics data for customers of a mail-order sales company in Germany, comparing it against demographics information for the general population. This used unsupervised learning techniques to perform customer segmentation, identifying the parts of the population that best describe the core
customer base of the company. 

2. **Supervised Learning Model** -This used the previous analysis to build a machine learning model that predicts whether or not each individual will respond to the campaign.



## Table of Contents:

1. [Installation](#installation)
2. [Data Files](#files)
3. [Instructions](#instructions)
4. [Results](#results)
5. [Acknowledgements](#acknowledgements)


## Installation: <a name="installation"></a>
Download and Install Anaconda distribution of Python. The code should run with no issues using Python versions 3.7.3.



## Data Files: <a name="files"></a>

There were four data files provided by Arvato for this project. The last file was created by the user. As part of the terms and conditions of Arvato, the files cannot be shared in this repository. However, they can be described below.

1. `Udacity_AZDIAS_052018.csv:` - Demographics data for the general population of Germany - 891,211 persons (rows) x 366 features (columns)

2. `Udacity_CUSTOMERS_052018.csv:` - Demographics data for customers of a mail-order company - 191,652 persons (rows) x 369 features (columns)

3. `DIAS Attributes - Values 2017.xlsx:` a data dictionary of the columns including description, possible values, and what the values mean.

4. `DIAS Information Levels - Attributes 2017.xlsx:` indicates the information level for each column (Person, Household, Building, etc)

5. `mailout_train.csv` - Demographics data for individuals who were targets of a marketing campaign (train) - 42,982 persons (rows) x 367 (columns)

6. `mailout_test.csv` - Demographics data for individuals who were targets of a marketing campaign (test) - 42,833 persons (rows) x 366 (columns)

7. `features.csv` - Contains a summary of properties for each demographics data column created by the user - 366 features (rows) x 4 (columns)



## Instructions: <a name="instructions"></a>

Since the data files are not available publicly, the Jupyter notebook is just for exploration. 

- Part 0 Capstone Project Arvato Project Workbook - Data expoloration and preprocessing
- Part 1 Customer Segmentation Report - Analysis of customers
- Part 2 Supervised Learning - Classification model



## Results <a name="results"></a>
The detailed analysis of the results can be read in [this Medium post](https://medium.com/@mei.eisenbach/arvato-bertelsmann-customer-analysis-ae1aac59a1ef) or in Arvato Report.pdf.


## Acknowledgements <a name="acknowledgements"></a>

Must give credit to Arvato Financial Solutions and Udacity for the challenge and data.