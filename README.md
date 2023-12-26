# Patient_Waiting_List_Analysis

## 📚 About Data

Healthcare Data - Wait List, Objective is to track current status of waiting list and Analyse historical monthly trend of waiting list in inpatient & outpatient categories. This Dataset contains two types of categories first one is inpatient and another is outpatient.

Inpatient - A patient who stays in a hospital while under treatment.
Outpatient - A patient who receives medical treatment without being admitted to hospital.


This dataset contains csv files, one for each year(2018 to 2021).
The row count of Inpatient data is 182136 and the Outpatient data contains 270983.



## 💡 Highlights

- Total waiting list for the current month.
- Waiting List for the last(previous year) for the same monthn so that we can find out how we are performing in terms of last year.
- Average Waiting list for bifurcation between outpattient, inpatient and day cases waiting list.
- Relationship between age profile and the time band.
- Top-5 average wait list by speciality.
- Monthly trend analysis on the basis of inpatient day cases and outpatient.

## ✏️ Data Wrangling

Conducted simple data wrangling and data cleaning:
- Removed rows with missing values
- Cleaned `Time_Bands` and `Age_Profile` columns
- Exclude rows with "Blank" values in Speciality column
- Append both Inpatient and Outpatient data together for analysis purpose.


## 📊 Visualization

Produced a 1-pager dashboard using Tableau.

Power BI: 

