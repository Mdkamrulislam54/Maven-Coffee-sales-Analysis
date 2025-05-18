# Maven-Coffee-sales-Analysis

-- Table
Column Name	Data Type	Description
transaction_id	INT	Unique ID for each transaction (auto-increment).
transaction_date	DATE	Date of the transaction.
transaction_time	TIME	Time of the transaction.
transaction_qty	INT	Quantity of product sold.
store_id	INT	ID of the store where the sale occurred.
store_location	VARCHAR(100)	Location name or address of the store.
product_id	INT	ID of the product sold.
unit_price	DECIMAL(10,2)	Price per unit of the product.
product_category	VARCHAR(50)	High-level product category (e.g., electronics).
product_type	VARCHAR(100)	Specific product type (e.g., smartphone).
product_detail	VARCHAR(100)	Extra details (e.g., brand, color, model).
