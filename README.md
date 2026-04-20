# 🧸 Toy Store Analytics Dashboard (Power BI)

## 🚀 What this project is about

This project is a full business analysis of an e-commerce toy store using Power BI.

Instead of just showing numbers, the goal was to answer real business questions:

- Where are we losing customers?
- Which marketing channels actually drive revenue?
- Which products are profitable vs risky?
- Do repeat users behave differently from new users?

---

## 🧠 What I built

A 5-page interactive dashboard covering:

### 1. Executive Overview
High-level business snapshot:
- Revenue, Profit, Orders, AOV
- Trends over time
- Overall conversion performance

---

### 2. Marketing Performance
Breakdown of acquisition channels:
- Traffic vs conversions by channel
- Revenue contribution
- Device-level performance

👉 **Key takeaway:**  
Google drives volume, but Bing converts better.

---

### 3. Funnel Analysis
User journey from entry to purchase:

Sessions → Product → Cart → Order

- Step-wise conversion rates
- Drop-off analysis
- Channel-level funnel comparison

👉 **Key takeaway:**  
The biggest drop happens at **Product → Cart (~64%)**  
This is the main optimization opportunity.

---

### 4. Product Performance
Deep dive into product-level metrics:
- Revenue & Profit by product
- Margin analysis
- Refund rates

👉 **Key takeaway:**  
Some high-margin products underperform in sales, while others show refund issues.

---

### 5. User Behavior
Understanding customer patterns:
- New vs Repeat users
- Conversion differences
- Device behavior
- User growth trends

👉 **Key takeaway:**  
Repeat users convert significantly higher.  
Mobile users underperform compared to desktop.

---

## 🏗️ How the data is structured

I used a **star schema** approach:

**Fact tables:**
- orders  
- order_items  
- website_sessions  
- website_pageviews  
- order_item_refunds  

**Dimension tables:**
- products  
- Date table  

This ensures clean relationships and scalable analysis.

---

## 📐 Key metrics I created

- Conversion Rate  
- Funnel Conversion (Product / Cart / Order)  
- Drop-off Rates  
- Margin %  
- Refund Rate  
- Repeat User Share  

---

## 🛠️ Tools used

- Power BI  
- DAX  
- Power Query  
- Data Modeling  

---

## 📊 What I learned

- How to think in terms of **business questions, not just visuals**
- The difference between **session-level vs user-level metrics**
- How to build a **funnel analysis from raw event data**
- Designing dashboards that highlight **decision points**

---

## 📸 Dashboard preview

<img width="660" height="374" alt="OVERVIEW" src="https://github.com/user-attachments/assets/2a74d6b6-af5c-4997-a7f1-96dbd76c6b5f" />
<br><br>
<img width="660" height="375" alt="Marketing Performance" src="https://github.com/user-attachments/assets/744e448d-c0ab-4b76-bf7c-a4e9d7dd65f2" />
<br><br>
<img width="659" height="374" alt="Funnel Analysis" src="https://github.com/user-attachments/assets/6c87c8c9-841c-4852-bfe4-3041e9b33cbe" />
<br><br>
<img width="660" height="375" alt="Product Performance" src="https://github.com/user-attachments/assets/2fed9435-e662-4fce-ae03-d3a465cfe9ea" />
<br><br>
<img width="658" height="375" alt="User Behaviour" src="https://github.com/user-attachments/assets/8b93a9cf-5c14-42be-b62e-5654ad010d5a" />


---

## 🎯 Why this project matters

This isn’t just a dashboard — it’s a **decision-making tool**.

It highlights:
- Where revenue is coming from  
- Where users drop off  
- What needs optimization  

---

## 👋 Let's connect

If you have feedback, ideas, or want to collaborate — feel free to reach out!
