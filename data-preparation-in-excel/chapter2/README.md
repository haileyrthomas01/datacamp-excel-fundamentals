## Chapter 2: Functions for Data Preparation
In this chapter, you’ll learn how to use text category functions to combine text strings with useful variables for better analysis. You will also utilize some of Excel's date and time functions, taking simple date columns to a new level.

## Assignments
### 2.1 - Equal Length
- Some values in the Customer State column could have unwanted characters due to a processing error with the customer information database.
- This could be an issue! You must use some text category functions to clean the data and continue the data preparation process.

### 2.2 - Joining Together
- Location data, such as the street, city, zip code, and state, dominate the information that DataCo has sent you regarding their customers.
- This data is all contained in different columns. Although some more specific fields, like street and zip code, would be useful for marketing or billing, it doesn't necessarily need to be split out.
- Would you conduct an analysis involving the customer's zip code or street name? There is more work to do on the Customers sheet! (Use =TEXTJOIN(", ",FALSE,___,___,___) and Protect Sheet)

### 2.3 - Dates and More
- DataCo is a supply chain company that receives many customer orders for products that must be delivered to different locations.
- This means that DataCo has to keep track of important date information, such as order or delivery dates.
- With this in mind, you can now create useful date columns and information related to dates that can be used for your analysis. (Use WEEKDAY(, ), =TODAY(), and =WORKDAY( ,))
