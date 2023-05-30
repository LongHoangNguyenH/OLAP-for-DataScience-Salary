# OLAP-for-DataScience-Salary


## Report
|Full name|Role|
|:--:|:--:|
| Nguyen Hoang Long| Leader |
| Dang Thi Tuong Vy| Member |
# Table of Content
1. [Introduction](#1-Introduction)
2. [SSIS](#2-SSIS)
3. [SSAS](#3-SSAS)
4. [DataMining](#4-DataMining)

## Introduction
Online Analytical Processing is software for performing multidimensional analysis at high speeds on large volumes of data from a data warehouse, data mart, or some other unified, centralized data store.
in this case we use Dataset about DataScience Salary to analyze.
This dataset include more than 50000 records, each record contain 29 columns like salary, title, tag, timestamp, ...
We collected this dataset from [Here](https://www.kaggle.com/datasets/jackogozaly/data-science-and-stem-salaries)

## SSIS
Based on the Data we collected we decide to devide our data into seven Dimentions
+ Company
+ Title
+ Tag
+ Time
+ City
+ Education
+ Level

Then we have to build each Data pipeline for each dimention
![Dim_Time image](./image/Dim_time.png "An optional title")

here is picture of schema


## SSAS

## DataMining
