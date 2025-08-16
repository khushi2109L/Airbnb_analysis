🔍**Overview**

This project focuses on analyzing Airbnb listings in New York City using Power BI. The goal is to explore how listings vary by neighborhood, room type, price, availability, and host activity.
I used Power BI to clean, model, and visualize the data through an interactive dashboard that can help hosts, travelers, or businesses make informed decisions.

📁 **About the Dataset**
**Source**: [Inside Airbnb – New York City Listings](http://data.insideairbnb.com/united-states/ny/new-york-city/latest/listings.csv)
Data Includes:
-Listing name and ID
-Host information
-Neighborhood and borough
-Room type (Entire home, Private room, etc.)
-Price per night
-Minimum nights
-Number of reviews
-Availability

🛠 Tools Used

**Power BI** – for data cleaning, modeling, and dashboard creation
**DAX** – for custom calculations and KPIs
**Power Query Editor** – for data transformation

**📌 Key Questions Answered**
-What’s the average price by neighborhood and room type?
-Which room type is demanded more ?
-Which listings get the most reviews?
-What’s the availability of listings according to the Price Range?

**🧼 Data Cleaning Highlights**

-Removed duplicate and missing entries
-Filtered out extreme outliers (e.g. listings with prices over $1,000/night)
-Converted data types (dates, numbers)
-Created custom columns like:
  -Price Category (Low, Medium, High)
  -Yearly Revenue Estimate = price × availability

**💡 Key Insights**

-Private rooms are the most common, but entire homes generate more revenue.
-Brooklyn offers a balance of affordability and availability.
-Listings with higher reviews tend to be more competitively priced.

**🚀 Future Enhancements**

-Add time-based trends if historical data is available
-Include customer review text analysis (sentiment analysis)
-Build a web version of the dashboard using Power BI Service
