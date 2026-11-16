# Login Test Scenario

# Login Functionality – Test Scenarios

## 1. Project Information

- **Project:** E-Commerce Application
- **Module:** User Login
- **Testing Type:** Functional Testing
- **Testing Approach:** Positive, Negative, Boundary Value and Security Testing

## 2. Login Test Scenarios

| Scenario ID | Test Scenario | Expected Outcome | Priority |
|---|---|---|---|
| TS_LOGIN_001 | Verify login using valid registered credentials | User should log in successfully | High |
| TS_LOGIN_002 | Verify login using an invalid email address | Appropriate validation message should appear | High |
| TS_LOGIN_003 | Verify login using an incorrect password | Login should be rejected | High |
| TS_LOGIN_004 | Verify login with both fields empty | Required field validations should appear | High |
| TS_LOGIN_005 | Verify login with email field empty | Email validation should appear | High |
| TS_LOGIN_006 | Verify login with password field empty | Password validation should appear | High |
| TS_LOGIN_007 | Verify email field with invalid formats | Invalid email formats should be rejected | Medium |
| TS_LOGIN_008 | Verify password field masking | Password should be masked by default | Medium |
| TS_LOGIN_009 | Verify password visibility functionality | Password visibility should toggle correctly | Medium |
| TS_LOGIN_010 | Verify Forgot Password navigation | User should reach password recovery page | Medium |
| TS_LOGIN_011 | Verify login using keyboard Enter key | Login action should be triggered | Medium |
| TS_LOGIN_012 | Verify email field with leading and trailing spaces | Input should be handled according to requirements | Medium |
| TS_LOGIN_013 | Verify password case sensitivity | Password comparison should be case-sensitive | High |
| TS_LOGIN_014 | Verify account behavior after multiple failed login attempts | Account protection policy should be enforced | High |
| TS_LOGIN_015 | Verify login session after browser refresh | Session should behave according to requirements | Medium |
| TS_LOGIN_016 | Verify logout after successful login | User session should be terminated | High |
| TS_LOGIN_017 | Verify browser back button after logout | Protected pages should not remain accessible without authentication | High |
| TS_LOGIN_018 | Verify login functionality across supported browsers | Login should work consistently | Medium |
| TS_LOGIN_019 | Verify login functionality on different screen sizes | Login page should display correctly | Medium |
| TS_LOGIN_020 | Verify SQL injection attempts in login fields | Malicious input should not bypass authentication | High |

## 3. Positive Testing Scenarios

1. Login using valid registered email and password.
2. Login using valid credentials with different supported email casing.
3. Login using keyboard Enter key.
4. Navigate to password recovery using Forgot Password.
5. Maintain an authenticated session according to the session policy.

## 4. Negative Testing Scenarios

1. Login using an unregistered email address.
2. Login using an incorrect password.
3. Submit login form with empty fields.
4. Enter invalid email formats.
5. Enter incorrect password multiple times.
6. Enter special characters in email and password fields.
7. Attempt SQL injection through login fields.

## 5. Boundary Value Testing Scenarios

1. Verify minimum allowed email length.
2. Verify maximum allowed email length.
3. Verify minimum password length.
4. Verify maximum password length.
5. Verify behavior when password length is below the minimum.
6. Verify behavior when password length exceeds the maximum.

## 6. Security Testing Scenarios

1. Verify password is not displayed in plain text by default.
2. Verify login credentials are transmitted securely over HTTPS.
3. Verify account lockout or rate-limiting policies.
4. Verify session expiration after inactivity.
5. Verify unauthorized access to protected pages.
6. Verify SQL injection protection.
7. Verify session invalidation after logout.

## 7. Compatibility Testing Scenarios

1. Verify login functionality in Chrome.
2. Verify login functionality in Firefox.
3. Verify login functionality in Edge.
4. Verify login page responsiveness on desktop.
5. Verify login page responsiveness on mobile devices.

## 8. Conclusion

The above scenarios cover major functional, negative, boundary, security and compatibility aspects of the e-commerce login module.

Detailed test cases should be prepared for each scenario based on application requirements.

---

**Author:** Vipin Yadav  
**Role:** Software QA Engineer
