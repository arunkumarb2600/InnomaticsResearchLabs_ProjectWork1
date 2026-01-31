📌 Project Overview

This project analyzes a food delivery dataset by combining data from multiple sources (CSV, JSON, and SQL). The goal is to understand customer behavior, restaurant performance, and revenue trends.
This project was created as part of a Data Analytics Hackathon.

📂 Dataset Description
The project uses three datasets:

1️⃣ orders.csv

Transactional data containing:
Order ID
User ID
Restaurant ID
Order Date
Order Amount

2️⃣ users.json

User master data containing:
User ID
Name
City
Membership Type (Gold/Regular)

3️⃣ restaurants.sql

Restaurant master data containing:
Restaurant ID
Restaurant Name
Cuisine
City

🔄 Data Processing Steps

Loaded CSV, JSON, and SQL data
Cleaned and validated data
Performed left joins:
orders ↔ users
orders ↔ restaurants

Created final dataset:
final_food_delivery_dataset.csv
