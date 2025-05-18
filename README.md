# Maven-Coffee-sales-Analysis

-- Table
CREATE TABLE IF NOT EXISTS transactions (
    transaction_id INT PRIMARY KEY AUTO_INCREMENT,
    transaction_date DATE NOT NULL,
    transaction_time TIME NOT NULL,
    transaction_qty INT NOT NULL CHECK (transaction_qty >= 0),
    store_id INT NOT NULL,
    store_location VARCHAR(100),
    product_id INT NOT NULL,
    unit_price DECIMAL(10, 2) NOT NULL CHECK (unit_price >= 0),
    product_category VARCHAR(50),
    product_type VARCHAR(100),
    product_detail VARCHAR(100)
);

