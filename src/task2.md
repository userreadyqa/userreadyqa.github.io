# Scenario
You are testing the login functionality of a web application. The login page contains:
- Username field
- Password field  
- Login button
- An error message displayed for invalid login attempts
- A "Remember Me" checkbox
- A "Forgot Password" link

# Task
Write 5-10 test cases for the login functionality, covering both positive and negative scenarios.

Use the following template for each test case:

## Test Case Template
- **Test Case ID:** A unique identifier for the test case
- **Title:** A brief description of the test case
- **Pre-conditions:** Any setup required before running the test
- **Test Steps:** Step-by-step instructions to execute the test
- **Expected Result:** The expected outcome for the test
- **Actual Result:** Leave this blank (to be filled during actual execution)
- **Priority:** Assign a priority (High/Medium/Low)
- **Remarks:** Any additional comments

# Solution
TODO: Your solution goes below
<!-- <Write your solution here> -->

<!-- 
### Test Case 1 

- **Test Case ID:** TC1 
- **Title:** Verify that alphanumberics are not applicable in the username field 
- **Pre-conditions:** The user is on the login page
- **Test Steps:** 
  - 1. Open the login page
  - 2. Enter the following into the username field: "t3s%tu8er"
  - 3. Enter a valid password into the password field
  - 4. Click on the login button
- **Expected Result:** Verify an error message is displayed for an invalid login attempt
- **Actual Result:** 
- **Priority:** High
- **Remarks:** Assuming remember me check box is unticked as default


### Test Case 2 

- **Test Case ID:** TC2 
- **Title:** Verify that numbers are not applicable in the username field 
- **Pre-conditions:** The user is on the login page
- **Test Steps:** 
  - 1. Open the login page
  - 2. Enter the following into the username field: "678456"
  - 3. Enter a valid password into the password field
  - 4. Click on the login button
- **Expected Result:** Verify an error message is displayed for an invalid login attempt
- **Actual Result:** 
- **Priority:** High


### Test Case 3 

- **Test Case ID:** TC3 
- **Title:** Verify that exceeding the username character limit (8) results in an invalid login attempt 
- **Pre-conditions:** The user is on the login page
- **Test Steps:** 
  - 1. Open the login page
  - 2. Enter the following into the username field: "usernameqa"
  - 3. Enter a valid password into the password field
  - 4. Click on the login button
- **Expected Result:** Verify an error message is displayed for an invalid login attempt
- **Actual Result:** 
- **Priority:** High

### Test Case 4 

- **Test Case ID:** TC4 
- **Title:** Verify valid login attempt with valid credentials
- **Pre-conditions:** The user is on the login page
- **Test Steps:** 
  - 1. Open the login page
  - 2. Enter a valid into the username field: "username"
  - 3. Enter a valid password into the password field: "pass123"
  - 4. Click on the login button
- **Expected Result:** Login attempt is successfull 
- **Actual Result:** 
- **Priority:** High

### Test Case 5 

- **Test Case ID:** TC5 
- **Title:** Verify the remember me feature is functional
- **Pre-conditions:** The user is on the login page
- **Test Steps:** 
  - 1. Open the login page
  - 2. Enter a valid into the username field: "username"
  - 3. Enter a valid password into the password field: "pass123"
  - 4. Click on the remember me check box
  - 5. Click on the login button
  - 6. Click on the logout button
- **Expected Result:** Login attempt is successfull. On logout, user is redirected back to the login page and the remember me checkbox is still ticked with username field pre-populated correctly and the password field empty. 
- **Actual Result:** 
- **Priority:** High

### Test Case 6 

- **Test Case ID:** TC6 
- **Title:** Verify invalid login attempt with invalid password
- **Pre-conditions:** The user is on the login page
- **Test Steps:** 
  - 1. Open the login page
  - 2. Enter a valid into the username field: "username"
  - 3. Enter a invalid password into the password field: "^&*%^GFt"
  - 4. Click on the login button
- **Expected Result:** Verify an error message is displayed for an invalid login attempt
- **Actual Result:** 
- **Priority:** High

### Test Case 7 

- **Test Case ID:** TC7 
- **Title:** Verify invalid login attempt with an blank username
- **Pre-conditions:** The user is on the login page
- **Test Steps:** 
  - 1. Open the login page
  - 2. Enter a valid into the username field: " "
  - 3. Enter a invalid password into the password field: "pass123"
  - 4. Click on the login button
- **Expected Result:** Verify an error message is displayed for an invalid login attempt
- **Actual Result:** 
- **Priority:** High

### Test Case 8 

- **Test Case ID:** TC8 
- **Title:** Verify invalid login attempt with an blank password
- **Pre-conditions:** The user is on the login page
- **Test Steps:** 
  - 1. Open the login page
  - 2. Enter a valid into the username field: "username"
  - 3. Enter a invalid password into the password field: " "
  - 4. Click on the login button
- **Expected Result:** Verify an error message is displayed for an invalid login attempt
- **Actual Result:** 
- **Priority:** High

### Test Case 9 
Verify invalid with character spaces "user name, pass 123"

-->

