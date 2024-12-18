# Currency Exchange Database API
## Overview
This project provides a simple REST API for currency exchange rates. It stores currency codes and their respective exchange rates in a MySQL database. Users can fetch the latest exchange rates between different currencies.

## Features
- List all currencies: Retrieve a list of all currencies available in the database.
- Get latest exchange rate: Fetch the latest exchange rate for a specific currency pair (e.g., USD to EUR).
- Data Source: The exchange rates are fetched and stored using an external source, yfinance 

## API Endpoints
### GET /currency/
Description: Fetches a list of all available currencies in the database.
### GET /currency/{currency_from}/{currency_to}/
Description: Fetches the latest exchange rate for the given currency pair 
### Combinations
- /currency/EUR/USD/
- /currency/USD/JPY/
- /currency/PLN/USD/

## screenshots:
## GET /currency/
![image](https://github.com/user-attachments/assets/e1a970c2-fdc6-48b0-b156-258d5e7fa406)


## GET /currency/EUR/USD/
![image](https://github.com/user-attachments/assets/a4264d4d-25cd-492b-9c1b-fe5d6a4d3d62)

## GET /currency/EUR/USD/
![image](https://github.com/user-attachments/assets/64daacee-ed06-4c65-9676-db0fa508a49a)

## GET /currency/EUR/USD/
![image](https://github.com/user-attachments/assets/672e51d9-3bc9-4344-9c8a-377c3914e3fb)

## ADMIN Interface:
![image](https://github.com/user-attachments/assets/7f223421-30b0-46df-8a4c-e713c7e08c5f)
![image](https://github.com/user-attachments/assets/0ba442e3-bdc2-4259-8cc0-5a61a9c0b4e6)
![image](https://github.com/user-attachments/assets/34eb59c8-7862-4be9-a5d2-cce1f32294ff)
Stores data from last 30 days.
