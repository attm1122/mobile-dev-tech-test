# mobile-dev-tech-test

## What to do
You have been asked by one of our clients to develop an product store mobile application. 

## Before everything
Create a new branch from master with your name

## Tasks
Please navigate to the projects tab and open the Product App stories. Complete as much stories as possible.
- Move the story in progress column when working on it
- Move the story in done column when done with it

## What do we test
__Do not go crazy__

- We prefer test over documentation
- We prefer quality over quantity
- Simplicity first
- Focus on tasks no extras
- SOLID Principles

## Api
Use our api to add and view the products.

### Base Endpoint
[https://paloit-products.azurewebsites.net/](https://paloit-products.azurewebsites.net/)

### Products Endpoint
[https://paloit-products.azurewebsites.net/products](https://paloit-products.azurewebsites.net/products)

#### GET All Products
 - get https://paloit-products.azurewebsites.net/products

#### GET One product
 - get https://paloit-products.azurewebsites.net/products/{id}
 >> example get https://paloit-products.azurewebsites.net/products/1
 
#### POST Product
 - post https://paloit-products.azurewebsites.net/products/
 - example body:
 ```$json
    {
        "name": "Soup",
        "price": 11.90,
        "description": "Tomato soup.",
        "image": "base64:fklkfglkjfg..."
    }
 ```

 
