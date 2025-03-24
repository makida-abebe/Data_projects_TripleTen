# TripleTen Business Analytics Project - Conversion and Retention Rates

### The Prompt
The executive team at an e-commerce company is interested in understanding how well the website is converting product page views into purchases. They have asked you to create a conversion funnel to better understand how users interact with the website. The company wants you to build acquisition cohorts based on the month of a user’s first purchase, and they want you to track cohort metrics month by month.

### The Data
The provided data was a raw transaction log spreadsheet including `'user_id'`, `'event_type'`: page view, shopping cart, or purchase, `'category_code'`, `'brand'`, `'price'`, and `'event_date'`.	Raw event activity spans September 2020 thru Februrary 2021. The brand and price of the product information was not pertinent to the conversion rate
and retention rate analysis.

### The Process
A unique UserID count was used to build the conversion funnel for the 3 events present in the raw activity data: page view, open shopping cart, and complete purchase. 



User cohorts were created based on the first month individual users made a purchase. VLookup was used to find the first_purchase date of the customer that was listed for each product page event in the dataset. The columns first_purchase_month and cohort_age in the purchase activity table were then created to build monthly cohorts.



Retention rates were calculated for each month, based on whether customers made a purchase in that month and calculating the age or number of months since their first purchase. 



### Results
The total conversion rate of customers from viewing a page to making a purchase is just over 10%. There is certainly room to make improvements in how the company is converting page views into product purchases. More specifically, the shopping cart to purchase conversion rate is about 36% while the view to shopping cart conversion is only 29%. The company should consider ways to get more customers to put items in shopping carts, which will help boost overall purchase numbers. Perhaps an emailed discount code or a holiday sale on popular items could be explored as methods to boost conversion rates at all stages. 

Retention rates are strongest in the first month of each cohort (when the cohort is age 1). However, rates quickly drop off (by about 50%) as the cohorts age. The company saw retention rates drop through the holiday months of November and December, so more investigation is needed in why customers did not return for holiday shopping. The company could also consider a campaign of reminder emails every 20-30 days that show customers a selection of products tailored to them in an effort to get them to return to the site and boost retention.

### Project Link
