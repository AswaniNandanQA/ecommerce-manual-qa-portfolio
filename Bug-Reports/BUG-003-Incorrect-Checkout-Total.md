BUG-003: Incorrect Total Amount During Checkout
Bug ID
BUG-003

Bug Title
Incorrect total amount displayed on the checkout page.

Module
Checkout / Order Summary

Environment
•	Application: E-commerce Website
•	Browser: Google Chrome
•	Operating System: Windows
•	Test Type: Manual Testing

Severity
Major

Priority
High

Preconditions
1.	The e-commerce website is accessible.
2.	The user has added a product to the shopping cart.
3.	The user can access the checkout page.
4.	The product price and shipping charges are known.
   
Test Steps
1.	Open the e-commerce website.
2.	Select a product priced at ₹1,000.
3.	Add two units of the product to the shopping cart.
4.	Proceed to checkout.
5.	Select a shipping method costing ₹100.
6.	Review the final order amount.
   
Test Data
•	Product: Laptop
•	Unit Price: ₹1,000
•	Quantity: 2
•	Subtotal: ₹2,000
•	Shipping Charge: ₹100
•	Expected Total: ₹2,100 (before taxes and discounts)

Expected Result
The checkout page should calculate and display the correct total amount of ₹2,100 before any applicable taxes or discounts.

Actual Result
The checkout page displays an incorrect total amount instead of ₹2,100.

Reproducibility
To be confirmed through repeated testing.

Status
Open (Sample)

Attachments
Screenshot or screen recording: To be added when the issue is reproduced.

Additional Notes
This is a sample portfolio bug report. The actual incorrect amount must be recorded after reproducing the defect. Severity, priority, reproducibility, and status must be confirmed through testing before reporting it as a real defect.

