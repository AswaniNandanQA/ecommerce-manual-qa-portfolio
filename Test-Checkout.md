E-commerce Checkout – Test Cases
Module: Checkout
Test Objective: To verify that customers can complete the checkout process correctly and securely.
Preconditions:
•	The e-commerce website is accessible.
•	The user has an account and is logged in, if required.
•	At least one product is available and added to the cart.
________________________________________



| Test Case ID | Test Scenario | Expected Result |
|---|---|---|
| TC-CHECKOUT-001 | Proceed to checkout with a valid cart | Checkout: Your Information page should open successfully. |
| TC-CHECKOUT-002 | Verify checkout with an empty cart | Record whether checkout is allowed or prevented when the cart is empty. |
| TC-CHECKOUT-003 | Verify checkout with all information fields empty | Appropriate validation message should be displayed. |
| TC-CHECKOUT-004 | Verify checkout with First Name field empty | First Name required validation message should appear. |
| TC-CHECKOUT-005 | Verify checkout with Last Name field empty | Last Name required validation message should appear. |
| TC-CHECKOUT-006 | Verify checkout with Postal Code field empty | Postal Code required validation message should appear. |
| TC-CHECKOUT-007 | Verify checkout with valid customer information | User should proceed to the Checkout: Overview page. |
| TC-CHECKOUT-008 | Verify Cancel button on checkout information page | User should return to the shopping cart. |
| TC-CHECKOUT-009 | Verify product details on order overview page | Correct product name and description should be displayed. |
| TC-CHECKOUT-010 | Verify product price on order overview page | Product price should match the Products page. |
| TC-CHECKOUT-011 | Verify item quantity in order overview | Displayed quantity should match the quantity added to the cart. |
| TC-CHECKOUT-012 | Verify item subtotal calculation | Item subtotal should be calculated correctly. |
| TC-CHECKOUT-013 | Verify tax calculation | Tax amount should be calculated correctly. |
| TC-CHECKOUT-014 | Verify total amount calculation | Final total should equal item subtotal plus tax. |
| TC-CHECKOUT-015 | Verify successful order placement | Order confirmation message should be displayed after clicking Finish. |


TC-CHECKOUT-001: Proceed to checkout with a valid cart
•	Test Data: Sauce Labs Backpack
• Preconditions: User is logged in with standard_user.
•	Steps:
1.	Add Sauce Labs Backpack to the cart.
2.	Open the shopping cart.
3.	Click Proceed to Checkout.
•	Expected Result: The user should be redirected to the Checkout: Your Information page.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CHECKOUT-002: Verify checkout with an empty cart
•	Test Data: Empty cart
•	Steps:
1.	Open the shopping cart without adding any products.
2.	Try to proceed to checkout.
•	Expected Result: The application should respond appropriately when checkout is attempted with an empty cart. Record the actual behaviour.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CHECKOUT-003: Verify checkout with all information fields empty
•	Test Data: First Name, Last Name and Postal Code left empty.
•	Steps:
  1. Open the Checkout: Your Information page.
  2. Leave all three fields empty.
  3. Click Continue.
•	Expected Result: The application should prevent checkout and display a required-field validation message.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CHECKOUT-004:  Verify checkout with First Name field empty
•	Test Data: 
  - First Name: Empty
  - Last Name: Nandan
  - Postal Code: 689691
•	Steps:
  1. Open the Checkout: Your Information page.
  2. Leave the First Name field empty.
  3. Enter Nandan in the Last Name field.
  4. Enter 689691 in the Postal Code field.
  5. Click Continue.
•	Expected Result: The application should display "Error: First Name is required" and prevent the user from proceeding.
•	Actual Result: Not Executed
•	Status: Not Executed



### TC-CHECKOUT-005: Verify checkout with Last Name field empty

- Test Data:
  - First Name: Aswani
  - Last Name: Empty
  - Postal Code: 689691

- Steps:
  1. Open the Checkout: Your Information page.
  2. Enter Aswani in First Name.
  3. Leave Last Name empty.
  4. Enter 689691 in Postal Code.
  5. Click Continue.

- Expected Result: Error: Last Name is required. User should be prevented from proceeding.
- Actual Result: Not Executed
- Status: Not Executed


### TC-CHECKOUT-006: Verify checkout with Postal Code field empty

- Test Data:
  - First Name: Aswani
  - Last Name: Nandan
  - Postal Code: Empty

- Steps:
  1. Open the Checkout: Your Information page.
  2. Enter Aswani in First Name.
  3. Enter Nandan in Last Name.
  4. Leave Postal Code empty.
  5. Click Continue.

