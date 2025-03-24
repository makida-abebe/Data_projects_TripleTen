# TripleTen Exploratory Data Analysis Project - NYC AirBNB Data

### The Prompt
Help a client analyze the Manhattan vacation rental market. They want guidance on which property types to invest in and you task is to analyze Airbnb data for insights. Make recommendations by answering the following questions: Which neighborhoods and property sizes are most attractive for vacation rentals?
and How much money did these listings generate?

### The Data
The AirBNB dataset was provided by TripleTen and includes 
- A Raw Listings Data spreadsheet containing  
    - Listing identifiers like `'listing_url'`, `'id'`, `'name'`, `'description'`, `'picture_url'` and more
    - Host information like `'host_id'`, `'host_name'`, `'host_location'`, `'host_listing_count'` and more
    - Neighborhood information like `'neighborhood'`, `'latitude'`, and `'longitude'` and more
    - Property information like `'accommodates'`, `'bedrooms'`, `'price'`, `'minimum_nights'`, and `'maximum_nights'` and more
    - Review information like `'number_of_reviews'`, `'first_review'`, and `'reviews_per_month'`and more
- A Raw Calendar data spreadsheet containing
    - `'listing_id'`
    - the `'date'` in the listing's calendar
    - whether the date is `'available'` for booking
    -  the `'price'` listed for the day and the `'adjusted_price'`
    -  the `'minimum_nights'` and `'maximum_nights'` for a booking made on this day

### The Process
I began with essential data cleaning before using pivot tables to analyze and identify which neighborhoods and property sizes attract the most vacation renters, using recent reviews as a metric. This part of the analysis was visualized by displaying the most reviewed neighborhoods and the distribution of property sizes within those areas.

![Image](https://github.com/user-attachments/assets/358d82d9-acc8-4e23-ac85-124fac33874d)

![Image](https://github.com/user-attachments/assets/85aabe33-1de5-4ec8-b530-8e4476aeb49c)

To calculate how much money the most attractive listings generated, I focused on the top 10 neighborhoods and the most popular-sized properties in those neighborhoods by creating a top_listing identifier column. Annual revenue was estimated by multiplying the last month's revenue by 12.

![Image](https://github.com/user-attachments/assets/18518af9-438c-4bc6-975f-e074124baa0f)


### Results
- This analysis aims to identify the most attractive and profitable Airbnb listings in Manhattan, focusing on maximizing annual revenue and understanding customer preferences. The approach involved cleaning and preparing the data to ensure accuracy, creating metrics such as revenue, annual revenue, and occupancy rates, and using pivot tables and visualizations to uncover key insights. Specific emphasis was placed on 1-bedroom properties and top-performing neighborhoods to refine recommendations. The findings revealed that neighborhoods such as Lower East Side, Midtown, and Upper East Side host some of the most lucrative listings, with specific properties achieving the highest annual revenue. These insights provide valuable guidance for Airbnb hosts to optimize property offerings and pricing strategies for increased profitability. 

### Project Link
https://docs.google.com/spreadsheets/d/1vlrRepf-EwGSrMyQh5E6M5qdB2SWVOGo7x0IzpJRY4M/edit?usp=sharing 
