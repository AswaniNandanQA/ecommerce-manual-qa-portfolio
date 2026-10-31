E-commerce Application – Test Execution Report
1. Project Information
•	Project Name: E-commerce Website Testing
•	Testing Type: Manual Testing
•	Test Environment: Google Chrome on Windows
•	Test Cycle: Practice Test Cycle 1
•	Execution Status: Not Started
•	Prepared By: QA Tester

2. Test Execution Summary
Metric	Count
Total Test Cases	80
Executed	10
Passed	10
Failed	0
Blocked	0
Not Executed	74

## 3. Test Execution Details

| Test Case ID | Test Scenario | Actual Result | Status | Defect ID |
|---|---|---|---|---|
| TC-LOGIN-001 | Login with valid credentials | Products page appeared successfully | Pass | N/A |
| TC-LOGIN-002 | Login with incorrect password | Invalid credentials error message displayed | Pass | N/A |
| TC-LOGIN-003 | Login with unregistered username | Invalid credentials error message displayed | Pass | N/A |
| TC-LOGIN-004 | Login with both incorrect username and incorrect password | Invalid credentials error message displayed | Pass | N/A |
| TC-LOGIN-005 | Login with both fields empty | Username required error message displayed | Pass | N/A |
| TC-LOGIN-006 | Login with empty username and valid password | Username required error message displayed | Pass | N/A |
| TC-LOGIN-007 | Login with valid username and empty password | Password required error message displayed | Pass | N/A |
| TC-LOGIN-008 | Login with invalid username and empty password | Password required error message displayed | Pass | N/A |
| TC-LOGIN-009 | Login with locked-out user credentials | Locked-out user error message displayed | Pass | N/A |
| TC-LOGIN-010 | Login with problem user credentials | Products page displayed successfully; incorrect product images observed | Pass | BUG-004 |
| TC-LOGIN-011 | Login with performance glitch user | Products page displayed successfully after a noticeable delay | Pass | N/A |
| TC-LOGIN-012 | Login with visual user credentials | Products page displayed successfully; no unusual behaviour observed | Pass | N/A |
| TC-LOGIN-013 | Login with leading and trailing spaces in username | Invalid credentials error message displayed | Pass | N/A |
| TC-LOGIN-014 | Login with uppercase username | Invalid credentials error message displayed | Pass | N/A |
| TC-LOGIN-015 | Login with uppercase password | Invalid credentials error message displayed | Pass | N/A |
| TC-LOGIN-016 | Login with very long username | Invalid credentials error message displayed | Pass | N/A |
| TC-LOGIN-017 | Login with special characters in username | Invalid credentials error message displayed | Pass | N/A |
| TC-LOGIN-018 | Login with username containing only spaces | Invalid credentials error message displayed | Pass | N/A |
| TC-LOGIN-019 | Login with numeric-only username | Invalid credentials error message displayed | Pass | N/A |
| TC-LOGIN-020 | Login with special characters in password | Invalid credentials error message displayed | Pass | N/A |

| TC-REG-001 | Register with valid details | Not Executed | Not Executed | N/A |
| TC-REG-002 | Register with an existing email | Not Executed | Not Executed | N/A |
| TC-SEARCH-001 | Search with a valid product name | Not Executed | Not Executed | N/A |
| TC-SEARCH-003 | Search with an invalid product name | Not Executed | Not Executed | N/A |
| TC-CART-001 | Add a single product to the cart	 | Not Executed | Not Executed | N/A |
| TC-CART-009 | Remove a product from the cart | Not Executed | Not Executed | N/A |
| TC-CHECKOUT-001 | Proceed to checkout with a valid cart | Not Executed | Not Executed | N/A |
| TC-CHECKOUT-004 | Verify successful order placement | Not Executed | Not Executed | N/A |


This table is an initial execution template containing 10 selected test cases. The full project contains 80 documented test cases.

4. Defect Summary
Defect ID	Defect Description	Severity	Priority	Status
BUG-001	Product not added to cart	Sample: Critical	Sample: High	Sample
BUG-002	Login accepts invalid credentials	Sample: Critical	Sample: High	Sample
BUG-003	Incorrect checkout total	Sample: Major	Sample: High	Sample

5. Testing Observations
•	Test cases have been documented for five major e-commerce modules.
•	Sample defect reports have been prepared for practice.
•	Actual execution has not started.
•	Defects must be reproduced before being reported as real application issues.

6. Conclusion
The test case documentation and sample defect reports are prepared for the e-commerce manual testing portfolio.
Actual test execution, defect verification, and final testing conclusions are pending.

7. Future Activities
1.	Execute the documented test cases against a test application.
2.	Record actual results.
3.	Update test statuses to Pass, Fail, or Blocked.
4.	Create defect reports for reproducible failures.
5.	Perform retesting after fixes.
6.	Prepare the final test summary report.

