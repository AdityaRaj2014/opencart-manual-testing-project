OpenCart Manual Testing - Test Cases
User Registration
TC-REG-001 — Successful User Registration

| Field | Details |
|---|---|
| Test Case ID | TC-REG-001 |
| Requirement ID | REQ-REG-01 |
| Scenario ID | TS-REG-01 |
| Test Case | Verify that a new user can register successfully |
| Preconditions | User is on the OpenCart Store Front and does not already have an account |
| Test Data | Valid registration details |
| Expected Result | User account should be created successfully |


Test Steps
| Step | Action | Test Data | Expected Result |
|---|---|---|---|
| 1 | Open the OpenCart Store Front | OpenCart URL | OpenCart Store Front should be displayed. |
| 2 | Open the My Account menu | — | My Account options should be displayed. |
| 3 | Select Register | — | Registration page should be displayed. |
| 4 | Enter valid registration details in all mandatory fields | Valid name, email, password, etc. | The entered information should be accepted. |
| 5 | Click Continue/Register | — | Registration should be processed successfully. |
| 6 | Verify the registration result | — | User account should be created successfully. |


Test Execution Result
| Field | Result |
|---|---|
| Actual Result | User account was created successfully. |
| Status | PASS |


TC-REG-002 — Invalid Email Registration
| Field | Details |
|---|---|
| Test Case ID | TC-REG-002 |
| Requirement ID | REQ-REG-03 |
| Scenario ID | TS-REG-03 |
| Test Case | Verify that the system validates the email address during registration |
| Preconditions | User is on the registration page |
| Test Data | Invalid email address |
| Expected Result | System should reject the invalid email address and display an appropriate validation message. |

Test Steps
| Step | Action | Test Data | Expected Result |
|---|---|---|---|
| 1 | Open the registration page | — | Registration page should be displayed. |
| 2 | Enter valid information in all mandatory fields | Valid details | Information should be accepted. |
| 3 | Enter an invalid email address | `aditya@` | System should identify the email as invalid. |
| 4 | Click Continue/Register | — | Registration should not be completed and an appropriate validation message should be displayed. |



