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
