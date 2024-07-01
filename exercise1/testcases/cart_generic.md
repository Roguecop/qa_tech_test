## Title: All elements in the page are displayed

Description: Ensure all the expected elements are present

Preconditions:

The cashier system is up and running.

Steps:

Open the cashier system.

Expected Result:

The elementd defined in the requirements are present

Postconditions:

The elementd defined in the requirements are present

## Title: Add no product to the cart

Description: Ensure the correct behavior when no product have been added to the cart

Preconditions:

The cashier system is up and running.

Steps:

Open the cashier system.

Expected Result:

The total price is 0

Postconditions:

The card have nothing inside and the price is 0

## Title: Add and remove products

Description: Ensure the correct behavior when a product is added or removed

Preconditions:

The cashier system is up and running.
The product data is correctly loaded from the YAML file.

Steps:

Open the cashier system.
Add 1 Green Tea (GR1) to the cart.
Check the price
Remove 1 Green Tea (GR1)
Check the price

Expected Result:

The total price is 0

Postconditions:

The card have nothing inside and the price is 0
