# E-Commerce Application – Test Execution Report

## 1. Execution Report Information

| Field | Details |
|---|---|
| Project Name | E-Commerce Web Application |
| Module | Login Functionality |
| Document Name | Test Execution Report |
| Version | 1.0 |
| Prepared By | Vipin Yadav |
| Testing Type | Functional Testing |
| Test Environment | Windows 11 |
| Browser | Google Chrome |
| Execution Cycle | Cycle 1 |

## 2. Test Execution Summary

The purpose of this document is to record the execution results of login functionality test cases and summarize the overall testing status.

**Note:** The following execution data is illustrative and has not been collected from a live application.

| Metric | Count |
|---|---:|
| Total Test Cases | 15 |
| Passed | 10 |
| Failed | 3 |
| Blocked | 1 |
| Not Executed | 1 |
| Total Executed | 14 |

## 3. Test Execution Details

| Test Case ID | Test Scenario | Expected Result | Actual Result | Status |
|---|---|---|---|---|
| TC_LOGIN_001 | Login with valid credentials | User should log in successfully | Login successful | Passed |
| TC_LOGIN_002 | Login with invalid email | Error message should appear | Error message displayed | Passed |
| TC_LOGIN_003 | Login with invalid password | Login should fail | Login rejected | Passed |
| TC_LOGIN_004 | Login with empty fields | Required field validation should appear | Validation displayed | Passed |
| TC_LOGIN_005 | Login with empty email | Email validation should appear | Validation displayed | Passed |
| TC_LOGIN_006 | Login with empty password | Password validation should appear | Validation displayed | Passed |
| TC_LOGIN_007 | Password masking | Password should be masked | Password displayed in plain text | Failed |
| TC_LOGIN_008 | Password visibility option | Visibility should toggle | Feature working correctly | Passed |
| TC_LOGIN_009 | Forgot Password navigation | Recovery page should open | Recovery page opened | Passed |
| TC_LOGIN_010 | Login using Enter key | Login should be triggered | Login triggered successfully | Passed |
| TC_LOGIN_011 | Invalid email format | Validation should appear | Validation displayed | Passed |
| TC_LOGIN_012 | Uppercase email handling | Email should be handled as per requirements | Behavior needs further verification | Blocked |
| TC_LOGIN_013 | Password case sensitivity | Incorrect casing should be rejected | Incorrect password rejected | Passed |
| TC_LOGIN_014 | Session after page refresh | Session should remain according to policy | Session behavior not verified | Not Executed |
| TC_LOGIN_015 | Logout functionality | User should be logged out | User logged out successfully | Passed |

## 4. Failed Test Case Details

### Failure 1

- **Test Case ID:** TC_LOGIN_007
- **Module:** Login
- **Status:** Failed
- **Severity:** Medium
- **Related Bug ID:** BUG_LOGIN_002

**Expected Result:**

Password should be masked by default.

**Actual Result:**

Password characters are visible in plain text.

**Action Required:**

Report the defect and retest after the fix.

### Failure 2

- **Test Case ID:** Illustrative failure record
- **Module:** Login
- **Status:** Failed

**Expected Result:**

Application should reject incorrect credentials.

**Actual Result:**

Login behavior did not match the expected authentication requirement.

**Action Required:**

Investigate and report the defect.

### Failure 3

- **Test Case ID:** Illustrative failure record
- **Module:** Login
- **Status:** Failed

**Expected Result:**

Application should display the appropriate validation message.

**Actual Result:**

Validation message was not displayed as expected.

**Action Required:**

Report the defect and perform retesting after resolution.

## 5. Execution Metrics

| Execution Status | Count |
|---|---:|
| Passed | 10 |
| Failed | 3 |
| Blocked | 1 |
| Not Executed | 1 |
| Total | 15 |

### Test Execution Progress

Execution completion percentage:

Executed Test Cases / Total Test Cases × 100

= 14 / 15 × 100

= 93.33%

### Pass Percentage

Passed Test Cases / Executed Test Cases × 100

= 10 / 14 × 100

= 71.43%

## 6. Defect Summary

| Bug ID | Description | Severity | Status |
|---|---|---|---|
| BUG_LOGIN_002 | Password displayed in plain text | Medium | Open |
| BUG_LOGIN_001 | Authentication validation issue | Critical | Open |
| BUG_LOGIN_004 | Validation message issue | Medium | Open |

*Note: Defect references are illustrative and should be reconciled with actual defect records.*

## 7. Blocked Test Cases

**Test Case ID:** TC_LOGIN_012

**Reason:** Required application behavior and approved requirements are not available for verification.

**Action:** Obtain requirement clarification and execute the test case once confirmed.

## 8. Test Execution Observations

- Most login test cases have passed in this illustrative execution cycle.
- Password masking requires correction.
- Authentication and validation defects require investigation.
- One test case is blocked due to requirement clarification.
- One test case remains pending execution.

## 9. Test Execution Conclusion

Based on the illustrative execution results, the login module requires further defect resolution and validation before sign-off.

Failed test cases should be retested after defect fixes, and regression testing should be performed to ensure that existing functionality is not impacted.

## 10. Approval

| Role | Name | Status |
|---|---|---|
| Prepared By | Vipin Yadav | Prepared |
| Reviewed By | QA Lead | Pending |
| Approved By | Project Manager | Pending |

---

**Author:** Vipin Yadav  
**Role:** Software QA Engineer
