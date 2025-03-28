# TripleTen Data Storytelling Project - What is causing returns?

### The Prompt
What is causing the high number of returned orders at the Superstore? I will conduct an analysis for the CEO of Superstore to identify the causes of customer returns and strategies to reduce them. 

### The Data
The Superstore data includes three tables: Orders, People, and Returns. 

- Orders Dataset:   Order ID, Order Date, Ship Date, Ship Mode, Customer ID, Customer Name, Segment, Country/Region, City, State, Postal Code, Region, Product ID, Category, Sub-Category, Product Name, Sales, Quantity, Discount, Profit
- People Dataset: Regional Manager, Region
- Returns Dataset: Returned, Order ID
  
### The Process
To prepare for the analysis, I merged the Orders dataset with the Returns dataset. I then created a calculated field to label returned items as '1' and non-returned items as '0', facilitating the calculation of average return rates and the total number of returns.

During the data analysis, I took into account various contributing factors to the number of returns including: month of order, product category, state and region, and individual customers. I created 6 visualizations to highlight reasons why return rates are high at Superstore. I also considered whether there is a correlation between total sales and total returned order when examined by product subcategory. 

![Image](https://github.com/user-attachments/assets/832f9873-c040-4bb2-a066-5b60a700e669)


After developing the final version of the return rates dashboard, I created a Tableau Story presentation for the CEO of Superstore. This presentation concisely summarizes the findings from my analysis and features an interactive dashboard that allows for detailed examination of returns by region and product sub-category. To conclude, I proposed several actionable steps that Superstore could implement to effectively address and reduce the high number of returns. 

![Image](https://github.com/user-attachments/assets/d48cd38c-21bf-4130-96fa-3daf63cf9516)

### Results
Key Findings: 
  1. Return rates rise proportionally with increases in sales volumes, suggesting a systemic correlation. 
  2. Certain products display exceptionally high return rates, indicating specific issues with those items.
  3. California is one of the highest factors in the general return rates.
  4. No single category or sub-category consistently underperforms across all regions, yet numerous specific items exhibit extremely high return rates, occasionally reaching up to 100%.
  5. Some customers exhibit frequent repeat purchases coupled with high return rates, suggesting atypical behavior.

Recommendations:
  1. Conduct a thorough review of manufacturing processes and shipping protocols for products with high return rates to identify and rectify potential defects or inefficiencies.
  2. Engage directly with customers who have abnormal return patterns to discern whether returns are due to product issues or specific purchasing behaviors, and use this feedback to improve product quality or customer experience.
  3. Analyze and address factors contributing to high return rates in California through adjustments in logistics, marketing, or customer service.
  4. Identify and improve or discontinue specific products with exceptionally high return rates after a detailed item-by-item analysis.
  5. Monitor and engage with repeat customers who frequently return items, using targeted strategies like loyalty programs or personalized communication to understand and mitigate their concerns.


### Project Link
https://public.tableau.com/views/Sprint5StorytellingwithDataProject_17401143318720/TotalSalesvs_TotalReturns?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link  
