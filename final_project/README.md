# Flipkart Sales Performance Dashboard

<img width="1547" height="872" alt="Screenshot 2026-04-05 121626" src="https://github.com/user-attachments/assets/1b866e46-0fa4-4998-9198-c3e1a88c3ed2" />


An interactive **Power BI dashboard** built to analyze Flipkart sales data and extract business insights related to revenue, profit, product categories, payment methods, and geographic distribution.

## Dashboard Insights

* Monthly **profit trends**
* Monthly **sales amount analysis**
* **Category-wise sales quantity**
* **Payment mode distribution**
* **Sub-category profit performance**
* **Regional sales visualization across India**

## Data Model

<img width="935" height="471" alt="Screenshot 2026-04-05 121639" src="https://github.com/user-attachments/assets/dcc119d7-22e4-4db0-9390-7b774ae9ec89" />


The dashboard uses a **two-table relational model**:

**Orders Table**

* Order ID
* Order Date
* Customer Name
* City
* State

**Details Table**

* Detail ID
* Order ID
* Category
* Sub Category
* Quantity
* Amount
* Profit
* Payment Mode

Relationship:

```
Orders[Order ID] 1 → * Details[Order ID]
```

## Tools Used

* Microsoft Power BI
* Power Query
* DAX
* Excel dataset

## Files Included

* `Flipkart_Dashboard.pbix` – Power BI dashboard file
* `dashboard_preview.png` – Dashboard screenshot
* Dataset (if shareable)

## Objective

To demonstrate **data modeling, dashboard design, and business insight generation** using Power BI.
