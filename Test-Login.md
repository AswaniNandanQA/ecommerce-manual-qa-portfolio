SauceDemo – Login Module Test Cases
1. Project Overview
•	Project: SauceDemo
•	Application URL: https://www.saucedemo.com/
•	Testing Type: Manual Testing
•	Module: Login
•	Prepared By: Aswani Nandan
•	Test Environment: SauceDemo practice application

**3. Test Data**
| Test Case ID | Username | Password | Purpose | 
|---|---|---|---|---|
| TD-001 | standard_user	secret_sauce | Valid login |
TD-002	wrong_user	wrong_password123	Invalid credentials
TD-003	locked_out_user	secret_sauce	Locked-out account
TD-004	problem_user	secret_sauce	Check login and product page
TD-005	performance_glitch_user	secret_sauce	Check login with performance delay
TD-006	visual_user	secret_sauce	Check visual behaviour
TD-007	standard_user	wrong_password123	Valid username, invalid password
TD-008	wrong_user	secret_sauce	Invalid username, valid password
TD-009	STANDARD_USER	secret_sauce	Uppercase username
TD-010	standard_user	SECRET_SAUCE	Uppercase password
TD-011	standard_user	secret@#$123	Special-character password
Note: The invalid usernames and passwords above are test inputs, not valid SauceDemo accounts. SauceDemo's publicly provided demo credentials are used for the valid and special-account scenarios.
5. Login Test Cases
TC-LOGIN-001: Login with valid credentials
•	Test Data: TD-001
•	Steps:
1.	Open the SauceDemo application.
2.	Enter standard_user in the username field.
3.	Enter secret_sauce in the password field.
4.	Click the Login button.
•	Expected Result: User should successfully log in and navigate to the Products page.
•	Actual Result: Products page displayed successfully.
•	Status: Pass
TC-LOGIN-002: Login with valid username and invalid password
•	Test Data: TD-007
•	Steps:
1.	Enter standard_user.
2.	Enter wrong_password123.
3.	Click Login.
•	Expected Result: Login should be rejected with an appropriate error message.
•	Actual Result: Error displayed: Epic sadface: Username and password do not match any user in this service
•	Status: Pass
TC-LOGIN-003: Login with invalid username and valid password
•	Test Data: TD-008
•	Steps:
1.	Enter wrong_user.
2.	Enter secret_sauce.
3.	Click Login.
•	Expected Result: Login should be rejected with an appropriate error message.
•	Actual Result: Invalid credentials error displayed.
•	Status: Pass
TC-LOGIN-004: Login with invalid username and invalid password
•	Test Data: Invalid username and password.
•	Steps:
1.	Enter wrong_user.
2.	Enter wrong_password123.
3.	Click Login.
•	Expected Result: Login should be rejected.
•	Actual Result: Invalid credentials error displayed.
•	Status: Pass
TC-LOGIN-005: Login with both fields empty
•	Test Data: Empty username and password.
•	Steps:
1.	Leave the username field empty.
2.	Leave the password field empty.
3.	Click Login.
•	Expected Result: Application should display a required-field validation message.
•	Actual Result: Epic sadface: Username is required
•	Status: Pass
TC-LOGIN-006: Login with empty username and valid password
•	Test Data: Empty username, secret_sauce.
•	Steps:
1.	Leave the username field empty.
2.	Enter secret_sauce in the password field.
3.	Click Login.
•	Expected Result: Application should display a username-required message.
•	Actual Result: Epic sadface: Username is required
•	Status: Pass
TC-LOGIN-007: Login with valid username and empty password
•	Test Data: standard_user, empty password.
•	Steps:
1.	Enter standard_user.
2.	Leave the password field empty.
3.	Click Login.
•	Expected Result: Application should display a password-required message.
•	Actual Result: Epic sadface: Password is required
•	Status: Pass
TC-LOGIN-008: Login with invalid username and empty password
•	Test Data: wrong_user, empty password.
•	Steps:
1.	Enter wrong_user.
2.	Leave the password field empty.
3.	Click Login.
•	Expected Result: Application should display a password-required message.
•	Actual Result: Epic sadface: Password is required
•	Status: Pass
TC-LOGIN-009: Login using a locked-out account
•	Test Data: TD-003
•	Steps:
1.	Enter locked_out_user.
2.	Enter secret_sauce.
3.	Click Login.
•	Expected Result: Application should prevent login and display an appropriate locked-out message.
•	Actual Result: Epic sadface: Sorry, this user has been locked out.
•	Status: Pass
TC-LOGIN-010: Login using problem_user
•	Test Data: TD-004
•	Steps:
1.	Enter problem_user.
2.	Enter secret_sauce.
3.	Click Login.
4.	Observe the Products page.
•	Expected Result: User should successfully log in and access the Products page.
•	Actual Result: Login successful. Incorrect/repeated product images were observed on the Products page.
•	Status: Pass
•	Related Bug: BUG-004 – Incorrect Product Images
TC-LOGIN-011: Login using performance_glitch_user
•	Test Data: TD-005
•	Steps:
1.	Enter performance_glitch_user.
2.	Enter secret_sauce.
3.	Click Login.
4.	Observe the page loading behaviour.
•	Expected Result: User should successfully log in and access the Products page.
•	Actual Result: Products page opened with a noticeable delay.
•	Status: Pass
•	Observation: Performance delay noticed; no performance failure was confirmed.
TC-LOGIN-012: Login using visual_user
•	Test Data: TD-006
•	Steps:
1.	Enter visual_user.
2.	Enter secret_sauce.
3.	Click Login.
4.	Observe the Products page.
•	Expected Result: User should successfully log in and access the Products page.
•	Actual Result: Products page opened successfully. No unusual behaviour was observed during this test.
•	Status: Pass
TC-LOGIN-013: Login with leading and trailing spaces in username
•	Test Data: Username: standard_user; Password: secret_sauce.
•	Steps:
1.	Enter standard_user including spaces.
2.	Enter secret_sauce.
3.	Click Login.
•	Expected Result: Application should handle the input according to its username validation rules and reject invalid credentials if spaces are not accepted.
•	Actual Result: Invalid credentials error displayed.
•	Status: Pass
TC-LOGIN-014: Login with uppercase username
•	Test Data: TD-009
•	Steps:
1.	Enter STANDARD_USER.
2.	Enter secret_sauce.
3.	Click Login.
•	Expected Result: Application should reject the credentials if usernames are case-sensitive.
•	Actual Result: Invalid credentials error displayed.
•	Status: Pass
TC-LOGIN-015: Login with uppercase password
•	Test Data: TD-010
•	Steps:
1.	Enter standard_user.
2.	Enter SECRET_SAUCE.
3.	Click Login.
•	Expected Result: Application should reject the credentials because the password does not match the correct case.
•	Actual Result: Invalid credentials error displayed.
•	Status: Pass
TC-LOGIN-016: Login with a very long username
•	Test Data: Very long username; password: secret_sauce.
•	Steps:
1.	Enter a very long username.
2.	Enter secret_sauce.
3.	Click Login.
•	Expected Result: Application should handle the input without crashing and reject invalid credentials.
•	Actual Result: Invalid credentials error displayed.
•	Status: Pass
TC-LOGIN-017: Login with special characters in username
•	Test Data: Username: standard_user@#$%; password: secret_sauce.
•	Steps:
1.	Enter standard_user@#$%.
2.	Enter secret_sauce.
3.	Click Login.
•	Expected Result: Application should reject invalid credentials.
•	Actual Result: Invalid credentials error displayed.
•	Status: Pass
TC-LOGIN-018: Login with username containing only spaces
•	Test Data: Username containing spaces only; password: secret_sauce.
•	Steps:
1.	Enter only spaces in the username field.
2.	Enter secret_sauce.
3.	Click Login.
•	Expected Result: Application should reject the input and prevent login.
•	Actual Result: Invalid credentials error displayed.
•	Status: Pass
TC-LOGIN-019: Login with numeric-only username
•	Test Data: Username: 1234567890; password: secret_sauce.
•	Steps:
1.	Enter 1234567890.
2.	Enter secret_sauce.
3.	Click Login.
•	Expected Result: Application should reject invalid credentials.
•	Actual Result: Invalid credentials error displayed.
•	Status: Pass
TC-LOGIN-020: Login with valid username and different special-character password
•	Test Data: TD-011
•	Steps:
1.	Enter standard_user.
2.	Enter secret@#$123.
3.	Click Login.
•	Expected Result: Application should reject invalid credentials.
•	Actual Result: Invalid credentials error displayed.
•	Status: Pass
4. Test Execution Summary
Metric	Result
Total Test Cases	20
Executed	20
Passed	20
Failed	0
Blocked	0
Not Executed	0
Overall Result: All 20 executed login test scenarios passed their expected outcomes.
Note: BUG-004 was observed during TC-LOGIN-010 on the Products page. The login itself passed; the product-image issue was documented separately.

