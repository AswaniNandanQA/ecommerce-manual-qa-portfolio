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


TC-LOGIN-011: Verify Password Masking
•	Objective: Verify that the password is hidden when entered into the password field.
•	Precondition: The login page is open.
•	Test Data: Any sample password.
•	Steps:
1.	Open the login page.
2.	Click the password field.
3.	Enter a sample password.
4.	Observe how the password is displayed.
•	Expected Result: The password should be displayed as masked characters, such as dots or asterisks.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-LOGIN-012: Verify Show/Hide Password Functionality
•	Objective: Verify that the user can show and hide the entered password using the visibility icon.
•	Precondition: The login page provides a show/hide password option.
•	Test Data: Sample password: Test@1234
•	Steps:
1.	Open the login page.
2.	Enter a password in the password field.
3.	Click the eye icon.
4.	Observe whether the password becomes visible.
5.	Click the eye icon again.
•	Expected Result: The password should become visible when show is selected and masked again when hide is selected.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-LOGIN-013: Verify Login Using the Enter Key
•	Objective: Verify that the user can submit the login form using the Enter key.
•	Precondition: A registered user account exists.
•	Test Data: Valid username and password.
•	Steps:
1.	Open the login page.
2.	Enter a valid username.
3.	Enter the correct password.
4.	Press the Enter key.
•	Expected Result: The login form should be submitted, and the user should be logged in successfully.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-LOGIN-014: Verify Login Button Behaviour
•	Objective: Verify that the Login button responds correctly when clicked.
•	Precondition: The login page is open.
•	Test Data: Valid username and password.
•	Steps:
1.	Open the login page.
2.	Enter valid login credentials.
3.	Click the Login button once.
4.	Observe the button and application response.
•	Expected Result: The form should be submitted once, and the application should provide appropriate feedback without unintended duplicate submissions.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-LOGIN-015: Verify Error Message for Invalid Credentials
•	Objective: Verify that an appropriate error message is displayed when invalid login credentials are entered.
•	Precondition: The login page is open.
•	Test Data: Invalid username and password.
•	Steps:
1.	Open the login page.
2.	Enter invalid login credentials.
3.	Click the Login button.
4.	Observe the error message.
•	Expected Result: Login should be rejected, and a clear, appropriate error message should be displayed.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-LOGIN-016: Verify Error Message After Correcting Invalid Credentials
•	Objective: Verify that the login error message is handled correctly after the user corrects invalid credentials.
•	Precondition: The login page displays an error after a failed login attempt.
•	Test Data: First attempt: Invalid credentials. Second attempt: Valid credentials.
•	Steps:
1.	Open the login page.
2.	Enter invalid credentials and click Login.
3.	Observe the error message.
4.	Replace the incorrect credentials with valid credentials.
5.	Click Login again.
•	Expected Result: The user should log in successfully, and the previous error message should no longer be displayed as an active error.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-LOGIN-017: Verify Forgot Password Navigation
•	Objective: Verify that the Forgot Password link navigates the user to the password recovery page.
•	Precondition: The login page provides a Forgot Password link.
•	Test Data: Registered email address.
•	Steps:
1.	Open the login page.
2.	Click the Forgot Password link.
3.	Observe the navigation.
4.	Enter the registered email address if requested.
5.	Submit the recovery request.
•	Expected Result: The user should be directed to the password recovery flow and receive appropriate confirmation.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-LOGIN-018: Verify Account Lockout After Repeated Failed Login Attempts
•	Objective: Verify that the application applies the specified account protection after repeated unsuccessful login attempts.
•	Precondition: The application has a documented failed-login limit and account protection policy.
•	Test Data: Registered username and incorrect password.
•	Steps:
1.	Open the login page.
2.	Enter a registered username and incorrect password.
3.	Repeat the failed login attempt until the configured limit is reached.
4.	Observe the application's response.
•	Expected Result: The application should apply the configured account protection policy and display an appropriate message.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-LOGIN-019: Verify Logout and Access to Protected Pages
•	Objective: Verify that a logged-out user cannot access protected pages using the previous authenticated session.
•	Precondition: The user is successfully logged in.
•	Test Data: Valid user account.
•	Steps:
1.	Log in successfully.
2.	Navigate to a protected page, such as the account dashboard.
3.	Click Logout.
4.	Attempt to access the previous protected page using the browser's Back button.
5.	Observe the application response.
•	Expected Result: The user should be logged out. Protected content should not remain accessible through the previous authenticated session.
•	Actual Result: Not Executed.
•	Status: Not Executed.


TC-LOGIN-020: Verify Session Timeout After Inactivity
•	Objective: Verify that the application handles an inactive user session according to its session timeout policy.
•	Precondition: The user is logged in, and the application has a defined session timeout period.
•	Test Data: Valid user account.
•	Steps:
1.	Log in successfully.
2.	Leave the application inactive for the configured timeout period.
3.	Attempt to access a protected page or perform an authenticated action.
4.	Observe the application's response.
•	Expected Result: The session should expire according to the configured policy, and the user should be asked to log in again.
•	Actual Result: Not Executed.
•	Status: Not Executed.



