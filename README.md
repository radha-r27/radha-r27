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
 <li> Changed the type of Order date and Shipping Date columns to Date datatype</li>

<Br></Br>
**Data Transformation**:

 <li> The following columns are added in Customer Dataset : </li>
      1. TotCustVal -> Calculates the Total Purchases made by the customer <br>
      2. age(bins) -> Groups the age rangewise Eg.  Age group 10-20, 20-30, 40-50, 60-70 etc <br>
      3. BinName    -> displays the Bin name according to age(bins) group <br>
      4. income_bins -> Split the Income binwise in groups of 25k for using in the visualization <br>
      5. IncomeBinName -> displays the income  ranging between 25K - 50K, 50K - 75K, 75K-100K, 100K-125K, 125K-150K based on the values from income_bins </li> <br>
<li> The following columns are added in Purchase Dataset : </li>
      1. Amtb4disc -> Calculates the value of product price & quantity <br>
      2. DiscountAmt -> Calculates Amtb4disc * discount percent given  <br>
      3. AmtAftDisc -> Calculates Amtb4disc - DiscountAmt  <br>
      4. TaxValue -> Calculates AmtAftDisc + Shipping cost multiplied by the tax percent  <br>
      5. OrderVal -> Calculates AmtAftDisc + TaxValue which gives the Sales value for the order   <br>
     </li>
<br>

**Analysis and Insights**:

   **1._General Observations:_**

<!---
radha-r27/radha-r27 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
