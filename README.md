# <h1 align="center" > 🛒 TARGET - Retail_Analysis 🛒  </h1>


<kbd><img src="https://github.com/user-attachments/assets/4b67bb90-3bf3-4823-818b-465f1f02e03a" alt="R"></kbd>


***

#### 📑This Repo serves as a Business case study. Providing Solution , Insights and Recommendation for the growth in their Revenue through sql queries.

 🔎This SQL solutions done in `Google BigQuery`

 🔗If you have any questions, reach out to me on [LinkedIn](www.linkedin.com/in/ritesh-gupta-53a725113).

🚀 Welcome to the Target Data Analysis project! 🎉

As a data scientist at Target, you've been given the exciting opportunity to analyze 100k orders from 2016 to 2018 made at Target in Brazil. 🌎🇧🇷

📚 The dataset is available in 8 csv files:

1. customers.csv 🧑‍🤝‍🧑
2. geolocation.csv 🗺️
3. order_items.csv 🛍️
4. payments.csv 💳
5. reviews.csv 📝
6. orders.csv 📦
7. products.csv 📝
8. sellers.csv 👩‍💼

🔍 So, what does 'good' look like? We'll import the dataset and perform exploratory analysis steps to check the structure, characteristics, data types, and time period for which the data is given. We'll also look at the cities and states of customers who ordered during the given period. 🕵️‍♀️

🔍 In-depth Exploration:

1. Is there a growing trend on e-commerce in Brazil? 📈 How can we describe the complete scenario? 🤔 Can we see some seasonality with peaks at specific months? ❄️☀️
2. What time do Brazilian customers tend to buy? 🕒 Do they prefer to shop at dawn, morning, afternoon, or night? 🌅🌇🌄🌃
3. Evolution of E-commerce orders in the Brazil region: 
   - Get month on month orders by states 📊
   - Distribution of customers across the states in Brazil 🗺️👥
4. Impact on Economy: Analyze the money movement by e-commerce by looking at order prices, freight and others.
   - Get % increase in cost of orders from 2017 to 2018 (include months between Jan to Aug only) - You can use “payment_value” column in payments table 💰
   - Mean & Sum of price and freight value by customer state 💵🚛
5. Analysis on sales, freight and delivery time 📊🚚
   - Calculate days between purchasing, delivering and estimated delivery 📅
   - Find time_to_delivery & diff_estimated_delivery ⏳
   - Group data by state, take mean of freight_value, time_to_delivery, diff_estimated_delivery 📊
   - Sort the data to get the following:
     - Top 5 states with highest/lowest average freight value - sort in desc/asc limit 5 📉📈
     - Top 5 states with highest/lowest average time to delivery 🚛⏰
     - Top 5 states where delivery is really fast/ not so fast compared to estimated date 🚚⚡
6. Payment type analysis: 💳
   - Month over Month count of orders for different payment types 📊
   - Count of orders based on the no. of payment installments 🔢
***
 <p align="right">
  <img src="https://github.com/user-attachments/assets/3d7e7cff-d4b5-4ed6-9042-a758ff45d915" alt="Image">
  
## Support
Give a ⭐️ if you like this project!
