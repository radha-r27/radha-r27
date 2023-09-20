### Capstone On E-Commerce BA - Dashboards with Power BI ###

<img width="797" alt="image" src="https://github.com/radha-r27/radha-r27/assets/144864829/ede2793e-5ea9-4cac-ab10-9eeed6f989a0">

### Customer Base Analysis for Shopee Brazil ###
**OBJECTIVE**

SHOPEE BRAZIL is looking to create a customer base, enhance the customer experience and recommend relevant
products to the customers and increase revenue as per the information present.
The aim is to provide important insights which can be helpful for the company to better understand their
customers.

**Description of Dataset**

The two datasets used in this capstone are Shoppe Brazil's Customer Dataset and Order details.

**_Customer Dataset:_**

The data provided details of customer demographics such as their country, age, gender, their income. The dataset has a size of 1000 rows


**_Purchase Dataset_**:

This dataset contains details of their order information such as Order No., products that they have purchased, quantity, its price, discount % given
to that product, tax percentage, Order date, shipment date, and shipping cost. The dataset has a size of 50,000 rows

**_Inference from the Main Dataset_**:

Although the dataset belongs to Shopee, Brazil its customers are from Brazil, Chile, Columbia, and Mexico. Purchase table contains the Sales
that happened in a span of 4 years from 2019 to 1st Jan 2023

**Schema And Table Diagram**:

<img width="542" alt="image" src="https://github.com/radha-r27/radha-r27/assets/144864829/01c293a7-d7ec-4eca-9217-3b15751d38c9">

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
        <li> The income range of 25K-50K holds higher number of customer base and higher sales value </li>  
        <li> The income range <25K holds lowest customer base and lowest sales value  </li>
        <li> Customer base belong to Age Group of 50-60,20-30,40-50 are Top 3 contributors of Sales  </li>
