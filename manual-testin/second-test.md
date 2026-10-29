Authentication testing
## TC-007: Invalid password
Steps
1. Enter standard_user as the username.
2. Enter an incorrect password.
3. Click Login.

**Expected result:** Login is rejected, an appropriate error message appears, and the products page is not accessible.
**Actual Result:** The application displayed "Epic sadface: Username and password do not match any user in this service".

**Status:** PASS

## TC-008: Locked-Out Account

**Expected Result:** The application denies access and displays an appropriate message indicating that the account is locked.

**Actual Result:** The application displayed "Epic sadface: Sorry, this user has been locked out."

**Status:** PASS


## TC-009: Empty Username

**Objective:** Verify that the application prevents login when the username field is empty.

**Expected Result:** The application rejects the login attempt and displays a validation message indicating that the username is required.

**Actual Result:** The application displayed "Epic sadface: Username is required".

**Status:** PASS

---

## TC-009: Empty Password 

**Objective:** Verify that the application prevents login when the password field is empty.

**Expected Result:** The application rejects the login attempt and displays a validation message indicating that the password is required.

**Actual Result:** The application displayed "Epic sadface: Password is required".

**Status:** PASS

---