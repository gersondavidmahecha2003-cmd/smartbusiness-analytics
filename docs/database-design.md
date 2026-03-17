# Database Design

## Users
id
name
email
password
role
created_at

## Clients
id
name
email
phone
company
created_at

## Products
id
name
description
price
stock
created_at

## Orders
id
client_id
total
status
created_at

## OrderItems
id
order_id
product_id
quantity
price
