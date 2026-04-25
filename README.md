# Pizza-Sales-SQL-Project
Title: Pizza Sales Database Analysis
# Introduction :
This project analyzes pizza sales data
Focus on order patterns, revenue, and product performance
Database includes multiple related tables

# Database Schema : 
# Tables used -
Orders
Order Details
Pizza
Pizza Types

# Explain relationships briefly :
One order → many order_details
Each pizza linked to pizza_types

# Orders Table : 
order_id (Primary Key)
order_date
order_time
# Purpose :
Stores basic order information

# Order Details Table :
order_details_id (Primary Key)
order_id (Foreign Key)
pizza_id
quantity
# Purpose :
Stores items in each order

# Pizza Table :
pizza_id
pizza_type_id
size
price
# Purpose :
Stores pizza variants and pricing

# Pizza Types Table :
pizza_type_id
name
category
ingredients
# Purpose:
Describes pizza categories and composition

# Key Insights :
Most ordered pizza category.
Peak order time.
Highest revenue-generating pizzas.

# Conclusion :
Database helps track sales trends
Useful for decision-making
Can improve marketing and inventory



















