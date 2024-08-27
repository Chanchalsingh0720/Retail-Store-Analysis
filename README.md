# E-commerce Data Analysis

## Project Overview

This project focuses on analyzing e-commerce data to understand order fulfillment and customer demographics. By examining order performance, customer acquisition channels, and referral behaviors, the analysis aims to provide actionable insights to improve customer experience and business operations.

## Data Description

### Orders Data (`Orders_Data`)

| Column Name     | Description                                  |
|-----------------|----------------------------------------------|
| ORDER_NUMBER    | Unique identifier for each order             |
| CUSTOMER_KEY    | Identifier linking orders to customers       |
| ORDER_TOTAL     | Total value of the order (can be negative for returns) |
| DISCOUNT        | Discount applied to the order                |
| ORDER_DATE      | Date when the order was placed               |
| ORDER_STATUS    | Status of the order (Delivered, Cancelled)   |
| DELIVERY_STATUS | Timeliness of the delivery (ON-TIME, LATE)   |

### Customer Data (`Customer_Data`)

| Column Name              | Description                                      |
|--------------------------|--------------------------------------------------|
| CUSTOMER_ID              | Unique identifier for each customer              |
| CUSTOMER_KEY             | Identifier used to link customers to orders      |
| CONTACT_NUMBER           | Customer's contact number                        |
| Referred Other customers | Indicates if the customer referred others (Y/N)  |
| Gender                   | Gender of the customer                           |
| Location                 | Customer's location                              |
| Acquired Channel         | Channel through which the customer was acquired  |

## Key Insights

1. **Order Fulfillment:** The majority of orders were delivered on time, demonstrating effective logistics. However, there is a need to investigate occasional delays and cancellations.

2. **Customer Acquisition:** The app is a strong acquisition channel, with most customers coming through it. There's potential to enhance the referral program to further leverage existing customers.

3. **Data Quality:** Duplicate entries and inconsistencies in customer data suggest a need for data cleansing to ensure accurate analysis.

4. **Demographics and Behavior:** Male customers dominate the dataset, and there are indications that female customers tend to make higher-value purchases. Understanding these patterns can help in targeted marketing.

## Recommendations

- **Optimize Logistics:** Address the reasons for late deliveries and cancellations to enhance customer satisfaction.
- **Enhance Referral Programs:** Encourage more customers to refer others, leveraging existing satisfied customers.
- **Improve Data Accuracy:** Clean and validate customer data to ensure reliable insights.
- **Focus on High-Value Customers:** Develop strategies to engage high-value customers, especially females, who show a propensity for higher-value orders.

## How to Use This Repository

1. **Data Files:** The dataset files (`Orders_Data.csv` and `Customer_Data.csv`) are available in the `data` directory.
2. **Analysis Notebooks:** Jupyter notebooks for data cleaning, analysis, and visualization are provided in the `notebooks` directory.
3. **Reports:** A summary of findings and recommendations can be found in the `reports` directory.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

