BUG-002: Login Accepts Invalid Credentials
Bug ID
BUG-002

Bug Title
Application allows users to log in with invalid credentials.

Module
Login / Authentication

Environment
•	Application: E-commerce Website
•	Browser: Google Chrome
•	Operating System: Windows
•	Test Type: Manual Testing

Severity
Critical

Priority
High

Preconditions
1.	The e-commerce website is accessible.
2.	The user is on the login page.
3.	Invalid login credentials are available for testing.
   
Test Steps
1.	Open the e-commerce website.
2.	Navigate to the login page.
3.	Enter an unregistered username or email address.
4.	Enter an incorrect password.
5.	Click the Login button.
6.	Observe the application response.
   
Test Data
•	Username/Email: unregistered@example.com
•	Password: WrongPassword123

Expected Result
The application should reject the invalid credentials and display an appropriate error message. The user should not be allowed to access the account.

Actual Result
The application accepts the invalid credentials and allows the user to access the account.

Reproducibility
Always (in this example scenario)

Status
Open

Attachments
Screenshot or screen recording: To be added when the issue is reproduced.

Additional Notes
This is a sample portfolio bug report. It represents a serious authentication failure. Actual severity, priority, reproducibility, and status must be confirmed through testing before reporting it as a real defect.

