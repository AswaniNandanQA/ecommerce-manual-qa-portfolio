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


TC-CHECKOUT-004: Verify mandatory shipping fields
•	Test Data: Leave required address fields empty.
•	Steps:
1.	Open the checkout page.
2.	Leave mandatory shipping fields empty.
3.	Click Continue.
•	Expected Result: Appropriate validation messages should appear for mandatory fields.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CHECKOUT-005: Verify invalid PIN code
•	Test Data: ABCDE
•	Steps:
1.	Open the shipping address form.
2.	Enter an invalid PIN code.
3.	Complete the other required fields.
4.	Click Continue.
•	Expected Result: The system should reject the invalid PIN code and display a suitable validation message.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CHECKOUT-006: Verify mobile number validation
•	Test Data: Invalid mobile number such as 123
•	Steps:
1.	Open the shipping address form.
2.	Enter an invalid mobile number.
3.	Complete the other required fields.
4.	Click Continue.
•	Expected Result: The system should display an appropriate mobile number validation message.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CHECKOUT-007: Verify selection of a saved address
•	Test Data: An existing saved shipping address.
•	Steps:
1.	Log in to the website.
2.	Add a product to the cart.
3.	Proceed to checkout.
4.	Select an existing saved address.
•	Expected Result: The selected saved address should be applied to the order.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CHECKOUT-008: Verify adding a new shipping address
•	Test Data: A valid new shipping address.
•	Steps:
1.	Proceed to checkout.
2.	Select Add New Address.
3.	Enter valid address details.
4.	Save the address.
•	Expected Result: The new address should be saved and selected for checkout, if supported.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CHECKOUT-009: Verify available shipping methods
•	Test Data: A valid shipping address.
•	Steps:
1.	Proceed to checkout.
2.	Enter a valid shipping address.
3.	Review the available shipping methods.
4.	Select a shipping method.
•	Expected Result: Available shipping methods should be displayed, and the selected method should be applied correctly.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CHECKOUT-010: Verify order summary
•	Test Data: Laptop, quantity 2
•	Steps:
1.	Add two laptops to the cart.
2.	Proceed to checkout.
3.	Review the order summary.
•	Expected Result: Product name, quantity, price, subtotal, shipping charges, taxes, and discounts should be displayed accurately where applicable.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CHECKOUT-011: Verify total amount calculation
•	Test Data: Product price ₹1,000, quantity 2, shipping ₹100
•	Steps:
1.	Add two products priced at ₹1,000 each.
2.	Proceed to checkout.
3.	Select shipping costing ₹100.
4.	Review the final total before payment.
•	Expected Result: The total should be ₹2,100 before any applicable taxes or discounts.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CHECKOUT-012: Verify payment method selection
•	Test Data: Available payment options.
•	Steps:
1.	Proceed to the payment section.
2.	Review the available payment methods.
3.	Select one available payment method.
•	Expected Result: The selected payment method should be accepted and displayed correctly.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CHECKOUT-013: Verify payment failure handling
•	Test Data: A payment gateway's approved test failure scenario.
•	Steps:
1.	Proceed to the payment section.
2.	Use the payment gateway's documented test scenario for a failed transaction.
3.	Submit the payment.
•	Expected Result: The system should display an appropriate failure message and should not create a falsely confirmed paid order.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CHECKOUT-014: Verify successful order placement
•	Test Data: Valid shipping details and an approved payment gateway test scenario.
•	Steps:
1.	Add a product to the cart.
2.	Complete the shipping details.
3.	Select a payment method.
4.	Complete the approved test payment.
5.	Place the order.
•	Expected Result: The order should be placed successfully and a confirmation message with an order reference should be displayed.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-CHECKOUT-015: Verify order confirmation details
•	Test Data: A successfully placed test order.
•	Steps:
1.	Complete a successful test checkout.
2.	Open the order confirmation page.
3.	Review the order details.
•	Expected Result: The confirmation should display the correct order reference, products, quantities, delivery address, and final amount.
•	Actual Result: Not Executed
•	Status: Not Executed
________________________________________
Test Summary
•	Total Test Cases: 15
•	Executed: 0
•	Passed: 0
•	Failed: 0
•	Not Executed: 15

