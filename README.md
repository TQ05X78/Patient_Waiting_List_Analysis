# Patient_Waiting_List_Analysis

## 📚 About Data

Healthcare Data - Wait List, Objective is to track current status of waiting list and Analyse historical monthly trend of waiting list in inpatient & outpatient categories. This Dataset contains two types of categories first one is inpatient and another is outpatient.

Inpatient - A patient who stays in a hospital while under treatment.
Outpatient - A patient who receives medical treatment without being admitted to hospital.


This dataset contains csv files, one for each year(2018 to 2021).
The row count of Inpatient data is 182136 and the Outpatient data contains 270983.



## 💡 Highlights

- Total waiting list for the current month is 709K.
- Waiting List for the last(previous year) for the same monthn is 640k,this helps to find out how we are performing in terms of last year.
- Average Waiting list for bifurcation between outpatient,inpatient and day cases waiting list.
- Average Waiting list for outpatient is 72%, for day case 17% and for inpatient 11%.
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

Produced a 2-pager dashboard using Power BI:

![Screenshot from 2023-12-26 18-17-59](https://github.com/TQ05X78/Patient_Waiting_List_Analysis/assets/66067511/af225587-ef2c-43cb-9b09-9629d099f017)

![Screenshot from 2023-12-26 18-18-14](https://github.com/TQ05X78/Patient_Waiting_List_Analysis/assets/66067511/b596b1e9-ccb8-4991-b720-49138c9adee4)


