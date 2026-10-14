# MODULE-EVALUATION-1-MONTHLY-ASSIGNMENT HEALTHCARE DATA ANALYSIS AND INSIGHTS
MONTHLY ASSIGNMENT MODULE EVALUATION 1 MONTHLY ASSIGNMENT
Data cleaning with powerquery
filed missing value month with sep using CTRL+F and year by =AVERAGE function and using find and replace
determine most frequently value of smoker, hospital tire, and city tire using powerquery
filled missing STATE ID with UNKNOWN using FIND AND REPLACE
Split customer names as TITLE, FIRSTNAME,LAST NAME using FALSH FILL AND CONCATENATE function
create new colum of medical examination
check inconsistencies heart issue and smoker with power query
create new colum weight status using =IFS(B2<18,"underweight",B2<=24.9,"normalweight",B2<=29.9,"overweight",B2>=30,"obesity")
create new column diabetes using =IFS(C2<5.7,"normal",AND(C2>=5.7,C2<=6.4),"prediabetes",C2>=6.5,"diabetes")
Merge year month and date using =DATE(B2,MONTH(1&C2),D2)
AGE Calculation by  =DATEDIF(J3,DATE(2023,6,8),"y")
fromat charges using format number
create new sheet using VLOOKUP eg: for first name =VLOOKUP('customer name'!A2,'customer name'!A:F,5,FALSE)
for BMI VLOOKUP('medical examination'!A2,'medical examination'!A:K,2,FALSE
for HBA1C VLOOKUP('customer name'!A2,'medical examination'!A:M,3,FALSE)
crate pie, donut, column, bar chart using inserting pivot table and with the help of table insert pivot charts
create scatter chart uisng the table arrey
created dash board uisng the charts and created slicers
