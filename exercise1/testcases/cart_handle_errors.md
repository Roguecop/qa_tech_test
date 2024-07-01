## Title: Invalid Product Code

Description: Ensure the system handles invalid product codes gracefully.

Preconditions:

The cashier system is up and running.
The product data is correctly loaded from the YAML file.

Steps:

Open the cashier system.
Add an unexpected product code. Cannot exist in the .yaml

Expected Result:

No price displayed or error message

Postconditions:

The cart displays no price and shows the existence of an error

## Title: Invalid Price

Description: Ensure the system handles wrong prices

Preconditions:

The cashier system is up and running.
The product data is correctly loaded from the YAML file, but the price is negative

Steps:

Open the cashier system.
Add an product with a negative price or price equal to zero.

Expected Result:

No price displayed or error message

Postconditions:

The cart displays no price and shows the existence of an error

## Title: No name of product

Description: Ensure the system handles wrong prices

Preconditions:

The cashier system is up and running.
The product data is correctly loaded from the YAML file

Steps:

Open the cashier system.
Add an product with no name

Expected Result:

No price displayed or error message

Postconditions:

The cart displays no price and shows the existence of an error


