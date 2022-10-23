1. Introduction
High-level information such as: number of panelists each day, can be used in order to identify outlier periods by using simple transformations and indexes. The project is a practical example of identifying outlier months based on number of participants for each day in order to assure the data quality. 

2. Purpose
The project was aimed to find a way to spot outlier months in regard to number of panelists (unique users per day). Two measures were used: Coefficient of variation - which can be used to identify months with abnormal variability of number of users as well as Forecasted Proportional Index (FPI) – the simple measure created for the purpose of this project. The rationale behind new measure, was to create index which will take in consideration the fact that each month can contain different number of days (due to the data issues or missing data).

 FPI can be understood as: 

![alt text](https://github.com/bohaterewicz/Forecasted-Proportional_Index-new-measure-for-high-level-data-quality-assurance/blob/main/FPI.png)


Where: p = number of users; N = number of days and N' = number of days from the following month

3. Dataset Information
Original dataset was obtained by calculating daily unique users from one of the biggest retail stores in the USA. Due to disclose data policy, the synthetic dataset has been created, having similar distributional properties as original data, while having different values.

