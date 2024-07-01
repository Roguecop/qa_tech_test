
## Title: Add single product to cart without using discounts

Description: Ensure that adding a single product to the cart works correctly.

Preconditions:

The cashier system is up and running.
The product data is correctly loaded from the YAML file.
No discount

Steps:

Open the cashier system.
Add 1 Green Tea (GR1) to the cart.

Expected Result:

The total price should be the same as the price in the .yaml related to the product

Postconditions:

The cart displays the added product with the correct total price.

## Title: Add multiple products to cart

Description: Ensure that adding multiple product to the cart works correctly.

Preconditions:

The cashier system is up and running.
The product data is correctly loaded from the YAML file.
No discount

Steps:

Open the cashier system.
Add 1 Green Tea, 1 Strawberries, and 1 Coffee to the cart.

Expected Result:

The total price should be the sun of all products used, as defined in the .yaml

Postconditions:

The cart displays the added product with the correct total price.
