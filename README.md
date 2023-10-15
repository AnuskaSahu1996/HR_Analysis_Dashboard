# HR_Analysis_Dashboard

📌 Project Assignment: Here I am submitting my last Project assigned as Task 3 "HR Analysis" by MeriSKILL.

📌 Project Purpose: The purpose of this analysis is to provide insight into effective employee management and help businesses meet their short-and long-term goals. It enables organization to measure the impact of a range of HR metrics on overall business performance and make decisions based on data. This Analysis helps to know about employee's performance, their satisfaction for the environment, reason of attrition, ratio of male and female etc.

📌 Data Exploration: Following the dataset, comprising various measurements as independent variables and one target variable, "Total Employee."

📌 Data Analysis: Our analysis insights and patterns to gather overall employees' details and information from different aspects and measurements.

📌 DAX Measures📈
Here are the DAX measures:

Total EMP = COUNTROWS('HR-Employee-Attrition')
Male = CALCULATE ([Total EMP],'HR-Employee-Attrition'[Gender]="male")
Female = CALCULATE ([Total EMP],'HR-Employee-Attrition'[Gender]="female")
% male = DIVIDE([Male], [Total EMP],0)
% Female = DIVIDE([Female], [Total EMP],0)
Total Attrition = COUNTROWS('HR-Employee-Attrition')
Attritionyes = CALCULATE ([Total Attrition],'HR-Employee-Attrition'[Attrition]="yes")
AttritionNo = CALCULATE ([Total Attrition],'HR-Employee-Attrition'[Attrition]="No")
%yes = DIVIDE ([Attrition yes], [Total Attrition],0)
%No = DIVIDE([AttritionNo], [Total Attrition],0)

📌 DAX Columns📊
overtimecal: This DAX is used to calculate the overtime working employees' total and percentage and relationship between age and overtime column.

Tasks to perform: 
🗑 Data Cleaning:

Deleting redundant columns.
Renaming the columns.
Dropping duplicates.
Cleaning individual columns.
Remove the Nan values from the dataset.
Check for some more Transformations.

📊 Data Visualization:

Insights: Below mentioned points are represented in different charts to reach the conclusion easily.

·        Plot a correlation map for all numeric variables
·        Overtime
·        Marital Status
·        Job Role
·        Gender
·        Education Field
·        Department
·        Business Travel
·        Relation between Overtime and Age
·        Total Working Years
·        Education Level
·        Number of Companies Worked
·        Distance from Home
![Screenshot (92)](https://github.com/AnuskaSahu1996/HR_Analysis_Dashboard/assets/144818919/ea10a384-1b8e-49c9-8e69-2188987fc2f0)

![Screenshot (93)](https://github.com/AnuskaSahu1996/HR_Analysis_Dashboard/assets/144818919/f60b67d8-014c-4aa5-9d99-50043a0d73de)

![Screenshot (90)](https://github.com/AnuskaSahu1996/HR_Analysis_Dashboard/assets/144818919/0ca832bd-579b-486f-aacc-02076ecc59c1)

Key Outcomes 📈🔑
Our project delivered valuable outcomes:
Insights: We uncovered insights to gather overall information about employees for the betterment and development of working environment.
Recommendations: we monitored the performance, opportunities, education, healthy lifestyle, skilled employees, so that we can found out where we are lacking.
Impact 🌟🏆
In essence, our project was part of the Meriskill internship, Task 3, aimed increasing the opportunities for employees so they can improve in every aspect and increase their skills and interest for work. 💡📢
