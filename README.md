# athletic_sales_analysis
Challenge 5 - UNC-VIRT-AI-PT-11-2023-U-LOLC
# Resampling and Melting DataFrames

In this activity, you'll use the `resample` function to down sample time series data and the `melt` function to reshape a DataFrame from a wider form to longer form.

## Instructions

### Using the `resample` Function

1. Use the provided code to read in the athlectic_sales` CSV file into a DataFrame, clean the data, convert the "date" column to a datetime object, and drop any "datetime" values that didn't get converted to a datetime object.

2.# Display the 2020 sales DataFrame

3. Check the 2020 sales data types.

4. Combine the 2020 and 2021 sales DataFrames on the rows and reset the index.athletic_sales_2020_2021 = athletic_sales_2020.join(athletic_sales_2021,lsuffix='_2020',rsuffix='_2021')

5. Convert the "invoice_date" to a datetime datatype

6. Confirm that the "invoice_date" data type has been changed

7. Show the number products sold for region, state, and city.

8. Show the total sales for the products sold for each region, state, and city. Rename the "total_sales" column to "Total Sales"

9. Rename the "units_sold" column to "Total_Products_Sold".

10. Filter the sales data to get the women's athletic footwear sales data.

11. Show the total number of women's athletic footwear sold for each retailer, region, state, and city.Rename the "units_sold" column to "Womens_Footwear_Units_Sold"

12. esample the pivot table into weekly bins, and get the total sales for each day & week
