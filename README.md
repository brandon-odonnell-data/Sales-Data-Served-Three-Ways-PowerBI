# Sales-Data-Served-Three-Ways-PowerBI
Tools and Languages: Power BI (see associated Excel and SQL projects)

Description and Intent: This analysis of electronics, appliances and accessories sales data from the USA, derived from twelve Kaggle CSV files spanning the entirety of 2019, was conducted to answer the files' associated series of questions (updated slightly to reflect different/additional queries):

What was the total sales amount for that year?

What was the best month for sales? How much was earned that month?

Which state had the highest total sales? How much?

Which city had the highest number of sales?

What time should we display advertisements to maximise the likelihood of customers buying products?

Which category of products is sold most often?

Which category of products generated the highest sales? How much?

Which product sold the most? Why do you think it sold the most?

The analysis was carried out entirely within Power BI, with additional intentions to 'serve the data' with two additional options: Excel and SQL.

Insights and Reporting: This analysis had been conducted previously in Excel and SQL, so there was some prior understanding of the data, as well as the option to cross-check calculated values. The six associated fields included:

Order ID: The number system used to keep track of orders. Each order receives its own Order ID that will not be duplicated. This number can be useful to the seller when attempting to find out certain details about an order such as shipment date or status.

Product: The product that has been sold.

Quantity Ordered: The total item quantity ordered in the initial order (without any changes).

Price Each: The price of an individual product.

Order Date: The date the customer is requesting the order be shipped.

Purchase Address: Prepared by the buyer, often through a purchasing department. The purchase order, or PO, usually includes a PO number, which is useful in matching shipments with purchases; a shipping date; billing address; shipping address; and the request items, quantities and price.

The data was loaded from the values processed previously during the Excel phase of this three-tier analysis. See the Excel version desciption of how this data was inspected and prepared for use. 

Extending on the dashboard created in Excel, presentation of this analysis made of use a map visual and an overview page with a summary of the important top values. Users could then navigate via buttons to separate pages with the relevant visualisations. Although not a requirement of the set of questions, slicers were added to the 'Location' and 'Product' pages to allow further consideration by month. An overall dark theme was used across the pages to give the uniform appearance of a set of official company colours. 

Finally, the posed questions were answered as follows:

What was the total sales amount for that year? $34,483,366

What was the best month for sales? How much was earned that month? December, $4,613,443

Which state had the highest total sales? How much? California, $13,711,290

Which city had the highest number of sales? San Francisco, CA

What time should we display advertisements to maximise the likelihood of customers buying products? Two peaks were identified at 12pm and 7pm. Advertising around 9am-10am to coincide with mid-morning breaks, as well as around 5pm-6pm to coincide with post-work breaks, may reach the highest number of potential customers engaging in online shopping. 

Which category of products is sold most often? Batteries

Which category of products generated the highest sales? How much? Laptops, $12,163,859

Which product sold the most? Why do you think it sold the most? AAA batteries (4-pack), followed by AA batteries (4-pack), charging cables and headphones. These products are the cheapest in the list and are also known to run out or failure regularly.
