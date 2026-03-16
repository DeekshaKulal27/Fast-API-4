# FastAPI Cart System -- Day 5 Assignment

## Overview

This project implements a simple Shopping Cart API using FastAPI. Users
can add products to a cart, view the cart, remove items, checkout, and
view orders.

## Technologies

-   Python
-   FastAPI
-   Uvicorn
-   Swagger UI

## Run the Project

Install dependencies: pip install fastapi uvicorn

Run server: python -m uvicorn main:app --reload --port 8001

Open Swagger: http://127.0.0.1:8001/docs

## API Endpoints

### Cart

POST /cart/add -- Add product to cart\
GET /cart -- View cart\
DELETE /cart/{product_id} -- Remove item from cart\
POST /cart/checkout -- Checkout cart

### Orders

GET /orders -- View orders

## Sample Products

1 -- Wireless Mouse -- ₹499\
2 -- Notebook -- ₹99\
3 -- USB Hub -- Out of Stock\
4 -- Pen Set -- ₹49

## Example Checkout

grand_total = 1097\
orders_created = 2

## Project Structure

YOUR_INTERNID_FASTAPI └── ASSIGNMENT 2 ├── main.py ├── Q1_Output.png ├──
Q2_Output.png ├── Q3_Output.png ├── Q4_Output.png ├── Q5_Output.png ├──
Q6_Output.png └── README.md
