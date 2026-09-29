# 📦 Olist E-Commerce Performance & Customer Analytics

![Tableau](https://img.shields.io/badge/Tableau-Public-E97627?style=for-the-badge&logo=Tableau&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)

An end-to-end data analytics project exploring **~100,000 Brazilian e-commerce transactions** (2016–2018) from Olist. This project aims to analyze sales performance, logistics bottlenecks, customer review dynamics, and payment preferences to provide actionable business recommendations.

---

## 📊 Live Interactive Dashboard

🔗 **[View Executive Dashboard on Tableau Public](https://public.tableau.com/views/OlistE-CommerceExecutiveDashboard_17906794085650/OlistE-CommerceExecutiveDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

---

## 🎯 Executive Summary

The analysis reveals significant opportunities for revenue growth and operational enhancement at Olist:

1. **Severe Retention Challenge:** Over $97\%$ of customers are **one-time buyers**, pointing to a missing retention/loyalty framework.
2. **Logistics Directly Drives Satisfaction:** On-time deliveries achieve a high customer rating average of **$4.15 / 5.00$**, whereas late deliveries drop drastically to **$2.55 / 5.00$**.
3. **Revenue Drivers:** Product sales are heavily driven by top categories including `health_beauty`, `watches_gifts`, and `bed_bath_table`.
4. **Payment Preference:** Credit Card dominates customer preference (~$75\%$), followed by Boleto (~$19\%$).

---

## 🔍 Key Findings & Insights

### 1. Sales Trend & Growth
* Steady revenue growth was observed throughout 2017, reaching peak order volumes during late 2017 and early 2018 (notably around Black Friday 2017).
* The average order value (AOV) remains stable, but revenue relies heavily on top-tier product categories.

### 2. Logistics & Operational Impact
* A clear inverse relationship exists between shipping delays and customer satisfaction score ($1 \text{ to } 5$ rating scale).
* Delayed orders generate severe churn risk, as negative reviews ($1\text{--}2$ stars) are predominantly tagged with delivery delay issues.

### 3. Payment Dynamics
* **Credit Card** represents the majority of transaction volume, with users favoring installment options ($1\text{--}10$ months).
* **Boleto** (cash-like voucher) represents a significant portion of orders but suffers from higher cancellation rates due to payment friction.

---

## 💡 Strategic Recommendations

1. **Implement Automated Retention & CRM Campaigns:**
   * Introduce targeted post-purchase email flows, personalized recommendations, and loyalty incentives to convert one-time buyers into repeat customers.
2. **Establish Regional Fulfillment & Delivery SLA Optimizations:**
   * Partner with regional logistics hubs near high-density customer clusters (e.g., Southeast Brazil) to lower transit times and mitigate delay-induced $1$-star reviews.
3. **Product Bundling & AOV Expansion:**
   * Create cross-category bundle offers (e.g., combining `health_beauty` with complementary items) to increase overall basket size and margin per order.
4. **Payment Friction Reduction:**
   * Send automated SMS/WhatsApp reminders for unpaid Boleto orders to reduce dropped checkout conversions.

---

## 🛠️ Data Pipeline & Methodology

1. **Data Cleaning & Integration (Google Colab / Python):**
   * Processed multiple relational datasets (`orders`, `order_items`, `customers`, `payments`, `reviews`, `products`).
   * Handled missing values, standardized timestamps, and created custom fields (e.g., `Delivery Status`).
2. **Exploratory Data Analysis (EDA):**
   * Performed aggregation and cohort behavior analysis using `Pandas` and `NumPy`.
3. **Dashboard & Visualization (Tableau Public):**
   * Built interactive sheets: *Sales Trend*, *Top Categories*, *Logistics Impact*, and *Payment Methods*.
   * Designed a cohesive executive layout for decision-makers.

---

## 📁 Repository Structure

```text
├── data/
│   └── olist_master_clean.csv      # Cleaned & merged dataset
├── notebooks/
│   └── olist_analysis.ipynb        # Colab Python analysis code
├── assets/
│   └── dashboard_preview.png       # Executive dashboard screenshot
└── README.md                       # Project documentation
```

---

## 👤 Author

* **LinkedIn:** [Your LinkedIn Profile]
* **Tableau Public:** [Your Tableau Public Profile]
* **Email:** [Your Email Address]