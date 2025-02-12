# Analyzing Best Performing Salespeople and Products for AdventureWorks

## **Overview**
This project focuses on analyzing the best-performing salespeople and products for AdventureWorks, a company that sells outdoor sporting equipment. The goal is to extract meaningful insights from the sales data to help improve overall performance.

---

## **Introduction**

### **Business Context**
AdventureWorks operates in multiple locations and sells a variety of outdoor sporting equipment. The company has been recording sales data across different locations and products. As the new data scientist, my task is to identify the best-performing products and salespeople and provide actionable insights to boost sales.

### **Business Problem**
The primary objectives are:
1. **Identify the best-performing products** by analyzing sales data across different categories.
2. **Analyze the best-performing salespeople** to determine if commission percentages motivate them to sell more.

To achieve this, I wrote SQL queries to extract and analyze the relevant data.

---

## **Dataset Information**
**Product Table:**
- Product: one row per product that the company sells
- ProductReview: one row per rating and review left by customers
- ProductModelProductDescriptionCulture: a link between products and their longer descriptions also indicating a “culture” - which language and region the product is for
- ProductDescription: a longer description of each product for a specific region
- ProductCategory: the broad categories that products fit into
- ProductSubCategory: the narrower subcategories that products fit into

**Sales Table:**
- SalesPerson: one row per salesperson, including information on their commission and performance
- SalesOrderHeader: one row per sale summarizing the sale
- SalesOrderDetail: many rows per sale, detailing each product that forms part of the sale
- SalesTerritory: the different territories where products are sold, including performance
- CountryRegionCurrency: the currency used by each region
- CurrencyRate: the average and closing exchange rates for each currency compared to the USD
