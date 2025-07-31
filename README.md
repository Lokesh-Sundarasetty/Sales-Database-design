# Sales Database SQL Project

## Overview
This project demonstrates the design and querying of a relational retail database using MySQL. The database manages customers, products, orders, order items, and returns to provide insights into sales performance, customer behavior, and product returns.

The goal is to showcase SQL skills, including data modeling, data population, complex joins, aggregate functions, window functions, and foreign key relationships.

## Database Schema
The database consists of five core tables:
- **customers**: Contains customer information (ID, first/last name, email, join date).  
- **products**: Stores product details like name, category, and price.  
- **orders**: Records order-level data linked to customers via customer ID.  
- **order_items**: Represents items in each order, linking products with quantity and price.  
- **returns**: Tracks returned items related to order items, including return date and reason.

Primary keys and foreign keys enforce data integrity and relationships between tables.

## Sample Data
The database is populated with realistic sample data:
- 15 customers with varied join dates and emails.  
- 10 products covering categories like Electronics, Furniture, Apparel, Accessories, Appliances.  
- Multiple orders and order items spanning different dates.  
- Returns linked to specific order items with reasons for return.
- 
## Key SQL Queries Included
- Count of records in each table for data overview.  
- Total sales revenue by month to observe trends.  
- Top customers by total spending.  
- Products with the highest return counts.  
- Products generating the highest total revenue.  
- Customers who returned products and their return frequency.  
- Monthly return rates (% of orders with returns).  
- The most sold product in each category using window functions (RANK).  
- Products ordered but never returned.

Each query demonstrates essential SQL concepts like joins, aggregations, grouping, filtering, and window functions.

## How to Use
1. **Setup Database**  
   Run the provided SQL scripts to create the database schema and populate tables with sample data.

2. **Run Queries**  
   Execute the included SQL queries to generate insights about the retail data.

3. **Visualize Results** (Optional)  
   Export query results or connect the database to visualization tools like Power BI for graphical analysis.

## Challenges and Notes 
- Ensured data integrity with foreign keys and carefully designed table relations.  
- Applied RANK() window function to identify top products per category.  
- Queries are designed to be modular and extensible for future enhancements.

## Future Enhancements
- Add discount and promotion tables for more complex analytics.  
- Incorporate customer demographic data for richer insights.  
- Develop stored procedures or views for common business reports.  
- Integrate with dashboards for real-time monitoring.

## Contact
For questions or feedback, please reach out to my LinkedIn: www.linkedin.com/in/lokesh-kumar-sundarasetty 


### License

This project is licensed under the MIT License.


