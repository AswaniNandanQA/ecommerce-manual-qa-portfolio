E-commerce Add to Cart – Test Cases
Module: Shopping Cart
Test Objective: To verify that users can add products to the shopping cart and manage cart items correctly.
Preconditions:
•	The e-commerce website is accessible.
•	Products are available in the product catalogue.
•	The user is logged in if login is required to use the cart.
________________________________________


TC-CART-001: Add a single product to the cart
•	Test Data: Laptop
•	Steps:
1.	Open the e-commerce website.
2.	Select a laptop.
3.	Click the Add to Cart button.
4.	Open the shopping cart.
•	Expected Result: The selected laptop should appear in the cart.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CART-002: Add multiple different products to the cart
•	Test Data: Laptop, Mobile, Headphones
•	Steps:
1.	Select a laptop and click Add to Cart.
2.	Select a mobile and click Add to Cart.
3.	Select headphones and click Add to Cart.
4.	Open the cart.
•	Expected Result: All three selected products should appear in the cart.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CART-003: Verify cart item count
•	Test Data: Add two different products.
•	Steps:
1.	Add the first product to the cart.
2.	Add the second product.
3.	Observe the cart item count.
•	Expected Result: The cart count should reflect the number of cart items according to the website's counting rules.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CART-004: Add the same product multiple times
•	Test Data: Laptop
•	Steps:
1.	Add a laptop to the cart.
2.	Return to the product page.
3.	Add the same laptop again.
4.	Open the cart.
•	Expected Result: The cart should handle the repeated addition correctly, either by increasing quantity or displaying separate lines according to the requirements.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CART-005: Increase product quantity in the cart
•	Test Data: Laptop, quantity 2
•	Steps:
1.	Add a laptop to the cart.
2.	Open the cart.
3.	Increase the quantity to 2.
•	Expected Result: The product quantity should update to 2 and the subtotal should be recalculated correctly.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CART-006: Decrease product quantity in the cart
•	Test Data: Laptop, quantity 2
•	Steps:
1.	Add a laptop to the cart.
2.	Increase its quantity to 2.
3.	Decrease the quantity to 1.
•	Expected Result: The quantity should update to 1 and the subtotal should be recalculated correctly.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CART-007: Verify minimum quantity limit
•	Test Data: Quantity 0
•	Steps:
1.	Add a product to the cart.
2.	Try to reduce its quantity below 1 or enter 0.
•	Expected Result: The system should prevent an invalid quantity or remove the item only according to the defined cart behaviour.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CART-008: Verify maximum quantity limit
•	Test Data: Quantity greater than available stock
•	Steps:
1.	Add a product to the cart.
2.	Try to increase its quantity beyond the available stock.
•	Expected Result: The system should prevent quantities exceeding available stock and display an appropriate message.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CART-009: Remove a product from the cart
•	Test Data: Laptop
•	Steps:
1.	Add a laptop to the cart.
2.	Open the cart.
3.	Click Remove for the laptop.
•	Expected Result: The laptop should be removed from the cart.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CART-010: Remove all products from the cart
•	Test Data: Laptop, Mobile, Headphones
•	Steps:
1.	Add three different products to the cart.
2.	Remove each product.
3.	Observe the cart.
•	Expected Result: The cart should display an appropriate empty-cart message.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CART-011: Verify product price in the cart
•	Test Data: A product with a known displayed price.
•	Steps:
1.	Note the product price on its product page.
2.	Add the product to the cart.
3.	Compare the displayed price in the cart.
•	Expected Result: The cart should display the correct product price according to the pricing rules.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CART-012: Verify cart subtotal calculation
•	Test Data: Product price ₹1,000, quantity 2
•	Steps:
1.	Add the product to the cart.
2.	Set quantity to 2.
3.	Observe the subtotal.
•	Expected Result: The subtotal should be ₹2,000 before any applicable discounts, taxes, or shipping charges.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CART-013: Verify cart persistence after page refresh
•	Test Data: Laptop
•	Steps:
1.	Add a laptop to the cart.
2.	Refresh the browser page.
3.	Open the cart.
•	Expected Result: The cart should retain the product if the website's requirements specify cart persistence.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CART-014: Verify cart after logout and login
•	Test Data: Laptop
•	Steps:
1.	Log in to the website.
2.	Add a laptop to the cart.
3.	Log out.
4.	Log in again using the same account.
5.	Open the cart.
•	Expected Result: Cart contents should behave according to the website's account and session persistence requirements.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CART-015: Add an out-of-stock product to the cart
•	Test Data: An out-of-stock product.
•	Steps:
1.	Open the product page for an out-of-stock item.
2.	Try to add it to the cart.
•	Expected Result: The system should prevent the purchase of unavailable stock and display an appropriate message.
•	Actual Result: Not Executed
•	Status: Not Executed
________________________________________
Test Summary
•	Total Test Cases: 15
•	Executed: 0
•	Passed: 0
•	Failed: 0
•	Not Executed: 15

