# FastAPI Assignment 1

This assignment focuses on building REST API endpoints using FastAPI.  
All tasks are implemented in a single main.py file.

--------------------------------------------------

**1. Add 3 More Products**

Scenario:
Your client added three new products to their store:
Laptop Stand, Mechanical Keyboard, and Webcam.

Tasks:
- Create endpoint: GET /products
- Add 3 new products to the products list with IDs 5, 6, and 7
- Each product must include:
  id
  name
  price
  category
  in_stock

--------------------------------------------------

# FastAPI Assignment 1

This assignment focuses on building REST API endpoints using FastAPI.  
All tasks are implemented in a single main.py file.

--------------------------------------------------

1. Add 3 More Products

Scenario:
Your client added three new products to their store:
Laptop Stand, Mechanical Keyboard, and Webcam.

Tasks:
- Create endpoint: GET /products
- Add 3 new products to the products list with IDs 5, 6, and 7
- Each product must include:
  id
  name
  price
  category
  in_stock

--------------------------------------------------

**2. Add a Category Filter Endpoint**

Scenario:
The mobile app should display products based on category
such as Electronics or Stationery.

Tasks:
- Create endpoint: GET /products/category/{category_name}
- Return only products where the category matches the given name
- If no products are found, return:
  {"error": "No products found in this category"}

--------------------------------------------------

**3. Show Only In-Stock Products**

Scenario:
Customers should only see products that are available in stock.

Tasks:
- Create endpoint: GET /products/instock
- Return only products where in_stock = True
- Also return the count of in-stock products

--------------------------------------------------

**4. Build a Store Info Endpoint**

Scenario:
The store homepage should display a summary of the store.

Tasks:
- Create endpoint: GET /store/summary
- Return:
  Total products count
  In-stock products count
  Out-of-stock products count
  List of unique product categories

--------------------------------------------------

**5. Search Products by Name**

Scenario:
Users should be able to search products using a keyword.

Tasks:
- Create endpoint: GET /products/search/{keyword}
- Search must be case-insensitive
- Return matched products
- If no product matches, return:
  {"message": "No products matched your search"}
- Return total number of matches

--------------------------------------------------

**6. Cheapest & Most Expensive Product**

Scenario:
The store wants to show the cheapest product as the Best Deal
and the most expensive product as the Premium Pick.

Tasks:
- Create endpoint: GET /products/deals
- Return:
  best_deal → product with the lowest price
  premium_pick → product with the highest price

--------------------------------------------------

Technologies Used:
Python
FastAPI
Uvicorn

