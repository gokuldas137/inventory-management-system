# Inventory Management System with Spring Boot - 2022

This Inventory Management System is developed using Java 17 and Spring Boot 2.7.5 with MySQL as the database. It facilitates efficient tracking of stocks, alerts administrators when inventory levels exceed predefined thresholds, and enables seamless supply chain management by allowing users to request replenishment from vendors. 

## Technologies Used

- Java 17
- Spring Boot 2.7.5
- MySQL
- GitHub
- Intellij

## Features

### Inventory Management

- **Systematic Record Keeping**: Stores details of inventory such as category, products, suppliers, and invoices.
- **Stock Maintenance**: Keeps stock levels up-to-date by calculating remaining stocks.
- **Order Fulfillment**: Ensures proper and timely order fulfillment, updating inventory based on sales details.
- **Stock Availability Alerts**: Sends email alerts to maintain stock availability whenever levels are low.
- **Inventory Accuracy**: Organizes and streamlines inventory placement and acquisition for better fulfillment.
- **User Service Improvement**: Enhances user service practices by optimizing inventory management.

### Functionalities

- **Register/Login**: Users can register and login using JWT token authentication.
- **Pricing Strategy**: Selling price of products is generated based on discount percentage from Maximum Retail Price.
- **Email Notifications**: Customers receive email purchase details; company receives email order details from suppliers.
- **PDF Invoices**: Generates PDF invoices for customer purchases and supplier orders.
- **Stock Updates**: Automatically updates stock quantities upon sales or placing orders.
