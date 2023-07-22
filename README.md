# **Investigate Hotel Business using Data Visualization**

## **Background**
It is very important for a company to always analyze its business performance. On this occasion, I will explore more business in the hospitality sector. The purpose of this project is analyzing customer behaviors in hotel business such as average number of hotel bookings each month and cancellation rates based on various factors. This project's workflows including data preprocessing, statistical descriptive analyzing and data visualization.

## **Goal**
Find out how hotel’s customers behave in making hotel reservations, and how they relate to the cancellation rate of hotel bookings.

## **Objective**
Insights will be presented in the form of visualization data to make it easier to understand and more persuasive.

## **Data**
The dataset contains 119.390 data rows and 29 features of customer behavior features who made hotel bookings.

## **Data Source**
If any of you curious about the database or wanna to try by yourself, feel free to access the database from [download here](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand).

## **Tools**
I've used various tools on this project. I've used jupyter as notebook, python as programming language, combination of matplotlib and seaborn library to generated data visualization.

## **Contents**

### **Data Preprocessing**
This process including identifying missing value, correcting unsuitable value, correcting dtypes and drop unnecessary data rows.

### **Monthly Hotel Booking Analysis Based on Hotel Types**
Including the calculation processes to get average number of hotel bookings per month based on hotel types and generate it's data visualization. I normalizes the data which for 'september' and 'october' has different ammount of years than others.

### **Impact Analysis of Stay Duration on Hotel Bookings Cancellation Rate**
Including the calculation processes to get cancellation rate of hotel bookings per stay duration based on hotel types, generate it's data visualization and looking for it's data trend according this metrcis.

### **Impact Analysis of Lead Time on Hotel Bookings Cancellation Rate**
Including the calculation processes to get cancellation rate of hotel bookings per lead time based on hotel types, generate it's data visualization and looking for which month is the lowest and highest cancellation rate.

## **Conclusion**
    1. According to result of my analysis, june and july are the peak season of hotel bookigs it has highest average number of hotel bookings than other months. But, there is another growth in december. It could be happen because june and july are holiday month for students in Indonesia, and december is end year's holiday month.

    2. For another insights, there is positive positive trend on cancellation rate of hotel bookings per stay duration. The longer customer's plan to stay, the higher cancellation rate. It could be happen because human error when customer did reservation or they cancelled the vacation plan because any urgent reasons that they couldn't turn down.

    3. Also, 1 month lead time has the lowest cancellation rate and 11-12 months lead time has the highest cancellation rate. The reason is look simmiliar like cancellation rate per stay duration.




