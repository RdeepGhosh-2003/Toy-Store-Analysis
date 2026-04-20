# 🧸 Toy Store Analytics Dashboard (Power BI)

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Analytics](https://img.shields.io/badge/Data%20Analytics-FF6F00?style=for-the-badge&logo=google-analytics&logoColor=white)

---

## 🚀 What this project is about

This project is a full **business analysis of an e-commerce toy store** using Power BI.

Instead of just showing numbers, the focus is on answering real business questions:

- 📉 Where are we losing customers?
- 📢 Which marketing channels actually drive revenue?
- 📦 Which products are profitable vs risky?
- 👥 Do repeat users behave differently from new users?

---

## 📊 Key Business Metrics

| Metric | Value |
|------|------|
| 💰 Revenue | $1.94M |
| 💵 Profit | $1.22M |
| 🛒 Orders | 32K |
| 🌐 Sessions | 473K |
| 💳 AOV | $60 |
| 📈 Conversion Rate | 6.83% |

---

## 🧠 What I built

A **5-page interactive dashboard** covering:

---

### 🟫 1. Executive Overview
High-level business snapshot:
- Revenue, Profit, Orders, AOV
- Trends over time
- Overall conversion performance

---

### 🟨 2. Marketing Performance
Breakdown of acquisition channels:
- Traffic vs conversions by channel
- Revenue contribution
- Device-level performance

👉 **Key takeaway:**  
Google drives the most traffic and revenue, while Bing converts more efficiently.

---

### 🟥 3. Funnel Analysis
User journey from entry to purchase:

**Sessions → Product → Cart → Order**

- Step-wise conversion rates  
- Drop-off analysis  
- Channel-level funnel comparison  

👉 **Key takeaway:**  
The biggest drop happens at **Product → Cart (~64%)**  
This is the biggest revenue opportunity.

---

### 🟪 4. Product Performance
Deep dive into product-level metrics:
- Revenue & Profit by product  
- Margin analysis  
- Refund rates  

👉 **Key takeaway:**  
Some products have high margins but low sales, while others show higher refund rates (potential quality issues).

---

### 🟦 5. User Behavior
Understanding customer patterns:
- New vs Repeat users  
- Conversion differences  
- Device behavior  
- User growth trends  

👉 **Key takeaway:**  
Repeat users convert significantly higher.  
Mobile users underperform compared to desktop.

---

## 🏗️ Data Model

This project uses a **Star Schema** for efficient and scalable analysis:

       DateTable
           │
           │
┌───────────▼───────────┐
│ Orders │
└───────────┬───────────┘
│
┌───────▼────────┐
│ Order_Items │
└───────┬────────┘
│
┌──────▼──────┐
│ Products │
└─────────────┘

Other Supporting Tables:

Website_Sessions
Website_Pageviews
Order_Item_Refunds


### 💡 Key Modeling Decisions
- Created a dedicated **Date Table** for time intelligence  
- Avoided ambiguous relationships  
- Built a centralized **Measures table**  
- Differentiated **user-level vs session-level metrics**

---

## 📐 Key metrics I created

- 📈 Conversion Rate  
- 🔻 Funnel Conversion (Product / Cart / Order)  
- 📉 Drop-off Rates  
- 💰 Margin %  
- 🔁 Refund Rate  
- 👥 Repeat User Share  

---

## 🛠️ Tools used

- 📊 Power BI  
- 🧮 DAX  
- 🔄 Power Query  
- 🧱 Data Modeling  

---

## 📊 What I learned

- Thinking in terms of **business problems, not just visuals**  
- Handling **session vs user level calculations**  
- Building **funnel analysis from raw behavioral data**  
- Designing dashboards focused on **decision-making**  

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

This is not just a dashboard — it is a **decision-making tool**.

It helps identify:
- 📊 Where revenue is coming from  
- 📉 Where users drop off  
- ⚠️ What needs optimization  
- 🚀 Where business can grow  

---

## 👋 Let's connect

If you have feedback, ideas, or want to collaborate — feel free to reach out!
