# Login Test Cases

# Login Functionality – Test Cases

## Project Information

- **Project:** E-Commerce Application
- **Module:** User Login
- **Testing Type:** Functional Testing
- **Test Environment:** Web Application
- **Test Design Techniques:** Equivalence Partitioning, Boundary Value Analysis

## Test Cases

| Test Case ID | Test Scenario | Test Steps | Test Data | Expected Result | Priority |
|---|---|---|---|---|---|
| TC_LOGIN_001 | Login with valid credentials | Enter valid email and password, click Login | Valid email/password | User should successfully log in and navigate to the homepage | High |
| TC_LOGIN_002 | Login with invalid email | Enter invalid email and valid password, click Login | invalid@email.com | Appropriate error message should be displayed | High |
| TC_LOGIN_003 | Login with invalid password | Enter valid email and incorrect password | Incorrect password | Login should fail with an appropriate error message | High |
| TC_LOGIN_004 | Login with both fields empty | Leave email and password blank, click Login | Blank fields | Required field validation should be displayed | High |
| TC_LOGIN_005 | Login with empty email | Leave email blank and enter password | Blank email | Email validation message should be displayed | High |
| TC_LOGIN_006 | Login with empty password | Enter email and leave password blank | Blank password | Password validation message should be displayed | High |
| TC_LOGIN_007 | Verify password masking | Enter password in password field | Any password | Password characters should be masked | Medium |
| TC_LOGIN_008 | Verify password visibility option | Click password visibility icon | Any password | Password should become visible or masked accordingly | Medium |
| TC_LOGIN_009 | Verify Forgot Password link | Click Forgot Password | Registered email | User should navigate to password recovery page | Medium |
| TC_LOGIN_010 | Verify login using Enter key | Enter valid credentials and press Enter | Valid credentials | Login should be triggered | Medium |
| TC_LOGIN_011 | Verify email format validation | Enter invalid email format | abc@ | Appropriate email validation should be displayed | Medium |
| TC_LOGIN_012 | Verify email field accepts uppercase | Enter registered email using uppercase letters | USER@EMAIL.COM | Email should be handled according to application requirements | Low |
| TC_LOGIN_013 | Verify password case sensitivity | Enter password with different letter casing | Modified password | Login should fail if password does not match | High |
| TC_LOGIN_014 | Verify session after successful login | Log in and refresh the page | Valid credentials | Session should remain active according to session policy | Medium |
| TC_LOGIN_015 | Verify logout functionality | Log in and click Logout | Valid credentials | User should be logged out successfully | High |

## Test Execution Summary

Execution status will be updated after testing the application.

| Status | Count |
|---|---:|
| Total Test Cases | 15 |
| Passed | Not Executed |
| Failed | Not Executed |
| Blocked | Not Executed |
| Not Executed | 15 |

## Notes

- Test cases are designed for a sample e-commerce login module.
- Actual results and execution status should be updated after execution.
- Test data should be prepared using valid and invalid user accounts.
- Expected behavior should be validated against approved application requirements.

---

**Author:** Vipin Yadav  
**Role:** Software QA Engineer
