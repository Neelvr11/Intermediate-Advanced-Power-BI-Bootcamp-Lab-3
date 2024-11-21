# Intermediate-Advanced-Power-BI-Bootcamp-Data Model
Skillsoft - Data Society conducted a 4-day Intermediate/Advanced Power BI Bootcamp.

# Design a Data Model

![image](https://github.com/user-attachments/assets/6ae2ca94-2db1-4764-bb3a-0b2fa41b5484)

![image](https://github.com/user-attachments/assets/22e072e9-f21d-48f9-80a1-865ce8f76adb)

**Relationships and Cardinality**

![image](https://github.com/user-attachments/assets/d418b4a7-6739-482a-bca2-6441a0ab4140)

**One-to-many (1:*) Many-to-one (*:1)**

![image](https://github.com/user-attachments/assets/ff9d46da-ff2b-4a70-87b6-b4493e6df58b)

**One-to-one (1:1)**

![image](https://github.com/user-attachments/assets/399f730c-426d-4463-a2ff-268e77a37320)

**Many-to-many (*:*)**

![image](https://github.com/user-attachments/assets/25446093-f3c4-42f0-b300-b2bed2146bf0)

**Inactive Relationships**

![image](https://github.com/user-attachments/assets/5cbbcf61-2eca-440f-8f10-f76fb5f5786b)

**CROSS FILTER DIRECTION**

![image](https://github.com/user-attachments/assets/84421db8-73a3-48e2-88b2-98ad1fb265f9)

# DATA MODEL BEST PRACTICES 

![image](https://github.com/user-attachments/assets/c89ce3ff-a65b-4bc8-81ee-38a6c8ec1148)

# Lab 3 - Design a Data Model (Relationships and Cardinality)

# 1) Organizing tables in the data model

Navigate to the Model view.	

![image](https://github.com/user-attachments/assets/5ffe8c09-dee0-40d4-bf20-13f4cf5010ef)

Organize the data tables separating the dimension tables placing them on the upper part of the model canvas and the Fact tables below.
	
![image](https://github.com/user-attachments/assets/8a0eb6d7-01c6-47cf-a27f-7999c6c1ad5d)

# 2) Creating relational connections between Fact and Dimension tables

Make table connections by connecting the corresponding Primary key from the Dimension tables to the Fact tables.

You can use the drag and drop method or from the Home tab select Manage relationships.

![image](https://github.com/user-attachments/assets/9a11ffc2-c011-4633-8179-9a23c278e2f8)

![image](https://github.com/user-attachments/assets/05ca4e72-d045-42e8-ba42-8ebaecc84e6d)


**Create the following connections**

![image](https://github.com/user-attachments/assets/54af3bbc-0c10-4b5d-abf4-8c45dc58c897)

![image](https://github.com/user-attachments/assets/d99ac374-0f98-4bf6-91b9-7c696a6a2718)


# 3) Validate filter propagation

Navigate to the Report View

From the Visualizations pane select the slicer visual and place the category field from the category table into the slicer field

Place the Subcategory field from the Subcategory table into the slicer field.

![image](https://github.com/user-attachments/assets/0ef64382-00b6-435a-9118-41ef06c0cd90)


Add a Table visual onto the canvas and Place the Region, Salesperson and Quantity field into the table visual

Test the slicers to ensure that the filter propagation is working correctly starting with the category slicer.
	

# 4) Create a doughnut chart showing the count segmentation of resellers based on product category

Place a doughnut chart onto the canvas with the Category field from the Category Table in the Legend and the Reseller field  from the reseller table in the values (Reseller should be aggregated to count)

![image](https://github.com/user-attachments/assets/de458c04-4266-4d71-8038-f874a393ddf3)

To get the correct values you will need to change the cross filter in the model view	

![image](https://github.com/user-attachments/assets/73ab0b67-3678-42d4-8566-8357d31fcd87)

Click on the connection string between the Reseller table and the Sales by Country Files

In the model view from the properties panel change the cross-filter direction from single to both and then apply changes

![image](https://github.com/user-attachments/assets/80814a3c-276c-4bcb-ad63-b48c9ebca3cd)


	



