## TC-001: Successful Login

**Objective:** Verify that a user can log in successfully using valid credentials.

**Expected Result:** The user is redirected to the products page after successful login.

**Actual Result:** The user successfully logged in and reached the products page.

**Status:** PASS

---

## TC-002: Add Product to Cart

**Objective:** Verify that a selected product can be added to the shopping cart.

**Expected Result:** The selected product appears in the shopping cart.

**Actual Result:** The Sauce Labs Backpack appeared in the cart. The Sauce Labs Bike Light was also added to the cart during testing.

**Status:** PASS

---

## TC-003: Open Checkout Page

**Objective:** Verify that clicking Checkout opens the checkout information page.

**Expected Result:** The checkout information form is displayed.

**Actual Result:** The checkout form was displayed with First Name, Last Name, and Zip/Postal Code fields.

**Status:** PASS

---

## TC-004: Required Field Validation

**Objective:** Verify that the application prevents checkout from proceeding when required fields are left empty.

**Expected Result:** The application displays a validation error and prevents the user from proceeding.

**Actual Result:** The application displayed an error requiring all fields to be filled in.

**Status:** PASS

---

## TC-005: Submit Valid Checkout Information

**Objective:** Verify that submitting valid checkout information allows the user to proceed to the order summary.

**Expected Result:** The order summary displays the selected product and the correct price breakdown.

**Actual Result:** The order summary displayed the Sauce Labs Bike Light at $9.99, tax of $0.80, and a total of $10.79.

**Status:** PASS

---

## TC-006: Complete Order

**Objective:** Verify that clicking Finish completes the order successfully.

**Expected Result:** An order confirmation message is displayed.

**Actual Result:** The application displayed "Thank you for your order!" and confirmed that the order had been dispatched.

**Status:** PASS