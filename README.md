# E-commerce-Sales-Transactions-Datas

The dataset appears to be from an e-commerce platform, containing records of customer purchases. It includes details such as order ID, product name, quantity, price, and order date. This structured data can be used to analyse sales trends, product popularity, and customer purchasing behaviour over time.

The project was completed in three phases:

Data Cleaning


Visualization and Conclusion

Tools Used:

Microsoft Excel
MySQL
Power BI

## Data cleaning:-

* Upload the dataset in the powerquery for verifing and cleaning porpus


![1  Update header](https://github.com/user-attachments/assets/befb2863-f340-46be-ae97-b0b11e2a6af0)

* The dataset’s column headers were updated for better clarity and readability. Abbreviations and lowercase names were replaced with standardized, properly formatted titles like Transaction_Id, User_Id, Product_Id and Category to ensure consistency across the dataset.

![2  Duplicates - Transaction _ID](https://github.com/user-attachments/assets/44427281-378e-40af-a631-a946cee7d87f)

![2 1 update product ID](https://github.com/user-attachments/assets/85951230-e970-4438-a048-8bce201d62c2)

* Duplicate values check: No duplicate values were found for Transaction_ID. However, one duplicate value was detected for Product_ID. To ensure uniqueness, the Product_ID has been updated using suffixes like /1, /2, etc.

![3  change price and discount with currency](https://github.com/user-attachments/assets/5df7300f-ea66-40f4-8600-55066e265c49)

* Modify the Price and Discount column types to display values in currency format.

![image](https://github.com/user-attachments/assets/7987ae6d-d89e-4692-87be-563c04a05a3c)

* change transaction time column with type of date

## Data Analysis

1)	Create “ecommerce” database in SQL and upload the data frame as well.

   ![image](https://github.com/user-attachments/assets/4de12128-b22a-455b-926e-79c495c5f352)

   Use table"













