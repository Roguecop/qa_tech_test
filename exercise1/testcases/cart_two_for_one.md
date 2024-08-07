
## Title: Add single product to cart using discounts of two for one

Description: Ensure that adding a single product to the cart works correctly with discounts.

Preconditions:

The cashier system is up and running.
The product data is correctly loaded from the YAML file.
Discount of two for one

Steps:

Open the cashier system.
Add 1 Green Tea (GR1) to the cart.

Expected Result:

The total price should be the same as the price in the .yaml related to the product. No discount is applied

Postconditions:

The cart displays the added product with the correct total price.

## Title: Add one product multiple times to cart using discounts of two for one

Description: Ensure that adding a single product to the cart works correctly with discounts.

Preconditions:

The cashier system is up and running.
The product data is correctly loaded from the YAML file.
Discount of two for one

Steps:

Open the cashier system.
Add 2 Green Tea (GR1) to the cart.
Check the price
Erase and add 100 Green Tea (GR1) to the cart.
Check the price
Erase and add 3 Green Tea (GR1) to the cart.
Check the price


Expected Result:

The total price should be the discounted price 

Postconditions:

The cart displays the added product with the discounted total price.


## Title: Add multiple products to cart using discounts of two for one


Description: Ensure that adding a single product to the cart works correctly with discounts.

Preconditions:

The cashier system is up and running.
The product data is correctly loaded from the YAML file.
Discount of two for one

Steps:

Open the cashier system.
Add 100 Green Tea (GR1) to the cart. 1 Strawberries, and 1 Coffee to the cart.

Expected Result:

The total price should be the discounted price, only to the product with N quantity

Postconditions:

The cart displays the added product with the discounted total price.

## Title: Add multiple products multiple times to cart using discounts of two for one


Description: Ensure that adding a single product to the cart works correctly with discounts.

Preconditions:

The cashier system is up and running.
The product data is correctly loaded from the YAML file.
Discount of two for one

Steps:

Open the cashier system.
Add 100 Green Tea (GR1) to the cart. 100 Strawberries, and 100 Coffee to the cart.

Expected Result:

The total price should be the discounted price. With the correct discount to all the products

Postconditions:

The cart displays the added product with the discounted total price.

## Title: Add multiple products multiple times to cart using discounts of two for one only in some of them


Description: Ensure that adding a single product to the cart works correctly with discounts.

Preconditions:

The cashier system is up and running.
The product data is correctly loaded from the YAML file.
Discount of two for one in coffee and tea. Not in Strawberries

Steps:

Open the cashier system.
Add 100 Green Tea (GR1) to the cart. 200 Strawberries, and 300 Coffee to the cart.

Expected Result:

The total price should be the discounted price. With the correct discount to coffee and tea

Postconditions:

The cart displays the added product with the discounted total price.