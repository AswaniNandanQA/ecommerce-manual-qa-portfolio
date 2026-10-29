E-commerce Application — Test Cases
Project Overview
Project: E-commerce Application
Testing Type: Manual Testing
Module: Login
Prepared by: Aswani Nandan


TC-LOGIN-001: Login with Valid Credentials
•	Objective: Verify that a registered user can log in successfully.
•	Precondition: The user has an active account.
•	Test Data: Valid registered username and password.
•	Steps:
1.	Open the application login page.
2.	Enter a valid registered username.
3.	Enter the correct password.
4.	Click the Login button.
•	Expected Result: The user should log in successfully and see the home page or dashboard.
•	Actual Result: To be recorded during test execution.
•	Status: Not Executed


TC-LOGIN-002: Login with an Incorrect Password
•	Objective: Verify that login is rejected when the password is incorrect.
•	Precondition: The user has an active account.
•	Test Data: Valid username and incorrect password.
•	Steps:
1.	Open the login page.
2.	Enter a valid registered username.
3.	Enter an incorrect password.
4.	Click the Login button.
•	Expected Result: Login should be rejected and an appropriate error message should appear.
•	Actual Result: To be recorded during test execution.
•	Status: Not Executed


TC-LOGIN-003: Login with Empty Fields
•	Objective: Verify validation when the username and password are empty.
•	Precondition: The login page is open.
•	Test Data: Empty username and password.
•	Steps:
1.	Leave the username field empty.
2.	Leave the password field empty.
3.	Click the Login button.
•	Expected Result: Login should not proceed; required-field validation should be displayed.
•	Actual Result: To be recorded during test execution.
•	Status: Not Executed
•	Status: Not Executed.


TC-LOGIN-004: Login with Both Username and Password Incorrect
•	Objective: Verify that a user cannot log in using an unregistered username and an incorrect password.
•	Precondition: The login page is open.
•	Test Data: Unregistered username and incorrect password.
•	Steps:
1.	Open the login page.
2.	Enter an unregistered username.
3.	Enter an incorrect password.
4.	Click the Login button.
•	Expected Result: Login should be rejected, and an appropriate error message should be displayed.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-LOGIN-005: Submit Login Form with Both Fields Empty
•	Objective: Verify that the application validates empty username and password fields.
•	Precondition: The login page is open.
•	Test Data: Username: Empty; Password: Empty.
•	Steps:
1.	Open the login page.
2.	Leave the username field empty.
3.	Leave the password field empty.
4.	Click the Login button.
•	Expected Result: Login should not proceed. Appropriate required-field validation messages should be displayed.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-LOGIN-006: Submit Login Form with Username Empty
•	Objective: Verify that the application validates an empty username.
•	Precondition: The login page is open.
•	Test Data: Username: Empty; Password: Valid password.
•	Steps:
1.	Open the login page.
2.	Leave the username field empty.
3.	Enter a valid password for a registered account.
4.	Click the Login button.
•	Expected Result: Login should not proceed, and the username-required validation message should be displayed.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-LOGIN-007: Submit Login Form with Password Empty
•	Objective: Verify that the application validates an empty password.
•	Precondition: The login page is open.
•	Test Data: Username: Valid registered username; Password: Empty.
•	Steps:
1.	Open the login page.
2.	Enter a valid registered username.
3.	Leave the password field empty.
4.	Click the Login button.
•	Expected Result: Login should not proceed, and the password-required validation message should be displayed.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-LOGIN-008: Verify Password Case Sensitivity
•	Objective: Verify that the password is case-sensitive when the account uses a case-sensitive password.
•	Precondition: A registered account exists with a known password containing letters.
•	Test Data: Valid username and password entered with at least one letter's case changed.
•	Steps:
1.	Open the login page.
2.	Enter a valid registered username.
3.	Enter the correct password but change the case of at least one letter.
4.	Click the Login button.
•	Expected Result: Login should be rejected if the entered password differs from the registered password.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-LOGIN-009: Verify Leading and Trailing Spaces in Username
•	Objective: Verify how the application handles spaces before or after a username.
•	Precondition: A registered account exists.
•	Test Data: Valid username with leading and/or trailing spaces.
•	Steps:
1.	Open the login page.
2.	Enter the registered username with a leading space.
3.	Enter the correct password.
4.	Click the Login button and record the result.
5.	Repeat with a trailing space in the username.
•	Expected Result: The application should handle spaces according to its documented requirements. Record whether it trims spaces or rejects the input.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-LOGIN-010: Verify Leading and Trailing Spaces in Password
•	Objective: Verify that spaces in the password are handled according to the application's password rules.
•	Precondition: A registered account exists with a known password.
•	Test Data: Correct password with an additional leading or trailing space.
•	Steps:
1.	Open the login page.
2.	Enter the registered username.
3.	Enter the correct password with an additional leading space.
4.	Click the Login button and record the result.
5.	Repeat with an additional trailing space.
•	Expected Result: The application should follow its defined password-handling rules. Password spaces should not be silently removed unless that behaviour is explicitly specified.
•	Actual Result: Not Executed.
•	Status: Not Executed.

