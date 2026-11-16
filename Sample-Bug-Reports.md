# E-Commerce Application – Sample Bug Reports

## 1. Project Information

- **Project:** E-Commerce Application
- **Module:** Login, Registration, Product Search and Shopping Cart
- **Testing Type:** Functional Testing
- **Environment:** Web Application
- **Browser:** Google Chrome
- **Document Type:** Defect Report

## 2. Bug Report 1 – Login with Invalid Password

| Field | Details |
|---|---|
| Bug ID | BUG_LOGIN_001 |
| Bug Title | Application accepts an incorrect password |
| Module | Login |
| Severity | Critical |
| Priority | High |
| Status | Open |
| Environment | Chrome, Windows 11 |

**Preconditions:**
- User should have a registered account.
- User should be on the login page.

**Steps to Reproduce:**
1. Open the application login page.
2. Enter a valid registered email address.
3. Enter an incorrect password.
4. Click the Login button.

**Expected Result:**

Application should reject the login request and display an appropriate error message.

**Actual Result:**

Application allows the user to log in despite entering an incorrect password.

**Attachments:** Screenshot/video evidence to be added after reproducing the issue.

---

## 3. Bug Report 2 – Password Visible by Default

| Field | Details |
|---|---|
| Bug ID | BUG_LOGIN_002 |
| Bug Title | Password is displayed in plain text by default |
| Module | Login |
| Severity | Medium |
| Priority | Medium |
| Status | Open |
| Environment | Chrome, Windows 11 |

**Preconditions:**
- User should be on the login page.

**Steps to Reproduce:**
1. Open the login page.
2. Enter a password in the password field.
3. Observe the entered characters.

**Expected Result:**

Password should be masked by default.

**Actual Result:**

Password characters are displayed in plain text without enabling the password visibility option.

**Attachments:** Screenshot evidence to be added after reproducing the issue.

---

## 4. Bug Report 3 – Add to Cart Button Not Working

| Field | Details |
|---|---|
| Bug ID | BUG_CART_001 |
| Bug Title | Add to Cart button does not add the selected product |
| Module | Shopping Cart |
| Severity | Major |
| Priority | High |
| Status | Open |
| Environment | Chrome, Windows 11 |

**Preconditions:**
- User should be on the product details page.
- Product should be available in stock.

**Steps to Reproduce:**
1. Open the e-commerce application.
2. Navigate to any available product.
3. Click the Add to Cart button.
4. Open the shopping cart.

**Expected Result:**

Selected product should be added successfully to the shopping cart.

**Actual Result:**

Product is not added to the shopping cart after clicking the Add to Cart button.

**Attachments:** Screenshot/video evidence to be added after reproducing the issue.

---

## 5. Bug Report 4 – Incorrect Product Search Results

| Field | Details |
|---|---|
| Bug ID | BUG_SEARCH_001 |
| Bug Title | Search displays unrelated products |
| Module | Product Search |
| Severity | Major |
| Priority | Medium |
| Status | Open |
| Environment | Chrome, Windows 11 |

**Preconditions:**
- User should be on the application homepage.

**Steps to Reproduce:**
1. Open the application.
2. Enter a specific product name in the search field.
3. Click the Search button.
4. Observe the displayed results.

**Expected Result:**

Search results should display products relevant to the entered search keyword.

**Actual Result:**

Search results display unrelated products.

**Attachments:** Screenshot evidence to be added after reproducing the issue.

---

## 6. Bug Report 5 – Cart Quantity Not Updated

| Field | Details |
|---|---|
| Bug ID | BUG_CART_002 |
| Bug Title | Product quantity is not updated after clicking the increase button |
| Module | Shopping Cart |
| Severity | Major |
| Priority | High |
| Status | Open |
| Environment | Chrome, Windows 11 |

**Preconditions:**
- User should have at least one product in the shopping cart.

**Steps to Reproduce:**
1. Open the shopping cart.
2. Locate the product quantity field.
3. Click the increase quantity button.
4. Observe the quantity and total price.

**Expected Result:**

Product quantity and total price should be updated correctly.

**Actual Result:**

Product quantity and total price remain unchanged after clicking the increase button.

**Attachments:** Screenshot/video evidence to be added after reproducing the issue.

---

## 7. Bug Report 6 – Logout Does Not Terminate Session

| Field | Details |
|---|---|
| Bug ID | BUG_LOGIN_003 |
| Bug Title | User can access protected pages after logout |
| Module | Authentication |
| Severity | Critical |
| Priority | High |
| Status | Open |
| Environment | Chrome, Windows 11 |

**Preconditions:**
- User should be logged into the application.

**Steps to Reproduce:**
1. Log in using valid credentials.
2. Navigate to the user dashboard.
3. Click the Logout button.
4. Use the browser Back button.
5. Attempt to access a protected page.

**Expected Result:**

User should not be able to access protected pages after logout without authenticating again.

**Actual Result:**

Protected page remains accessible after logout.

**Attachments:** Screenshot/video evidence to be added after reproducing the issue.

---

## 8. Defect Summary

| Bug ID | Module | Severity | Priority | Status |
|---|---|---|---|---|
| BUG_LOGIN_001 | Login | Critical | High | Open |
| BUG_LOGIN_002 | Login | Medium | Medium | Open |
| BUG_CART_001 | Shopping Cart | Major | High | Open |
| BUG_SEARCH_001 | Product Search | Major | Medium | Open |
| BUG_CART_002 | Shopping Cart | Major | High | Open |
| BUG_LOGIN_003 | Authentication | Critical | High | Open |

## 9. Important Notes

- These are sample defect reports created for portfolio demonstration.
- The defects are hypothetical and have not been verified against a live application.
- Screenshots and actual execution evidence should be attached when defects are reproduced.
- Severity and priority should be assigned based on business impact and project requirements.
- Defect status should be updated throughout the defect life cycle.

---

**Author:** Vipin Yadav  
**Role:** Software QA Engineer
