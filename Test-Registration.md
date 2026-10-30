E-commerce Application — Registration Test Cases
Project Overview
•	Project: E-commerce Application
•	Module: User Registration
•	Testing Type: Manual Testing
•	Prepared by: Aswani Nandan
•	Total Test Cases: 15
________________________________________


TC-REG-001: Register with Valid Details
•	Objective: Verify that a new user can successfully register using valid information.
•	Precondition: The registration page is accessible, and the email address is not already registered.
•	Test Data:
o	Name: Aswani Nandan
o	Email: aswani.qa.test@example.com
o	Password: Test@1234
o	Confirm Password: Test@1234
•	Steps:
1.	Open the registration page.
2.	Enter a valid full name.
3.	Enter a unique email address.
4.	Enter a valid password.
5.	Enter the same password in the Confirm Password field.
6.	Accept the terms and conditions if required.
7.	Click the Register button.
•	Expected Result: The account should be created successfully, and an appropriate confirmation message or next step should be displayed.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-REG-002: Register with an Already Registered Email Address
•	Objective: Verify that the application prevents registration using an email address that already exists.
•	Precondition: An account already exists with the test email address.
•	Test Data: Existing registered email address.
•	Steps:
1.	Open the registration page.
2.	Enter a valid name.
3.	Enter an already registered email address.
4.	Enter a valid password.
5.	Confirm the password.
6.	Click Register.
•	Expected Result: Registration should be rejected, and an appropriate message should inform the user that the email address is already registered.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-REG-003: Register with an Invalid Email Format
•	Objective: Verify that the application validates an incorrectly formatted email address.
•	Precondition: The registration page is open.
•	Test Data: aswani.qa.test@com
•	Steps:
1.	Open the registration page.
2.	Enter a valid name.
3.	Enter the invalid email address.
4.	Enter a valid password.
5.	Confirm the password.
6.	Click Register.
•	Expected Result: Registration should not proceed, and an appropriate email validation message should be displayed.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-REG-004: Submit Registration with All Fields Empty
•	Objective: Verify that the application validates all mandatory fields when the registration form is submitted empty.
•	Precondition: The registration page is open.
•	Test Data: All fields empty.
•	Steps:
1.	Open the registration page.
2.	Leave all mandatory fields empty.
3.	Click Register.
•	Expected Result: Registration should not proceed. Required-field validation messages should be displayed.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-REG-005: Submit Registration with Name Field Empty
•	Objective: Verify that the application validates an empty name field.
•	Precondition: The registration page is open.
•	Test Data: Name: Empty; all other fields: Valid.
•	Steps:
1.	Open the registration page.
2.	Leave the name field empty.
3.	Enter a valid email address.
4.	Enter a valid password.
5.	Confirm the password.
6.	Click Register.
•	Expected Result: Registration should be rejected, and a required-name validation message should appear.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-REG-006: Submit Registration with Email Field Empty
•	Objective: Verify that the application validates an empty email field.
•	Precondition: The registration page is open.
•	Test Data: Email: Empty; all other fields: Valid.
•	Steps:
1.	Open the registration page.
2.	Enter a valid name.
3.	Leave the email field empty.
4.	Enter a valid password.
5.	Confirm the password.
6.	Click Register.
•	Expected Result: Registration should be rejected, and an appropriate required-email message should appear.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-REG-007: Submit Registration with Password Field Empty
•	Objective: Verify that the application validates an empty password field.
•	Precondition: The registration page is open.
•	Test Data: Password: Empty; all other fields: Valid.
•	Steps:
1.	Open the registration page.
2.	Enter a valid name and email address.
3.	Leave the password field empty.
4.	Enter a value in Confirm Password if available.
5.	Click Register.
•	Expected Result: Registration should not proceed, and a required-password validation message should be displayed.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-REG-008: Verify Confirm Password Mismatch
•	Objective: Verify that the application prevents registration when the password and confirmation password do not match.
•	Precondition: The registration page is open.
•	Test Data:
o	Password: Test@1234
o	Confirm Password: Test@5678
•	Steps:
1.	Open the registration page.
2.	Enter a valid name.
3.	Enter a unique email address.
4.	Enter Test@1234 in the password field.
5.	Enter Test@5678 in the Confirm Password field.
6.	Click Register.
•	Expected Result: Registration should be rejected, and a password mismatch validation message should be displayed.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-REG-009: Verify Password Minimum Length
•	Objective: Verify that the application enforces the minimum password length specified in its requirements.
•	Precondition: The registration page is open, and the minimum password length is documented.
•	Test Data: A password containing fewer characters than the specified minimum.
•	Steps:
1.	Open the registration page.
2.	Enter valid name and email details.
3.	Enter a password shorter than the required minimum.
4.	Confirm the same password.
5.	Click Register.
•	Expected Result: Registration should be rejected, and an appropriate password-length validation message should appear.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-REG-010: Verify Password Maximum Length
•	Objective: Verify that the application handles passwords exceeding the maximum permitted length.
•	Precondition: The registration page is open, and the maximum password length is documented.
•	Test Data: A password exceeding the specified maximum length.
•	Steps:
1.	Open the registration page.
2.	Enter valid name and email details.
3.	Enter a password exceeding the maximum permitted length.
4.	Confirm the password if accepted by the field.
5.	Click Register.
•	Expected Result: The application should enforce its documented maximum password length and provide appropriate validation.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-REG-011: Verify Password Complexity Requirements
•	Objective: Verify that the application enforces its documented password complexity rules.
•	Precondition: Password complexity requirements are available.
•	Test Data: A password that does not satisfy one or more required complexity rules.
•	Steps:
1.	Open the registration page.
2.	Enter valid name and email details.
3.	Enter a password that does not meet the documented complexity requirements.
4.	Confirm the password.
5.	Click Register.
•	Expected Result: Registration should be rejected with an appropriate password complexity message.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-REG-012: Verify Special Characters in Name Field
•	Objective: Verify that the application handles special characters in the name field according to its input validation rules.
•	Precondition: The registration page is open.
•	Test Data: Name: Aswani@123
•	Steps:
1.	Open the registration page.
2.	Enter Aswani@123 in the name field.
3.	Enter valid email and password details.
4.	Click Register.
•	Expected Result: The application should accept or reject the name according to its documented name-field rules and display appropriate feedback.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-REG-013: Verify Terms and Conditions Validation
•	Objective: Verify that the application checks whether the user has accepted the terms and conditions when acceptance is mandatory.
•	Precondition: The registration form contains a mandatory terms and conditions checkbox.
•	Test Data: Valid registration details with the checkbox unchecked.
•	Steps:
1.	Open the registration page.
2.	Enter valid registration details.
3.	Leave the terms and conditions checkbox unchecked.
4.	Click Register.
•	Expected Result: Registration should not proceed, and an appropriate validation message should be displayed.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-REG-014: Verify Email Verification Process
•	Objective: Verify that the application sends an email verification request after registration when email verification is required.
•	Precondition: A unique email address is available, and email verification is enabled.
•	Test Data: Valid registration details with an accessible test email account.
•	Steps:
1.	Open the registration page.
2.	Enter valid registration details.
3.	Submit the registration form.
4.	Open the test email inbox.
5.	Check whether a verification email is received.
6.	Follow the verification link if available.
•	Expected Result: The verification email should be received, and the account should be verified according to the application's defined process.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-REG-015: Verify Registration Confirmation Message
•	Objective: Verify that the application displays an appropriate confirmation after successful registration.
•	Precondition: The registration page is open, and a unique email address is available.
•	Test Data: Valid registration details.
•	Steps:
1.	Open the registration page.
2.	Enter all required registration details correctly.
3.	Accept the terms and conditions if required.
4.	Click Register.
5.	Observe the confirmation message or next screen.
•	Expected Result: The application should display a clear registration success message or direct the user to the next required step, such as email verification.
•	Actual Result: Not Executed.
•	Status: Not Executed.
________________________________________
Execution Note
All test cases are currently marked Not Executed. Actual results and final statuses must be recorded only after executing them against a suitable test application.
Some scenarios depend on application requirements, such as password length, password complexity, terms acceptance, and email verification. Confirm those requirements before execution.

