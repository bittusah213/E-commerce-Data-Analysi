# E-commerce-Data-Analysi

## Description
######  This project was built to help the sales team understand why the month,years,days Performance was lagging in certain areas. It compares current vs previous date quantities, highlights bottom-performing countries, and reveals month-over-months trends by product types. It also give the deatials of dataset.

## Question
###### 1. How to find out total no. of records 
###### 2. How to find out total no. of columns?
###### 3. Display all column names ?

###### 4. All Column Names Description:-
###### InvoiceNo (invoice_num): A number assigned to each transaction
###### StockCode (stock_code): Product code
###### Description (description): Product name
###### Quantity (quantity): Number of products purchased for each transaction
###### InvoiceDate (invoice_date): Timestamp for each transaction
###### UnitPrice (unit_price): Product price per unit
###### CustomerID (cust_id): Unique identifier each customer
###### Country (country): Country name

###### 5. How to find out all missing values for each columns?

######  By understanding the data in a more descriptive manner,
###### we notice one thing:
###### Quantity has negative values, 
###### At this stage, we’ll just remove Quantity with negative values.

###### 6. First Show all Quantity has negative values records?
###### 7. Then find out total shape of Quantity has negative values records? [shape=10624]
###### 8. How to remove all Quantity records with negative values?
###### 9. Then find out total records shape ? [df_new.shape is  541909-10624=531285]

###### To calculate the total money spent on each purchase, 
###### we simply multiply Quantity with Unit Price:
###### amount_spent = quantity * unit_price

###### 10. After UnitPrice column insert new column Amount_Spent & also formula assigned?

###### In This dataset InvoiceDate column is string form so that:

###### 11. InvoiceDate column converts string format into datetime format?

###### 12.  We add a few columns after InvoiceDate that consist of the Year, Month, Day 
       and Hour for each transaction for analysis work.

###### 13. How to find out Top 5 customers with highest money spent records?
      Show Only 3 columns ['CustomerID','Country','Amount_Spent']

###### 14. Plotting bar chart : How many orders (per month)?

###### 15. Plotting bar chart : How many orders (per day)?

###### 16. Plotting bar chart : How many orders (per hour)?

## Process
### Read the data using the python(pandas).
### Slove the all question pandas libray it give a result we can understand easly.
### all the visual represented by the help of python(matplotlib)
### plotted by the class pyplot the describe the visual.

### Visual
