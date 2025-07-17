# 📦 Quick Commerce India – Data Analysis Project

![Power BI Dashboard Banner](https://static.vecteezy.com/system/resources/previews/002/916/508/original/big-isolated-motorcycle-colorful-icons-vector.jpg) 

## 📊 Project Overview

This data analysis project explores the performance of major quick commerce platforms in India using a synthetic dataset of **100,000 orders**. The analysis provides deep insights into platform-wise performance, customer satisfaction, refund patterns, category-wise revenue, and more.

The project is designed using **Power BI** and leverages **DAX (Data Analysis Expressions)** for advanced data modeling, calculated columns, and dynamic measures.

---

## 🔧 Tools & Technologies Used

* **Power BI Desktop**
* **DAX (Data Analysis Expressions)**
* **Microsoft Excel (for pre-cleaning)**
* **Data Visualization & Dashboard Design**

---

## 🧠 Key Skills Demonstrated

* DAX measures and calculated columns
* Power BI slicers and filters for interactivity
* Business insights generation
* Visual storytelling for stakeholders
* Sentiment analysis on customer feedback

---

## 🧩 DAX Functions Used

Some of the key DAX implementations in this project include:

* **SWITCH()** for customer sentiment classification
* **IF(), CALCULATE(), COUNTROWS()** for refund analysis
* **AVERAGE(), SUM(), DISTINCTCOUNT()** for KPI creation
* **FILTER()** to manage dynamic filtering in cards and visuals
* **DATE formatting and conversion** for time-based analysis

Example:

```dax
Sentiment = 
    SWITCH(TRUE(),
        SEARCH("rude", LOWER('Customer Feedback'[Feedback]), 1, 0) > 0, "Negative",
        SEARCH("great", LOWER('Customer Feedback'[Feedback]), 1, 0) > 0, "Positive",
        "Neutral"
    )
```

---

## 📈 Key Metrics & KPIs

| Metric                 | Value         |
| ---------------------- | ------------- |
| Total Orders           | 100,000       |
| Total Revenue          | ₹59 Million   |
| Avg Delivery Time      | 29.54 minutes |
| Average Service Rating | 3.24 / 5      |
| Refund Rate            | 45.82%        |

---

## 🔍 Key Insights for Industry

1. **Platform Performance**:

   * All three platforms—**Swiggy Instamart**, **Blinkit**, and **JioMart**—generate comparable revenues, but **JioMart** shows slightly better average ratings.

2. **Customer Sentiment**:

   * Majority of customers are **Neutral (61.64%)**, but **15.12%** are **Negative**, often linked to delivery staff behavior—an area needing urgent improvement.

3. **High Refund Rate**:

   * Refunds account for **45.82%** of orders, indicating issues with fulfillment or product quality that require attention.

4. **Revenue by Category**:

   * Top revenue-generating categories:

     * **Personal Care** – ₹17M
     * **Grocery** – ₹14M
     * **Beverages** – ₹9M
   * Suggests higher margins or demand for essential and personal items.

5. **Platform-wise Service Ratings**:

   * All platforms hover around the **3.2–3.3 rating** range, suggesting no one platform significantly outperforms others in perceived service quality.

6. **Actionable Feedback**:

   * Repetitive negative feedback like “Delivery person was rude” across platforms highlights the **need for staff training** and **customer service improvement**.

---

## 🖼️ Dashboard Features

* Interactive slicers by:

  * **Platform**
  * **Product Category**
  * **Sentiment**
* Charts include:

  * Refund vs No Refund count
  * Revenue by category
  * Sentiment distribution
  * Average rating per platform
* Clear KPIs shown in cards for executive summaries

---

## 📁 Project Structure

```
📁 Quickcommerce-DA-Project/
├── 📄 Quickcommerce_Dashboard.pbix
├── 📄 Quickcommerce DA project.pdf (Dashboard Screenshots)
├── 📄 README.md
```

---

## 📌 Future Improvements

* Integrate time-based trends (monthly performance).
* Drill-down to city/region-level analysis.
* Include delivery personnel performance metrics.
* Real-time data dashboard using Power BI Service.

---

## 🧑‍💼 Target Audience

This project is ideal for:

* **Hiring Managers** evaluating data analysts
* **Business decision-makers** in quick commerce
* **Data science learners** exploring Power BI and DAX
* **Startups** seeking data-driven growth strategies

---

## 🏁 Conclusion

This analysis provides a snapshot of the **quick commerce ecosystem in India**, leveraging **Power BI and DAX** to extract actionable insights. It serves as a model for businesses looking to improve delivery operations, customer satisfaction, and product focus.

---

## ⭐ Let’s Connect

If you found this project interesting, feel free to connect : adinathwork03@gmail.com

* ⭐ Star the repository
* 📬 Reach out for collaboration!

---

