# FastAPI Internship Assignment – E-commerce API

This project is built using FastAPI and Python as part of the FastAPI Internship training. The API simulates a simple e-commerce system where users can view products, filter them by category, check available products, search items, and view store summary statistics.

## Features
- Get all products
- Filter products by category
- Show only in-stock products
- Store summary with product statistics
- Search products by keyword
- Bonus: Find the cheapest and most expensive products

## Technologies Used
- Python
- FastAPI
- Uvicorn
- Swagger UI

## API Endpoints

| Endpoint | Description |
|--------|-------------|
| /products | Get all products |
| /products/category/{category_name} | Filter products by category |
| /products/instock | Get only available products |
| /store/summary | Store statistics summary |
| /products/search/{keyword} | Search products |
| /products/deals | Cheapest and most expensive products |

## Running the Project

Install dependencies:

pip install fastapi uvicorn

Run the server:

uvicorn main:app --reload

Open Swagger UI:

http://127.0.0.1:8000/docs

## Project Structure

├── main.py  
├── Q1_Output.png  
├── Q2_Output.png  
├── Q3_Output.png  
├── Q4_Output.png  
└── Q5_Output.png  

## Author
Praveen Kumar Kandi
