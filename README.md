Zepto Product Analytics

📌 Project Overview

Conducted end-to-end analysis of Zepto’s product catalog containing 10,000+ SKUs across 50+ categories to identify opportunities in inventory management, pricing strategy, and revenue generation. Using MySQL and Excel, I cleaned the dataset, performed exploratory analysis, and developed data-driven business recommendations. The analysis identified ₹27L+ in potential value through revenue recovery, margin improvement, and inventory optimisation.

🎯 Business Problems

The analysis focused on several business challenges:

* Revenue leakage from high-value products being out of stock
* Inefficient discounting across product categories
* Slow-moving inventory tying up working capital
* Inefficient warehouse space allocation
* Duplicate products with inconsistent pricing
* Limited visibility into category-level performance
* Missed opportunities to identify high-value products for customer retention
* Inconsistent pricing patterns across categories

❓ Business Questions

1. Which categories generate the most revenue?
2. Are stockouts of high-value products contributing to revenue loss?
3. Which products offer the best value for customers?
4. Are discounts appropriately distributed across categories?
5. How can warehouse space be optimised based on weight-to-value ratios?
6. How much working capital is tied up in slow-moving inventory?
7. How are products distributed by size, and how does size relate to pricing?
8. Are duplicate products creating pricing inconsistencies?

📊 Dataset

Source: Zepto Product Catalog
Records: 10,000+ SKUs
Categories: 50+

Key Attributes

* SKU ID
* Category
* Product Name
* MRP
* Discount %
* Available Quantity
* Discounted Selling Price
* Weight (g)
* Stock Status

Data Quality

Initial data quality checks identified:

* 47 invalid price records
* 150+ duplicate records
* NULL values across 5 columns
* 92% initial completeness

After cleaning, the dataset was standardised and prepared for analysis.

🔍 Analysis & Key Insights

Revenue Analysis

* Five categories generated approximately 65% of total revenue: Groceries, Beverages, Personal Care, Household Essentials, and Packaged Food.
* Snacks and Beverages offered 40%+ discounts while contributing approximately 15% of revenue.
* Revenue was concentrated within a relatively small number of categories despite the broad product range.

Inventory Analysis

* Identified 47 high-value products priced above ₹500 with discounts below 10% that were consistently out of stock.
* Estimated ₹6.1L+ in annual revenue loss associated with these stockouts.
* Identified 300+ slow-moving SKUs representing approximately ₹15L in tied-up inventory.
* Electronics generated approximately 10x the value per kilogram compared with Groceries (₹12,000 vs ₹1,200/kg).

Customer & Product Analysis

* Identified 200+ products offering less than ₹1 per gram, representing potential value-for-money opportunities.
* Bulk products (5kg+) received approximately 25% lower discounts, indicating potential pricing opportunities.
* Identified 150+ duplicate products with inconsistent pricing.

💡 Business Recommendations

Quick Wins

* Increase reorder frequency for 47 high-value products to address stockout-related revenue loss.
* Introduce a “Best Value” product category featuring identified value-for-money products.
* Launch clearance campaigns for 300+ slow-moving SKUs to release tied-up working capital.

Strategic Recommendations

* Review discounting strategies for Snacks and Beverages to improve margin efficiency.
* Consolidate duplicate SKUs with inconsistent pricing.
* Prioritise warehouse space based on product value density.

Long-Term Recommendations

* Develop an automated reporting dashboard for continuous KPI monitoring.
* Implement A/B testing to evaluate pricing strategies.
* Conduct monthly category performance reviews.

🛠️ Tools & Technologies

* MySQL
* SQL
* Excel
* Pivot Tables
* Charts
* GitHub
* Markdown

SQL Techniques

* Common Table Expressions (CTEs)
* Window Functions
* Subqueries
* CASE statements
* JOINs
* Aggregations
* Data Cleaning

📈 Impact Summary

Opportunity	Estimated Impact
Revenue recovery	₹6.1L+ annually
Inventory optimisation	₹15L
Potential margin improvement	₹2.25L
Logistics optimisation	20% potential cost reduction
Products identified for marketing	200+
Estimated first-year ROI	173%

🔑 Skills Demonstrated

* Data Cleaning & Quality Assurance
* Advanced SQL Analysis
* Business Intelligence & Reporting
* Revenue Analysis
* Inventory Analysis
* Pricing Analysis
* Data Visualisation
* Business Recommendation Development


📌 Conclusion

The analysis demonstrated how SQL and Excel can be used to transform a large product catalogue into actionable business insights. The findings highlighted opportunities to reduce stockouts, optimise inventory, improve pricing decisions, and identify potential revenue and margin improvements.
