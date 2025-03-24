# TripleTen Restaurant Analysis Project - Zomato Restaurant App

### The Prompt
Zomato is a multinational restaurant aggregator and food delivery company. As your first assignment as a junior analyst, you’re given several test datasets to analyze the business performance of restaurants and customers registered in the service. I choose to focus on a Restaurant Analysis Segmentation. 
My analysis will answer Three questions:
  1.	Restaurants serving certain types of cuisine generate higher revenue than others.
  2.	Higher-rated restaurants will have significantly higher revenue compared to lower-rated ones.
  3.	Restaurants with a higher average cost per menu item generate more revenue.


### The Data
I used two provided datasets with information on over 140,000 individual restaurants, and over 150,000 unique orders for this Analysis. 

Orders dataset:

![Image](https://github.com/user-attachments/assets/5ef5f8c8-245e-45da-89ff-ef8edede3903)

Restaurant dataset: 

![Image](https://github.com/user-attachments/assets/65f75916-dbb3-4cd2-9035-bcb294f5efb6)


### The Process
For my project on analyzing restaurant performance based on various factors, the process began with integrating data from two primary sources: restaurant details and order records. I merged these tables effectively, a task that required converting the 'R Id' column from a decimal to an integer in the orders dataset to accurately match the 'Id' column in the restaurant dataset. Following the merge, I cleaned the data to ensure the integrity and uniformity of the datasets involved, which included replacing blanks with null or zero as appropriate.
The analytical phase was structured around three primary hypotheses. The first hypothesis examined whether specific cuisines generate higher revenues than others, positing that popular or premium-priced cuisines might affect overall profitability. The second hypothesis explored the correlation between restaurant ratings and revenue, based on the assumption that higher-rated establishments attract more customers, thus generating higher sales. The third hypothesis evaluated the effectiveness of pricing strategies, analyzing whether restaurants with higher menu prices achieve higher revenues, indicative of an upscale dining preference.
The analysis plan was methodically laid out to tackle each hypothesis with a clear set of objectives and approaches: from analyzing total revenue across different cuisines, examining the relationship between ratings and revenue, to comparing revenue across various pricing tiers. The outcome sought to identify trends and patterns that could inform effective pricing strategies and operational improvements, especially for high-cost, low-revenue scenarios like the KOHINOOR HOTEL.
To visually articulate the findings, I planned an interactive dashboard that allows exploration of revenue trends across different dimensions. The visualizations were designed to include bar charts comparing revenues across cuisines and scatter plots correlating ratings with revenue. Additionally, bar charts would further analyze the relationship between menu pricing and revenue, ensuring a comprehensive graphical representation of the data that supports strategic business decision-making.

To summarize my findings, I created three dashboards and a Tableau story presenting key insights.

#### Cuisine and Revenue Analysis Dashboard
![Image](https://github.com/user-attachments/assets/fdeb653f-5f9a-42e4-80b7-a91ceb395640)

#### Ratings and Revenue Dashboard
![Image](https://github.com/user-attachments/assets/c335ef6d-c749-4018-af51-85bebc46e433)

#### Cost Point Effectiveness on Sales Dashboard
![Image](https://github.com/user-attachments/assets/3233ccaf-d1ad-414b-bf22-07f0ff7c26cd)

### Results
Conclusion: 
  1. Revenue and Cuisine Type – The visualization indicates that North Indian and Chinese cuisines dominate in revenue. This supports the hypothesis that certain cuisines generate higher revenue than others. The correlation suggests that popular and widely available cuisines drive more sales. 
  2. Impact of Ratings on Revenue – The scatter plot shows that higher-rated restaurants do not always achieve higher revenue. For example, Domino’s Pizza has a lower rating but generates the highest revenue. This disproves the hypothesis and suggests that brand recognition, affordability, and accessibility may be stronger factors than ratings in driving revenue. 
  3. Price Point Effectiveness – The analysis indicates that there is no definitive positive correlation between higher menu prices and increased revenue. Some restaurants with lower operational costs achieved high revenue, while others with higher costs saw lower returns. This suggests that pricing strategies alone are not the sole determinants of success; instead, factors such as brand strength, cuisine popularity, and customer preferences also play significant roles in influencing a restaurant's financial performance.


Recommendations:
  1. Expand Popular Cuisine Offerings – North Indian and Chinese cuisines drive the most revenue. Restaurants should adapt their menus to include high-demand dishes.
  2. Prioritize Brand and Accessibility Over Ratings – High ratings don’t guarantee revenue. Investing in marketing, loyalty programs, and accessibility can boost sales regardless of ratings.
  3. Evaluate Cost Efficiency – Restaurants with high costs but lower revenue (e.g., KOHINOOR HOTEL) may need to reassess expenses, streamline operations, and optimize supply chain management to improve profitability.
  4. Improve Convenience and Visibility – Restaurants with lower ratings but high revenue benefit from strong branding and easy accessibility. Expanding delivery and online ordering can drive sales.
  5. Utilize Data for Growth – Regular analysis of cuisine trends, pricing impact, and customer behavior can help refine strategies for sustained success.


### Project Link
https://public.tableau.com/views/Sprint7FinalProject_17417515822480/CuisineandRevenueAnalysis?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link  
