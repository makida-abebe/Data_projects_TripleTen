# TripleTen Business Analytics Project - Conversion and Retention Rates

### The Prompt
The executive team at an e-commerce company is interested in understanding how well the website is converting product page views into purchases. They have asked you to create a conversion funnel to better understand how users interact with the website. The company wants you to build acquisition cohorts based on the month of a user’s first purchase, and they want you to track cohort metrics month by month.

### The Data
The provided data was a raw transaction log spreadsheet including `'user_id'`, `'event_type'`: page view, shopping cart, or purchase, `'category_code'`, `'brand'`, `'price'`, and `'event_date'`.	Raw event activity spans September 2020 thru Februrary 2021. The brand and price of the product information was not pertinent to the conversion rate
and retention rate analysis.

### The Process
To construct the conversion funnel, a unique UserIDs count was applied to the three types of events documented in the raw data: page view, open shopping cart, and complete purchase.

![Image](https://github.com/user-attachments/assets/8d189518-dc0b-4df4-a405-fa957552f4f0)

User cohorts were established based on the month when individual users first made a purchase. The VLookup function was used to determine the first purchase date of each customer associated with product page events in the dataset. Columns labeled 'first_purchase_month' and 'cohort_age' were then added to the purchase activity table to create the formation of monthly cohorts.

![Image](https://github.com/user-attachments/assets/a5acacae-bdd0-4c8d-998d-0a845c24c012)

Retention rates were calculated monthly, by checking if customers made a purchase in a given month and determining the number of months since their initial purchase. 

![Image](https://github.com/user-attachments/assets/fa2d0d33-6370-41e1-af0d-ddf2c97ab932)

### Results
The conversion funnel analysis demonstrates the website's effectiveness in converting viewers into buyers, offering a detailed view-to-purchase conversion analysis. This analysis identifies significant drop-off points and highlights stages with the highest conversion potential. Meanwhile, the retention rates provide insights into the long-term engagement of users by tracking the percentage of users who continue to make purchases over time. The data shows a strong initial retention that decreases over subsequent months, emphasizing the need for enhanced engagement strategies to maintain customer interest and activity. 

### Project Link
https://docs.google.com/spreadsheets/d/196e6W6Vl0oJkm26sAMGiVCPElJL_VRHQT5-sAut5YuE/edit?usp=sharing  
