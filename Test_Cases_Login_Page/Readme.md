Login Module – Test Cases

This folder contains manual test cases designed for the **Login module**
of the Facebook web application.

The test cases validate the functional behavior, UI elements, input
validations, error handling, and performance of the login functionality.

---------------------------------------------------------------------------------------------------

Module Covered
- Login

---------------------------------------------------------------------------------------------------

Test Case Coverage
The following scenarios are covered in this module:

- Login with valid email and password
- Login with valid phone number and password
- Login with invalid email format
- Login with mismatched password
- Login with empty email and password fields
- Forgot password functionality
- Show / Hide password icon behavior
- Login button enable/disable behavior
- Error message validation and reset behavior
- Basic login performance check

---------------------------------------------------------------------------------------------------

Types of Testing Performed
- Functional Testing
- UI Testing
- Negative Testing
- Validation Testing
- Regression Testing
- Performance Testing

---------------------------------------------------------------------------------------------------

Test Data
Test cases include combinations of:
- Valid and invalid email addresses
- Valid and invalid passwords
- Empty input fields
- Boundary value inputs

Dummy test data is used to simulate real user scenarios.

---------------------------------------------------------------------------------------------------

Defects Identified
Multiple high and critical severity defects were identified during testing,
including:
- Login allowed without entering credentials
- Login allowed with mismatched password
- Login allowed with invalid email format

These defects are documented separately in the **Defect_Report** folder.

---------------------------------------------------------------------------------------------------

Test Environment
- Operating System: Windows 10
- Browser: Google Chrome
- Application Type: Web Application

---------------------------------------------------------------------------------------------------

Status Summary
- Total test cases executed: 12
- Passed: Majority of functional and UI scenarios
- Failed: Negative and validation scenarios (defects logged)

---------------------------------------------------------------------------------------------------

Author
Ashwini Sudke  
Manual QA Engineer

