# Python-Product-Sales-Analysis

## Business problem 

Hi,
Really hoping you could help me out with some analysis. This is quite short notice but I have a meeting with the executive team to update them on sales approaches for the new product line so I need this information as soon as possible.

We need to know:

- How many customers were there for each approach?
- What does the spread of the revenue look like overall? And for each method?
- Was there any difference in revenue over time for each of the methods?
- Based on the data, which method would you recommend we continue to use? Some of these methods take more time from the team so they may not be the best for us to use if the results are similar.

We don’t really know if there are other differences between the customers in each group, so anything you can tell us would be really helpful to give some context to what went well.

I need to report to the executive team in 4 weeks. You need to present to me before then so

I understand what is going on and what we do next.

Look forward to seeing your presentation.

## The data

The sales rep has pulled some data from their sales tracking system for us. They haven’t included numbers for how much time was spent on each customer, but there may be some other useful customer information in here.

The data only relates to the new products sold. As there are multiple different products, the revenue will vary depending on which products were sold.

You can find the data here. I will let you decide how to process it, just make sure you include all your decisions in your report.

The data hasn’t been validated, so make sure that you check it against all of the information in the table before you start your analysis.

### **product_sales.csv**
| Column | Description |
|--------|-------------|
| `week` | Week sale was made, counted as weeks since product launch |
| `sales_method` | Character, which of the three sales methods were used for that customer |
| `customer_id` | Character, unique identifier for the customer |
| `nb_sold` | Numeric, number of new products sold |
| `revenue` | Numeric, revenue from the sales, rounded to 2 decimal places |
| `year_as_customer` | Numeric, number of years customer has been buying from us (company founded in 1984) |
| `nb_site_visited` | Numeric, number of times the customer has visited our website in the last 6 months |
| `state` | Character, location of the customer i.e. where orders are shipped |
