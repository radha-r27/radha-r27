### Capstone On E-Commerce BA - Dashboards with Power BI ###

<img width="661" alt="image" src="https://github.com/radha-r27/radha-r27/assets/144864829/c7694361-fed8-43d6-b3b0-929c4c50ea15">


<img width="663" alt="image" src="https://github.com/radha-r27/radha-r27/assets/144864829/f1cd8593-70ff-4910-a7f1-5a1eed547606">


<img width="659" alt="image" src="https://github.com/radha-r27/radha-r27/assets/144864829/f3342744-f9cd-40d1-8c3d-bb4201d3cefa">


<img width="661" alt="image" src="https://github.com/radha-r27/radha-r27/assets/144864829/71a49fb0-20fa-48ad-b2d9-dcc8453bbbb8">


<img width="661" alt="image" src="https://github.com/radha-r27/radha-r27/assets/144864829/e1c1be33-182e-4670-a51c-fb435254cb2f">


<img width="662" alt="image" src="https://github.com/radha-r27/radha-r27/assets/144864829/85353931-93fc-4ca1-a79c-aa5a3f48fa13">




### Customer Base Analysis for Shopee Brazil ###
**OBJECTIVE**

SHOPEE BRAZIL is looking to create a customer base, enhance the customer experience and recommend relevant
products to the customers and increase revenue as per the information present.
The aim of this Capstone is to assume the role as a Data Analyst and to provide important insights that can be helpful to have a better understanding of their
customers.

**Description of Dataset**

The two datasets used in this capstone are Shoppe Brazil's Customer Dataset and Purchase Dataset.

**_Customer Dataset:_**

The data provided details of customer demographics such as their country, age, gender, their income. The dataset has a size of 1000 rows


**_Purchase Dataset_**:

This dataset contains details of their order information such as Order No., products that they have purchased, quantity, its price, discount % given
to that product, tax percentage, Order date, shipment date, and shipping cost. The dataset has a size of 50,000 rows

**_Inference from the Main Dataset_**:

Although the dataset belongs to Shopee, Brazil its customers are from Brazil, Chile, Columbia, and Mexico. Purchase table contains the Sales
that happened in a span of 4 years from 2019 to 1st Jan 2023

**Schema And Table Diagram**:

<img width="616" alt="image" src="https://github.com/radha-r27/radha-r27/assets/144864829/20e31cf7-7d95-46a8-b381-4a257d71a500">

<Br></Br>

**Data Extraction**:

Shopee Brazil contains two Datasets which are extracted from the Excel CSV file provided in the canvas.
The two datasets customer.csv and purchase.csv are extracted using the Import from Text/CSV option available in Power BI

**Data Cleaning**:

 <li> Changed the type of column Income in Customer dataset to Fixed Decimal Number ($)</li>
 <li> Changed the type of Order date and Shipping Date columns to Date datatype</li> <br>

**Data Transformation**:
 <li> Columns are added in Customer Dataset to: </li>
       &nbsp &nbsp &nbsp &nbsp &nbsp1. Calculate the Total Purchases made by the customer <br>
       &nbsp &nbsp &nbsp &nbsp &nbsp2. Group the age rangewise Eg.  Age group 10-20, 20-30, 40-50, 60-70 etc <br>
       &nbsp &nbsp &nbsp &nbsp &nbsp3. To split the Income range in groups of 25k <br> <br>
  <li> Columns are added in Purchase Dataset to: </li>
       &nbsp &nbsp &nbsp &nbsp &nbsp1. Calculate the value of product price & quantity <br>
       &nbsp &nbsp &nbsp &nbsp &nbsp2. Calculate the discount amount  <br>
       &nbsp &nbsp &nbsp &nbsp &nbsp3. Calculate the amount after discount <br>
       &nbsp &nbsp &nbsp &nbsp &nbsp4. Calculate the Taxable amount based on tax percentage  <br>
       &nbsp &nbsp &nbsp &nbsp &nbsp5. Calculate the Sales value for the order   <br>
<br>

**Analysis and Insights**:

   **1._General Observations:_**
        <li> Customer base is spanned across 4 countries with a total of 1000 customers in 4 years </li>
        <li> Among the 4 countries, Columbia has the highest sales and highest customer base.</li>
        <li> The total purchase by Gender is higher in Columbia </li>
        <li> The income range of 25K-50K holds higher number of customer base and higher sales value</li> 
        <li> The income range <25K holds lowest customer base and lowest sales value</li>
        <li> Customer base belong to Age Group of 50-60,20-30,40-50 are Top 3 contributors of Sales</li>
        <Br></Br>
    **2._Sales by Gender:_**
     <Br></Br>
             Male accounted for 50.35% of Sales.﻿﻿﻿﻿Total Sales was higher for Male (13,94,80,104.16) than Female (13,75,43,537.79)
﻿﻿             ﻿﻿Colombia in Gender Male made up 14.64% of Sales.﻿﻿﻿﻿Average Sales was higher for Male (3,48,70,026.04) than Female (3,43,85,884.45)
      <Br></Br>
     **3._sales by Income Range:_**  <Br></Br>
             Customers having income between 25K-50K contributes highest sales in total sales value followed by 125K-150K & 50K-75K.Lowest spending
             nature is observed for customers with income range <25K in all the countries. Customers in the income range 50K-75K  produces highest 
             sales in Chile and Mexico. The customers with income range 25K-50K are potential customers in Colombia where as 125K-150K are for Brazil.




                
