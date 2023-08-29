# Art Gallery Project

## Description

This project is a simple art gallery website that allows users to view and purchase art.

## Table of Contents

- Backend API (laravel)
- Database (mysql)
- Website (angular)
- Admin Panel (angular)

## Requirements

### Website

- User registration
- User login
- User logout
- Cart page
- Checkout page
- Product listing
- Product details
- Product search

### Admin Panel

- Authentication
  - Login
  - Logout
- Product
  - List all products and search by name
  - Create new product
  - Update product
  - Delete product
- Order
  - List all orders and search by order number
  - Details of an order
  - Update status of an order
- Customers
  - List all customers

## Specifications

### Data Model

#### Product

- Name
- Description
- Price
- Stock
- Image
- Category
- Status

#### Order

- Order number
- Customer name
- Customer email
- Customer phone
- Customer address
- Order status
- Order date
- Order items
  - Product name
  - Product price
  - Product quantity
  - Product subtotal
- Order total

#### Customer

- Name
- Email
- Phone
- Address

### Business Logic

#### Admin Panel

- Only admin can access
- Only admin can create, update, delete products
- Only admin can update order status
- Only admin can view customer list

#### Website

- Only logged in user can checkout
- Only logged in user can view order history
- Only logged in user can view cart
- Only logged in user can add product to cart
- Only logged in user can remove product from cart
- Only logged in user can update product quantity in cart
- Only logged in user can view profile
- user can view product details
- user can search product
- user can view product list

#### Backend

- Database must be migrated and seeded with sample data
