# Customer-Shopping-Behavior-Analysis

##  Project Overview
This project analyses **customer shopping behaviour** using data from **3,900 purchases** to uncover spending patterns, customer segments, product preferences, and subscription trends.  
Insights are delivered through **Python, SQL, and Power BI** to support data-driven business decisions.

**Tools:** Python (Pandas) | MYSQL | Power BI  
**Records:** 3,900 purchases | 18 features

---

## Business Objectives
- Understand customer spending and purchase behaviour  
- Identify high-value and loyal customer segments  
- Analyse product performance and discount dependency  
- Support subscription growth and targeted marketing strategies  

---

##  Dataset Summary
- **Customer attributes:** Age, Gender, Location, Subscription Status  
- **Purchase details:** Item, Category, Amount, Season, Size, Color  
- **Behavioural data:** Discounts, Previous Purchases, Purchase Frequency, Ratings, Shipping Type  
- **Data quality:** 37 missing values in *review_rating* (handled during cleaning)

---

##  Exploratory Data Analysis (EDA) using Python
- Cleaned and explored data using Pandas  
- Imputed missing *review_rating* values using **median by product category**  
- Standardised column names   
- Engineered features:
  - `age_group`
  - `purchase_frequency_days`
- Removed redundant column (*promo_code_used*)
- Loaded cleaned data into **MYSQL** for SQL analysis

---

##  Key Analysis (SQL)
- Revenue comparison by **gender**
- Identification of **high-spending discount users**
- **Top 5 products** by average rating
- Average spend by **shipping type** (Express vs Standard)
- **Subscribers vs non-subscribers** revenue comparison
- Products most dependent on **discounts**
- Customer segmentation: **New, Returning, Loyal**
- Revenue contribution by **age group**
- Subscription likelihood among **repeat buyers**

---

##  Key Insights
- **Male customers generate higher total revenue** than females  
- **Subscribers and non-subscribers spend similar amounts per purchase**, but non-subscribers dominate volume  
- Majority of customers fall into the **Loyal segment**  
- **Express shipping users spend slightly more on average**  
- Certain products (e.g. hats, sneakers, coats) are **highly discount-dependent**  
- **Young adults and middle-aged customers** contribute the most revenue  

---

##  Power BI Dashboard
An interactive dashboard was built to visualise:
- Customer count & average spend KPIs  
- Revenue and sales by category  
- Subscription breakdown  
- Revenue by age group  
- Filters for gender, category, shipping type, and subscription status  

---

##  Business Recommendations
- **Boost subscriptions** with exclusive benefits  
- **Reward repeat buyers** to strengthen loyalty  
- **Review discount strategy** to protect margins  
- **Promote top-rated and best-selling products**  
- **Target marketing** toward high-revenue age groups and express-shipping users  

---

##  Skills Demonstrated
Data Cleaning • Feature Engineering • SQL Analytics • Power BI Dashboards  
Customer Segmentation • Business Insight Generation • Data Storytelling


