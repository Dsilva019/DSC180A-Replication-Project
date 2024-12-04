# DSC180A-Replication-Project
This repository contains all of the code that was utilized for the 2024-2025 UCSD Data Science Capstone Quarter 1 Ethical AI Replication Project. 

---
## Introduction
The goal of this project was to learn how to mitigate bias in machine learning models using IBM's AIF460 toolkit. The dataset that is being used to test the toolkit is extracted from the [Medical Expenditure Panel Survey (MEPS)](https://meps.ahrq.gov/mepsweb/) from [2015](https://meps.ahrq.gov/mepsweb/data_stats/download_data_files_detail.jsp?cboPufNumber=HC-181) and from [2016](https://meps.ahrq.gov/mepsweb/data_stats/download_data_files_detail.jsp?cboPufNumber=HC-192). In this project we test the toolkit's effectiveness in debiasing a Logistic Regression and Random Forest model when trying to predict a patient being high utilization or not.

---
## How to get Started

##### 1) Getting the code
- clone repository into your working directory:
    `git clone https://github.com/Dsilva019/DSC180A-Replication-Project.git`

##### 2.a) Setting up environment (Windows Users)
- create a working environment:
    `python -m venv venv`
- activate the working environment:
    `venv/scripts/activate`
- download the dependencies:
    `pip install -r AIF360_Files/requirements.txt`

##### 2.b) Setting up environment (Linux/Mac OS users)
- create a working environment:
    `python3 -m venv venv`
- activate the working environment:
    `source venv/bin/activate`
- download the dependencies:
    `pip install -r AIF360_Files/requirements.txt`
- install the necessary packages using pip
    `pip install matplotlib numpy IPython pandas seaborn sklearn aif360`

##### 3) Downloading the Data
- navigate to https://www.kaggle.com/datasets/nanrahman/mepsdata to find the data
- download the data as a .zip (it includes both h181.csv and h192.csv)
- extract the csv files into the same folder as the notebook



