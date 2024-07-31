# Comparison-of-Region-Based-on-Sales-using-Tableau

Description:
The director of a leading organization wants to compare the sales between two regions. He has asked each region operators to record the sales data to compare by region. The upper management wants to visualize the sales data using a dashboard to understand the performance between them and suggest the necessary improvements.

Objective: 
Help the organization by creating a dashboard to visualize the sales comparison between two selected regions.

Datasets: 
Sample Superstore

Steps to Perform: 
1. Select Sample Superstore as Dataset  
    1. Use Sample Superstore Dataset
    2. Select Data
    3. Use Group by from Data Source Table on a Folder to create a folder to segregate the required data for Customer Name and        Order ID inorder to organize the data thoroughly.
2. Create a hierarchy called Location for the variable Country. 
3. Create two parameters: Primary Region and Secondary Region with all regions listed in them. Here, primary and secondary   
   region are the two regions where the sales are being compared.
    1. Create Parameters for Primary Region and Secondary Region
    2. Create a Calculated Field for both Primary Region and Secondary Region
4. Create a First Order Date
    1. Create a Calculated Field and name it as the First Order Date
5. Create a dashboard
    1. Align all sheets in the dashboard
6. Partition the dashboard to display the below details of Primary Region and Secondary Region
    First Order Date
    Total Sales
    Average Sales per Order
    No. of Customers
    No. of Orders
    No. of Products in Sale
