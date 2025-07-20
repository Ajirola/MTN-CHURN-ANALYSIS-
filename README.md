# MTN-CHURN-ANALYSIS-

## 📑 Table of Contents
- [Description](#description)
  
- [Overview](#overview)
  
- [Problem Statement](#problem-statement)
  
- [Objective](#objective)
 
- [Key areas analyzed]()

- [Data Source]()

- [Data Description]()
  
- [Tools Used](#tools-used)

- [Data cleaning]()
  
- [Analysis and visualization]()
  
- [Dashboard](#dashboard)
 
- [Key metrics]()
  
- [Insights Gained](#insights-gained)
  
- [Recommendation](#recommendation)
  
- [Contact](#contact)


## 📄 Description
This project presents an interactive dashboard for MTN's customer churn analysis. It explores trends and patterns in customer behavior, retention, and churn across different categories including age, tenure, device usage, and customer feedback.

## 📌 Project Overview
Understanding churn patterns is vital for improving customer retention and maximizing revenue. This dashboard visualizes churn metrics from 974 MTN customers to identify areas for targeted interventions.

## ❓ Problem Statement
MTN is experiencing a 29% customer churn rate, which may affect profitability, customer lifetime value, and brand loyalty. Identifying the key churn drivers is essential for building retention strategies.


## 🎯 Objective
1️⃣ To analyze churn trends across demographics, tenure, devices, and customer reviews  

2️⃣ To derive actionable, data-driven insights  

3️⃣ To recommend effective strategies to reduce churn

4️⃣ Support business decisions through easy-to-understand visuals

## 📊 Key Areas Analysed
📍 Gender-based churn rate  

📍 Age group-wise churn  

📍 Tenure category churn behavior  

📍 Device-specific churn analysis  

📍 Churn trend over months  

📍 Customer review patterns
  

## 📚 Data Source

The dataset was obtained from kaggle website

Here's the link to the dataset: https://www.kaggle.com/datasets/nextmillionaire/pizza-sales-dataset

## 🧾 Dataset Description
This dataset contains 974 rows of customer entries and the following columns

| **Column Name**              | **Description**                                                                                                                                  |
|-----------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| `Customer ID`               | A unique identifier assigned to each customer. May appear more than once if the customer owns multiple devices.                                 |
| `Full Name`                 | Full name of the customer. Names are representative of various Nigerian ethnicities and regions.                                                  |
| `Date of Purchase`          | Month and year the device or plan was purchased. All entries are from the year **2025**.                                                         |
| `Age`                       | Age of the customer (ranges from **16 to 80**). Influences purchasing behavior.                                                                  |
| `State`                     | Nigerian state where the customer resides, including the **FCT**.                                                                                |
| `MTN Device`                | Device purchased by the customer. Includes: **Mobile SIM Card**, **Broadband MiFi**, **4G Router**, **5G Broadband Router**.                     |
| `Gender`                    | Gender of the customer (**Male** or **Female**).                                                                                                 |
| `Satisfaction Rate`         | A score from **0 to 5** reflecting the customer’s satisfaction level.                                                                            |
| `Customer Review`           | Categorical review of experience: **Poor**, **Fair**, **Good**, **Very Good**, **Excellent**.                                                    |
| `Customer Tenure in months` | How long the customer has been subscribed (in months).                                                                                           |
| `Subscription Plan`         | The name of the MTN data plan purchased (e.g., **60GB Monthly Broadband Plan**, **7GB Monthly Plan**, etc.).                                     |
| `Unit Price`                | Cost of the data plan in **Nigerian Naira (₦)**.                                                                                                 |
| `Data Usage`                | Estimated data usage in **gigabytes (GB)**. Not necessarily equal to plan size—it reflects actual usage behavior.                               |
| `Number of Times Purchased` | How many times the plan was purchased within the month (simulates usage/consumption frequency).                                                  |
| `Total Revenue`             | Total amount spent by the customer (**Unit Price × Number of Times Purchased**).                                                                 |
| `Customer Churn Status`     | Indicates whether the customer has churned (**Yes**) or is still active (**No**).                                                                |
| `Reasons for Churn`         | If churned, shows the reason (e.g., **Poor Network**, **Relocation**, **High Call Tariffs**, etc.). Empty for active customers.                  |

## 🛠️ Tools Used
- **Power BI** – for interactive dashboards and visualizations  
- **Microsoft Excel** – for initial data cleaning and formatting

## 🧹 Data Cleaning
📍 Removed duplicates and null values

📍 Standardized pizza names, sizes, and categories  

📍 Converted date columns to readable formats

### Analysis & Visualization
📍 Grouped and summarized data using DAX formulas in Power BI  

📍 Built visualizations like bar charts, donut charts, and line graphs  

📍 Applied slicers for interactive filtering by category and size

## 📈 Dashboard  
![Screenshot](Screenshot_20250718-071456.jpg)



## 🔢 Key Metrics

| Metric               | Value       |
|----------------------|-------------|
| **Total Sales**      | 818,000     |
| **Total Orders**     | 21,000       |
| **Total Pizzas Sold**| 50,000       |


## 📊 Insights gained 
✅ **Best and Worst Performing Pizzas**

✅ **Top Performers**:  
**Thai Chicken Pizza** leads with **43,000** units sold, followed by **Barbecue Chicken** and **California Chicken**

❌ **Lowest Performers**:  

**Brie Carre Pizza** is the least popular with only **11,600** units sold, others include **Spinach-based varieties**

Indicating potential areas to **improve** or **phased out underperforming varieties**.

## ✅ **Pizza size sales**
**Large-sized** dominate sales **45.89%**, while **X-Large** contribute atleast **1.72%.**

This trends suggest that customers prefer **larger pizzas** over **regular** or **medium**, but the **extra large** might be too big or not cost effective for most customers.


## ✅ **Pizza Category sales**
**Classic** dominate sales **26.91%**, followed by **Supreme**  **25.46%**. The least is **Veggie** **23.68%**.

This indicates that customer preferences are **Classic & Supreme**


## ✅ **Sales trends by days**
The highest sales occurs on **friday**, while **Sunday** had the lowest sales 

This indicates a strong **weekend effect**, with Fridays being popular for ordering pizza, potentially due end of week relaxation or  social gatherings.


## ✅ **Monthly trends by sales**
Sales **peaks** in **July** **72.6k**, while in **October** sales **dips** to the lowest **62.4k**.

These trends could correlate with seasonal events, holidays or marketing campaigns influencing customer behavior 

## ✍️ Recommendations
1️⃣ **Promote top-performing pizzas** like **Thai Chicken and Barbecue Chicken**.

2️⃣ **Reevaluate low-performers** like **Brie Carre Pizza and spinach-based varieties**.

3️⃣ **Focus production on L and M sizes**, which make up over 75% of total sales.

4️⃣ **Increase staffing and stock** for peak days **(Fridays)** and peak months **(June)**.

5️⃣ **Introduce offers or discounts** on low-performing days (Sundays) and off-peak months (like September)

## 👩🏽‍💻 Contact:
Created by: **Ajirola Amudat**  
_Data Analyst | Power BI Enthusiast_

📧 For collaboration or inquiries, connect with me on [LinkedIn](https://www.linkedin.com/in/ajirola-amudat-a-3083882b2?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)

![Screenshot](Screenshot_20250311-144911.jpg)



