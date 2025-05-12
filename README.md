# Retail Data Project
An open-source database project using a Kaggle online retail dataset for UK retail data from 2010-2011.

## Built Using 
* Docker
* Apache Airflow
* BigQuery, dbt (Cosmos)
* Python
* SQL
* Soda
* bash

## Dataset 
https://www.kaggle.com/datasets/tunguz/online-retail 

| Column  | Description |
| ------- | ----------- |
| InvoiceNo  | Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.  |
| StockCode  | Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.  |
| Description  | Product (item) name. Nominal.  |
| Quantity  | The quantities of each product (item) per transaction. Numeric.  |
| InvoiceDate  | Invoice Date and time. Numeric, the day and time when each transaction was generated.  |
| UnitPrice  | Unit price. Numeric, Product price per unit in sterling.  |
| CustomerID  | Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.  |
| Country  | Country name. Nominal, the name of the country where each customer resides.  |

## Data Pipeline 

![image](https://github.com/user-attachments/assets/150f5193-3cf9-43df-bdca-48d5070a6162)

## Data Modelling
<img src="https://img.notionusercontent.com/s3/prod-files-secure%2F9abc35a8-365d-406e-9fce-27f6f89eb34e%2Fb2b83771-d029-4c3f-bd46-a34916b83dd9%2FScreenshot_2023-07-13_at_16.59.35.png/size/w=1420?exp=1747148314&sig=w-KAg1SsMHYs9fXOYldIxLN6PBX7hESDbFEyKvwarDM&id=734f8e5b-5fd0-4947-8cbb-1a952e3b80fe" width=50% height=50%>

## Prerequisites

* Docker
* Astro CLI
* Soda
* Google Cloud

