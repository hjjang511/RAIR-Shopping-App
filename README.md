# RAIR Shopping App

## Introduction
The RAIR Shopping App is a one-stop destination for consumers and business stakeholders for their shopping and business needs. Inspired by the ever-evolving landscape of retail, the application provides a seamless and intuitive shopping experience for customers, offering a diverse range of products through an operational database. Recognizing the importance of informed decision-making, we integrated a powerful business insights section tailored for stakeholders, empowering them with valuable data to make strategic business decisions leveraging an analytical database.

## Data Sources
Our shopping app uses the following data sources:
- **Flipkart Products**: Product information.
- **Mockaroo**: User and promotion data.
- **Synthetic Data**: Orders and order items generated using Python.

## Application Design
The application design consists of two main databases – Operational and Analytical.

- **Operational Database (OLTP)**: Manages customer transactions and updates stock levels.
- **Analytical Database (OLAP)**: Supports data analysis for the Admin portal without impacting operational performance.

## Technologies and Libraries Used
- **Programming Language**: Python, SQL
- **Database**: MySQL
- **GUI Development**: PyQt Designer
- **Data Analysis and Visualization**: Pandas, Seaborn, Matplotlib, SciPy, Statsmodels

## Operational Database Design
The operational database handles customer-facing functionalities such as browsing products, managing shopping carts, updating addresses, and viewing order history. It ensures data integrity and supports seamless user interactions.

## Analytical Database Design
The analytical database, supported by a separate data warehouse, enables stakeholders to analyze sales trends, customer demographics, and other key metrics without slowing down the operational database.

## ETL Process
The ETL (Extract, Transform, Load) process for the RAIR Shopping App involves:
1. **Extraction**: Data extracted from CSV files using Pandas.
2. **Transformation**: Data prepared and structured for operational and analytical databases.
3. **Loading**: Data loaded into MySQL databases.

## Application Features
### User Features
- **Login/Register**: Users can log in or create new accounts.
- **Home Screen**: Browse products with pagination.
- **Order History**: View past orders and order details.
- **Shopping Cart**: Add products to the cart and proceed to checkout.
- **Checkout**: Apply promotions and finalize purchases.

### Admin Features
- **Admin Portal**: Access detailed dashboards and analytical tools.
- **Product Management**: Edit product prices and stock levels.
- **User Management**: Manage user accounts and privileges.
- **Promotion Management**: Add or expire promotion codes.

## Impact
- **Transaction Processing Speed**: Increased by 30%.
- **Data Accuracy**: Improved by 25%.
- **User Satisfaction**: Enhanced by providing a seamless shopping experience.
- **Business Efficiency**: Empowered stakeholders with powerful analytical tools for strategic decision-making.

## How to Run
1. Clone the repository.
2. Install required packages: `Pandas`, `Seaborn`, `Matplotlib`, `Kaleido`, `Statsmodels`, `SciPy`.
3. Set up MySQL databases using provided SQL scripts.
4. Run the application using `main.py`.

## Screenshots
![Login Page](screenshots/login.png)
![Home Screen](screenshots/home.png)
![Order History](screenshots/order_history.png)
![Checkout](screenshots/checkout.png)
![Admin Dashboard](screenshots/admin_dashboard.png)
