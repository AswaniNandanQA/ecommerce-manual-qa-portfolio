SauceDemo – Shopping Cart Test Cases
1. Project Overview
•	Project: SauceDemo
•	Application URL: https://www.saucedemo.com/
•	Testing Type: Manual Testing
•	Module: Shopping Cart
•	Prepared By: Aswani Nandan
•	Total Test Cases: 15
•	Execution Status: Not Executed
•	Test Environment: SauceDemo practice application
•	Test Account: standard_user
2. Execution Note
These test cases are designed for the SauceDemo shopping cart module. All test cases will be executed manually, and actual results will be documented after observing the application's behaviour.

3.Cart Test Cases

| Test Case ID | Test Scenario | Expected Result |
|---|---|---|
| TC-CART-001 | Add a single product to cart | Product should be added successfully. |
| TC-CART-002 | Add multiple products to cart | All selected products should be added successfully. |
| TC-CART-003 | Verify cart badge count after adding one product | Cart badge should display 1. |
| TC-CART-004 | Verify cart badge count after adding multiple products | Cart badge should display the correct number of products. |
| TC-CART-005 | Verify Add to Cart button changes to Remove | Button should change to Remove after adding the product. |
| TC-CART-006 | Remove product from Products page | Selected product should be removed from the cart. |
| TC-CART-007 | Open shopping cart | Shopping cart page should open successfully. |
| TC-CART-008 | Verify product details in cart | Correct product name and description should be displayed. |
| TC-CART-009 | Verify product price in cart | Product price should match the price on the Products page. |
| TC-CART-010 | Remove product from shopping cart page | Selected product should be removed successfully. |
| TC-CART-011 | Remove one product from multiple products | Only the selected product should be removed; other products should remain. |
| TC-CART-012 | Remove all products from cart | Shopping cart should become empty. |
| TC-CART-013 | Continue shopping from cart | User should return to the Products page. |
| TC-CART-014 | Verify cart contents after page refresh | Cart contents should behave according to the application's intended session behaviour. |
| TC-CART-015 | Verify cart contents after logout and login | Cart contents should behave according to the application's intended session behaviour. |

4. Detailed Test Cases
   
