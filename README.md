# 🚗 Car Sales Data Analysis using Excel

## 📌 Project Overview
This project analyzes a car sales dataset using **Microsoft Excel** to uncover insights about sales performance, customer behavior, dealer efficiency, and product preferences.  
The analysis focuses on **data cleaning, transformation, pivot table analysis, and visualization**, following a real-world **Data Analyst workflow**.

---

## 📂 Dataset Description
The dataset contains historical car sales records with the following key attributes:

- **Car_id** – Unique identifier for each sale  
- **Date** – Date of car purchase  
- **Customer Name** – Name of the customer  
- **Gender** – Customer gender  
- **Annual Income** – Customer annual income  
- **Dealer_Name** – Name of the dealer  
- **Company** – Car manufacturer (brand)  
- **Model** – Car model  
- **Engine** – Engine type  
- **Transmission** – Manual / Automatic  
- **Color** – Car color  
- **Price ($)** – Selling price of the car  
- **Dealer_No** – Dealer identification number  
- **Body Style** – SUV, Sedan, Hatchback, etc.  
- **Phone** – Customer contact number  
- **Dealer_Region** – Dealer location/region  

---

## 🧹 Data Cleaning & Preparation
The following steps were performed in Excel:

- Removed duplicate records using **Car_id**
- Standardized text columns using `TRIM()` and `PROPER()`
- Converted columns to correct data types (Date, Number, Currency)
- Handled missing values without making assumptions
- Ensured phone numbers were stored as **text**
- Created additional helper columns for analysis

---

## ➕ Feature Engineering
New analytical columns were created:

- **Year** – Extracted from Date
- **Month** – Extracted from Date
- **Income Group** – Low / Medium / High
- **Price Segment** – Budget / Mid-range / Premium

---

## 📊 Data Analysis (Pivot Tables)
Key pivot table analyses include:

1. **Total Sales by Company**
   - Identifies top-performing car brands

2. **Sales Performance by Dealer Region**
   - Compares revenue and sales volume across regions

3. **Transmission vs Body Style**
   - Analyzes customer preference for car types

4. **Average Price by Gender**
   - Examines purchasing behavior differences

---


## 🔍 Key Insights
- Automatic transmission vehicles dominate overall sales
- SUVs contribute the highest share of revenue
- Certain dealer regions significantly outperform others
- Premium cars show higher demand among high-income customers

---

## 🛠 Tools Used
- **Microsoft Excel**
  - Pivot Tables
  - Data Cleaning Functions
  

---

## 📁 Project Structure
