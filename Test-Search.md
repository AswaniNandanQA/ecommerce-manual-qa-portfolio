E-commerce Search – Test Cases
Module: Product Search
Test Objective: To verify that the product search functionality works correctly under different conditions.
Precondition: The user is on the e-commerce website, and the search feature is available.
________________________________________


TC-SEARCH-001: Search with a valid product name
•	Test Data: Laptop
•	Steps:
1.	Open the e-commerce website.
2.	Enter "Laptop" in the search box.
3.	Click the Search button.
•	Expected Result: Relevant laptop products should be displayed.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-SEARCH-002: Search with a partial product name
•	Test Data: Lap
•	Steps:
1.	Enter "Lap" in the search box.
2.	Click Search.
•	Expected Result: Relevant products matching the partial search term should be displayed, if partial matching is supported.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-SEARCH-003: Search with an invalid product name
•	Test Data: XYZ12345
•	Steps:
1.	Enter "XYZ12345" in the search box.
2.	Click Search.
•	Expected Result: A suitable "No products found" message should be displayed.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-SEARCH-004: Search with an empty search field
•	Test Data: Empty
•	Steps:
1.	Leave the search box empty.
2.	Click Search.
•	Expected Result: The website should handle the empty search appropriately without displaying unexpected results or errors.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-SEARCH-005: Search using numbers
•	Test Data: 12345
•	Steps:
1.	Enter "12345" in the search box.
2.	Click Search.
•	Expected Result: Matching products should be displayed, or a suitable no-results message should appear.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-SEARCH-006: Search using special characters
•	Test Data: @#$%
•	Steps:
1.	Enter "@#$%" in the search box.
2.	Click Search.
•	Expected Result: The website should handle special characters safely without crashing or displaying unexpected errors.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-SEARCH-007: Search using uppercase letters
•	Test Data: LAPTOP
•	Steps:
1.	Enter "LAPTOP" in the search box.
2.	Click Search.
•	Expected Result: Relevant products should be displayed if search is case-insensitive.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-SEARCH-008: Search using lowercase letters
•	Test Data: laptop
•	Steps:
1.	Enter "laptop" in the search box.
2.	Click Search.
•	Expected Result: Relevant products should be displayed.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-SEARCH-009: Search with leading and trailing spaces
•	Test Data: Laptop 
•	Steps:
1.	Enter " Laptop " in the search box.
2.	Click Search.
•	Expected Result: Leading and trailing spaces should be handled according to the search requirements. If trimming is supported, relevant laptop products should appear.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-SEARCH-010: Search with a long search term
•	Test Data: A search term containing 100 or more characters.
•	Steps:
1.	Enter a long search term in the search box.
2.	Click Search.
•	Expected Result: The website should handle long input safely without breaking the page.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-SEARCH-011: Verify search results relevance
•	Test Data: Mobile
•	Steps:
1.	Search for "Mobile".
2.	Review the displayed products.
•	Expected Result: Displayed products should be relevant to the search term.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-SEARCH-012: Verify search suggestions
•	Test Data: Lap
•	Steps:
1.	Enter "Lap" in the search box.
2.	Observe the suggestions, if available.
•	Expected Result: Relevant search suggestions should appear if the website supports autocomplete.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-SEARCH-013: Verify search using the Enter key
•	Test Data: Laptop
•	Steps:
1.	Enter "Laptop" in the search box.
2.	Press the Enter key.
•	Expected Result: The search should be triggered and relevant results should appear.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-SEARCH-014: Verify search button functionality
•	Test Data: Headphones
•	Steps:
1.	Enter "Headphones" in the search box.
2.	Click the Search button.
•	Expected Result: The search should be triggered and relevant headphone products should appear.
•	Actual Result: Not Executed
•	Status: Not Executed


TC-SEARCH-015: Verify search results after refreshing the page
•	Test Data: Laptop
•	Steps:
1.	Search for "Laptop".
2.	Wait for the search results to appear.
3.	Refresh the page.
•	Expected Result: Search results should behave according to the website's requirements. If search state is preserved, the same results should appear.
•	Actual Result: Not Executed
•	Status: Not Executed
________________________________________
Test Summary
•	Total Test Cases: 15
•	Executed: 0
•	Passed: 0
•	Failed: 0
•	Not Executed: 15