TC-CART-001: Add a Single Product to Cart
Test Objective: To verify that a user can successfully add a single product to the shopping cart.
Preconditions:
1.	SauceDemo application is accessible.
2.	User is logged in with valid credentials.
3.	Products page is displayed.
Test Data:
•	Username: standard_user
•	Password: secret_sauce
•	Product: Sauce Labs Backpack
Test Steps:
1.	Open https://www.saucedemo.com/.
2.	Enter valid username and password.
3.	Click Login.
4.	Locate Sauce Labs Backpack.
5.	Click Add to Cart.
6.	Check the cart badge.
Expected Result:
1.	The selected product should be added successfully.
2.	Cart badge should display 1.
3.	Add to Cart button should change to Remove.
Actual Result: To be recorded after execution.
Status: Not Executed
Defect ID: N/A
________________________________________
TC-CART-002: Add Multiple Products to Cart
Test Objective: To verify that a user can add multiple different products to the shopping cart.
Preconditions:
1.	User is logged in.
2.	Products page is displayed.
3.	Cart is initially empty.
Test Data:
•	Sauce Labs Backpack
•	Sauce Labs Bike Light
•	Sauce Labs Bolt T-Shirt
Test Steps:
1.	Locate Sauce Labs Backpack and click Add to Cart.
2.	Locate Sauce Labs Bike Light and click Add to Cart.
3.	Locate Sauce Labs Bolt T-Shirt and click Add to Cart.
4.	Check the cart badge.
Expected Result:
1.	All three products should be added successfully.
2.	Cart badge should display 3.
Actual Result: To be recorded after execution.
Status: Not Executed
Defect ID: N/A
________________________________________
TC-CART-003: Verify Cart Badge Count After Adding One Product
Test Objective: To verify that the cart badge displays the correct item count after adding a product.
Preconditions:
1.	User is logged in.
2.	Products page is displayed.
3.	Cart is initially empty.
Test Data:
•	Product: Sauce Labs Backpack
Test Steps:
1.	Click Add to Cart for Sauce Labs Backpack.
2.	Observe the shopping cart icon.
3.	Check the displayed badge count.
Expected Result:
The cart badge should display 1.
Actual Result: To be recorded after execution.
Status: Not Executed
Defect ID: N/A
________________________________________
TC-CART-004: Verify Cart Badge Count After Adding Multiple Products
Test Objective: To verify that the cart badge updates correctly when multiple products are added.
Preconditions:
1.	User is logged in.
2.	Products page is displayed.
3.	Cart is initially empty.
Test Data:
•	Sauce Labs Backpack
•	Sauce Labs Bike Light
•	Sauce Labs Bolt T-Shirt
Test Steps:
1.	Add Sauce Labs Backpack to the cart.
2.	Add Sauce Labs Bike Light to the cart.
3.	Add Sauce Labs Bolt T-Shirt to the cart.
4.	Observe the cart badge.
Expected Result:
The cart badge should display 3.
Actual Result: To be recorded after execution.
Status: Not Executed
Defect ID: N/A
________________________________________
TC-CART-005: Verify Add to Cart Button Changes to Remove
Test Objective: To verify that the product button changes after adding a product to the cart.
Preconditions:
1.	User is logged in.
2.	Products page is displayed.
3.	Selected product is not already in the cart.
Test Data:
•	Product: Sauce Labs Backpack
Test Steps:
1.	Locate Sauce Labs Backpack.
2.	Observe the Add to Cart button.
3.	Click Add to Cart.
4.	Observe the button again.
Expected Result:
The button should change from Add to Cart to Remove.
Actual Result: To be recorded after execution.
Status: Not Executed
Defect ID: N/A
________________________________________
TC-CART-006: Remove Product From Products Page
Test Objective: To verify that a user can remove an added product directly from the Products page.
Preconditions:
1.	User is logged in.
2.	Products page is displayed.
3.	A product has been added to the cart.
Test Data:
•	Product: Sauce Labs Backpack
Test Steps:
1.	Locate Sauce Labs Backpack.
2.	Click Remove.
3.	Observe the cart badge.
4.	Open the shopping cart and verify the product.
Expected Result:
1.	The product should be removed from the cart.
2.	Cart badge should disappear if the cart is empty.
3.	The product should no longer appear in the cart.
Actual Result: To be recorded after execution.
Status: Not Executed
Defect ID: N/A
________________________________________
TC-CART-007: Open Shopping Cart
Test Objective: To verify that a user can access the shopping cart page.
Preconditions:
1.	User is logged in.
2.	Products page is displayed.
3.	At least one product has been added.
Test Data:
•	Product: Sauce Labs Backpack
Test Steps:
1.	Add Sauce Labs Backpack to the cart.
2.	Click the shopping cart icon.
Expected Result:
The shopping cart page should open successfully and display the added product.
Actual Result: To be recorded after execution.
Status: Not Executed
Defect ID: N/A
________________________________________
TC-CART-008: Verify Product Details in Cart
Test Objective: To verify that the correct product details are displayed in the shopping cart.
Preconditions:
1.	User is logged in.
2.	At least one product has been added to the cart.
3.	Shopping cart page is opened.
Test Data:
•	Product: Sauce Labs Backpack
Test Steps:
1.	Add Sauce Labs Backpack to the cart.
2.	Open the shopping cart.
3.	Observe the product name and description.
Expected Result:
The cart should display the correct product name and description.
Actual Result: To be recorded after execution.
Status: Not Executed
Defect ID: N/A
________________________________________
TC-CART-009: Verify Product Price in Cart
Test Objective: To verify that the product price displayed in the cart matches the price displayed on the Products page.
Preconditions:
1.	User is logged in.
2.	Products page is displayed.
Test Data:
•	Product: Sauce Labs Backpack
Test Steps:
1.	Observe the price of Sauce Labs Backpack on the Products page.
2.	Add the product to the cart.
3.	Open the shopping cart.
4.	Compare the displayed prices.
Expected Result:
The product price should be consistent on both pages.
Actual Result: To be recorded after execution.
Status: Not Executed
Defect ID: N/A
________________________________________
TC-CART-010: Remove Product From Shopping Cart Page
Test Objective: To verify that a user can remove a product directly from the shopping cart page.
Preconditions:
1.	User is logged in.
2.	At least one product has been added to the cart.
3.	Shopping cart page is opened.
Test Data:
•	Product: Sauce Labs Backpack
Test Steps:
1.	Add Sauce Labs Backpack to the cart.
2.	Open the shopping cart.
3.	Click Remove for the selected product.
4.	Observe the cart contents.
Expected Result:
The selected product should be removed successfully from the shopping cart.
Actual Result: To be recorded after execution.
Status: Not Executed
Defect ID: N/A
________________________________________
TC-CART-011: Remove One Product From Multiple Products
Test Objective: To verify that removing one product does not remove other products from the cart.
Preconditions:
1.	User is logged in.
2.	Multiple products have been added to the cart.
3.	Shopping cart page is opened.
Test Data:
•	Sauce Labs Backpack
•	Sauce Labs Bike Light
•	Sauce Labs Bolt T-Shirt
Test Steps:
1.	Add all three products to the cart.
2.	Open the shopping cart.
3.	Click Remove for Sauce Labs Bike Light.
4.	Observe the remaining products.
Expected Result:
1.	Sauce Labs Bike Light should be removed.
2.	Sauce Labs Backpack and Sauce Labs Bolt T-Shirt should remain in the cart.
3.	Cart badge should display 2.
Actual Result: To be recorded after execution.
Status: Not Executed
Defect ID: N/A
________________________________________
TC-CART-012: Remove All Products From Cart
Test Objective: To verify that a user can remove all products from the shopping cart.
Preconditions:
1.	User is logged in.
2.	Multiple products have been added to the cart.
3.	Shopping cart page is opened.
Test Data:
•	Sauce Labs Backpack
•	Sauce Labs Bike Light
Test Steps:
1.	Add both products to the cart.
2.	Open the shopping cart.
3.	Click Remove for Sauce Labs Backpack.
4.	Click Remove for Sauce Labs Bike Light.
5.	Observe the shopping cart.
Expected Result:
1.	All products should be removed.
2.	No products should be displayed in the cart.
3.	Cart badge should disappear.
Actual Result: To be recorded after execution.
Status: Not Executed
Defect ID: N/A
________________________________________
TC-CART-013: Continue Shopping From Cart
Test Objective: To verify that a user can return to the Products page from the shopping cart.
Preconditions:
1.	User is logged in.
2.	Shopping cart page is opened.
Test Data:
•	Existing cart item: Sauce Labs Backpack
Test Steps:
1.	Open the shopping cart.
2.	Click Continue Shopping.
3.	Observe the displayed page.
Expected Result:
The user should be redirected to the Products page.
Actual Result: To be recorded after execution.
Status: Not Executed
Defect ID: N/A
________________________________________
TC-CART-014: Verify Cart Contents After Page Refresh
Test Objective: To observe whether cart contents remain available after refreshing the browser page.
Preconditions:
1.	User is logged in.
2.	At least one product has been added to the cart.
3.	Shopping cart page is opened.
Test Data:
•	Product: Sauce Labs Backpack
Test Steps:
1.	Add Sauce Labs Backpack to the cart.
2.	Open the shopping cart.
3.	Refresh the browser page.
4.	Observe the shopping cart contents.
Expected Result:
Cart contents should behave consistently with the application's intended session behaviour. Record the actual observed behaviour.
Actual Result: To be recorded after execution.
Status: Not Executed
Defect ID: N/A
________________________________________
TC-CART-015: Verify Cart Contents After Logout and Login
Test Objective: To observe whether cart contents remain available after the user logs out and logs in again.
Preconditions:
1.	User is logged in with valid credentials.
2.	At least one product has been added to the cart.
Test Data:
•	Username: standard_user
•	Password: secret_sauce
•	Product: Sauce Labs Backpack
Test Steps:
1.	Add Sauce Labs Backpack to the cart.
2.	Log out of the application.
3.	Log in again using the same credentials.
4.	Open the shopping cart.
5.	Observe whether the product is displayed.
Expected Result:
Record whether the product remains in the cart after logging in again. Compare the observed behaviour with the application's intended session behaviour.
Actual Result: To be recorded after execution.
Status: Not Executed
Defect ID: N/A