- Expected Result: Error: Postal Code is required. User should be prevented from proceeding.
- Actual Result: Not Executed
- Status: Not Executed


### TC-CHECKOUT-007: Verify checkout with valid customer information

- Test Data:
  - First Name: Aswani
  - Last Name: Nandan
  - Postal Code: 689691

- Steps:
  1. Add Sauce Labs Backpack to the cart.
  2. Open the shopping cart.
  3. Click Checkout.
  4. Enter valid First Name, Last Name and Postal Code.
  5. Click Continue.

- Expected Result: User should be redirected to the Checkout: Overview page.
- Actual Result: Not Executed
- Status: Not Executed


### TC-CHECKOUT-008: Verify Cancel button on checkout information page

- Test Data: Sauce Labs Backpack

- Steps:
  1. Add Sauce Labs Backpack to the cart.
  2. Open the shopping cart.
  3. Click Checkout.
  4. Click Cancel on the Checkout: Your Information page.

- Expected Result: User should return to the shopping cart.
- Actual Result: Not Executed
- Status: Not Executed


### TC-CHECKOUT-009: Verify product details on order overview page

- Test Data: Sauce Labs Backpack

- Steps:
  1. Add Sauce Labs Backpack to the cart.
  2. Proceed to checkout.
  3. Enter valid customer information.
  4. Click Continue.
  5. Review the product details on the Checkout: Overview page.

- Expected Result: Correct product name and description should be displayed.
- Actual Result: Not Executed
- Status: Not Executed


### TC-CHECKOUT-010: Verify product price on order overview page

- Test Data: Sauce Labs Backpack

- Steps:
  1. Note the product price on the Products page.
  2. Add Sauce Labs Backpack to the cart.
  3. Proceed to checkout.
  4. Enter valid customer information.
  5. Click Continue.
  6. Compare the price on the Checkout: Overview page.

- Expected Result: Product price should match the price displayed on the Products page.
- Actual Result: Not Executed
- Status: Not Executed


### TC-CHECKOUT-011: Verify item quantity in order overview

- Test Data: Sauce Labs Backpack

- Steps:
  1. Add Sauce Labs Backpack to the cart.
  2. Proceed to checkout.
  3. Enter valid customer information.
  4. Click Continue.
  5. Check the displayed item quantity.

- Expected Result: Displayed quantity should match the quantity added to the cart.
- Actual Result: Not Executed
- Status: Not Executed

### TC-CHECKOUT-012: Verify item subtotal calculation

- Test Data: Sauce Labs Backpack

- Steps:
  1. Note the price of Sauce Labs Backpack.
  2. Add the product to the cart.
  3. Proceed to checkout.
  4. Enter valid customer information.
  5. Click Continue.
  6. Check the Item total displayed on the overview page.

- Expected Result: Item total should equal the sum of the prices of all products in the cart.
- Actual Result: Not Executed
- Status: Not Executed

### TC-CHECKOUT-013: Verify tax calculation

- Test Data: Sauce Labs Backpack

- Steps:
  1. Add Sauce Labs Backpack to the cart.
  2. Proceed to checkout.
  3. Enter valid customer information.
  4. Click Continue.
  5. Check the displayed tax amount.
  6. Compare it with the applicable tax calculation.

- Expected Result: Tax amount should be calculated correctly based on the displayed item subtotal and applicable tax rate.
- Actual Result: Not Executed
- Status: Not Executed


### TC-CHECKOUT-014: Verify total amount calculation

- Test Data: Sauce Labs Backpack

- Steps:
  1. Add Sauce Labs Backpack to the cart.
  2. Proceed to checkout.
  3. Enter valid customer information.
  4. Click Continue.
  5. Note the Item total and Tax amount.
  6. Verify the final Total amount.

- Expected Result: Final total should equal Item total plus Tax.
- Actual Result: Not Executed
- Status: Not Executed

### TC-CHECKOUT-015: Verify successful order placement

- Test Data: Sauce Labs Backpack

- Steps:
  1. Add Sauce Labs Backpack to the cart.
  2. Open the shopping cart.
  3. Click Checkout.
  4. Enter valid First Name, Last Name and Postal Code.
  5. Click Continue.
  6. Review the order overview.
  7. Click Finish.
  8. Review the order confirmation page.

- Expected Result: Order should be placed successfully and the Checkout: Complete! confirmation message should be displayed.
- Actual Result: Not Executed
- Status: Not Executed
________________________________________
Test Summary
•	Total Test Cases: 15
•	Executed: 0
•	Passed: 0
•	Failed: 0
•	Not Executed: 15

