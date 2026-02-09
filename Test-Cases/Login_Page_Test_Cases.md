# Login Page Test Cases
## Test Case 1: Login with empty username
**Objective:**  
Verify that the system displays an error when the username/email field is left empty during login.
**Preconditions:**  
- User is on the Facebook login page.
- User has access to a valid password (any string).
**Test Steps:**  
1. Open the Facebook login page.  
2. Leave the username/email field empty.  
3. Enter any password in the password field.  
4. Click the Login button.
**Expected Result:**  
- The system should display an error message asking the user to enter an email or mobile number.
**Actual Result:**
Error message "The email address or mobile number you entered isn't connected to an account" is displayed below the email field.

**Status:**
Pass
----

## Test Case 2: Login with empty password
**Objective:**  
Verify that the system displays an error when the password field is left empty during login.
**Preconditions:**  
- User is on the Facebook login page.
- User has access to a valid email id.
**Test Steps:**  
1. Open the Facebook login page.  
2. Enter the valid email id in the email or phone number field.
3. Leave the password field empty.  
4. Click the Login button.
**Expected Result:**  
- The system should display an error message asking the user to enter a valid password.
**Actual Result:**
Error message "The password you've entered is incorrect. Forgot password?" is displayed below the password field.

**Status:**
Pass




