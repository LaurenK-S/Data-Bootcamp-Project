# Data-Bootcamp-Project

Data analysis project using Excel, PowerBI and Tableau

This project used a database of a company's employee data. The data was prepared and cleaned using Excel and then analysed using various formulas to answer business and financial questions such as "How much does the company need to make overall to cover the current salaries of it's employees", "How much does bonuses add to the salary cost?" and various other insights. Data visualisation was produced using excel, Power BI and Tableau.

### Q1. How much does the company need to make overall to cover the current salaries of its employees?
Solution using Excel: To cover all the current salaries of the employees (excluding bonus), the Company needs to make at least $14,100,110,721,276.00 to break even. To calculate this, all the salaries were added using the following formula:

=SUM(J7:J985)

To cover all the current salaries of the employees including bonus, the company needs to make at least $16,215,127,977,718.40 to break even. To calculate this, all the salaries plus bonus were added using the following formula:

=SUM(M2:M993)

### Q2. Which Country has the larger cost to run?

Solution Using PowerBI: 
<img width="155" alt="Q2" src="https://github.com/user-attachments/assets/be5cfa9b-4b83-4b34-b7f3-d85ecc651aff" />

### Q3. How much could the bonuses add to the salary cost?
Solution Using PowerBI:

<img width="179" alt="Screenshot 2025-05-07 015815" src="https://github.com/user-attachments/assets/b56ba599-8c93-4860-81c4-90c7da7b1768" />

<img width="137" alt="Screenshot 2025-05-07 015954" src="https://github.com/user-attachments/assets/5977fa1a-2306-4d99-b2f5-17f43338da10" />

### Q4. How many Employees are based in each country?
Solution using Excel:

To work this out the following formulas were used: =COUNTIF(N2:N993, "China"), =COUNTIF(N2:N993, "United States"), =COUNTIF(N2:N993, "Brazil").  

![Screenshot 2025-05-07 020552](https://github.com/user-attachments/assets/9c5e9b1b-1804-4c59-a964-27728b2b6e9d)

Solution Using Tableau:
This chart shows the count of employees in each city. 

![Screenshot 2025-05-07 020752](https://github.com/user-attachments/assets/ca20bb89-4290-41b0-88e5-8b3350a02146)

### Q5. What is the average age and salary for each country?

Solution using PowerBI:

![Screenshot 2025-03-13 120052](https://github.com/user-attachments/assets/2434ed97-0965-4ee0-ac8f-16b2b26e5308)












