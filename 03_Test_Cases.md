# Test Cases - OrangeHRM Manual Testing Project

# Login Module Test Cases

| Test Case ID | Test Scenario | Test Steps | Test Data | Expected Result | Status |
|---|---|---|---|---|---|
| TC_001 | Valid Login | Enter valid username and password, click login | Username: Admin Password: admin123 | User should login successfully | Pass |
| TC_002 | Invalid Login | Enter invalid credentials and click login | Invalid username/password | Error message should be displayed | Pass |
| TC_003 | Empty Username | Leave username empty and enter password | Password: admin123 | Username required message should appear | Pass |
| TC_004 | Empty Password | Enter username and leave password empty | Username: Admin | Password required message should appear | Pass |
| TC_005 | Logout Functionality | Login and click logout | Valid credentials | User should logout successfully | Pass |

# Dashboard Module Test Cases

| Test Case ID | Test Scenario | Test Steps | Expected Result | Status |
|---|---|---|---|---|
| TC_006 | Dashboard Verification | Login and check dashboard | Dashboard should be displayed | Pass |
| TC_007 | Menu Navigation | Click different menu options | User should navigate successfully | Pass |

# Admin Module Test Cases

| Test Case ID | Test Scenario | Test Steps | Expected Result | Status |
|---|---|---|---|---|
| TC_008 | Add User | Open Admin module and add new user | New user should be created | Pass |
| TC_009 | Search User | Search existing user | User record should display | Pass |
| TC_010 | Delete User | Select user and delete | User should be deleted | Pass |

# PIM Module Test Cases

| Test Case ID | Test Scenario | Test Steps | Expected Result | Status |
|---|---|---|---|---|
| TC_011 | Add Employee | Enter employee details and save | Employee should be added | Pass |
| TC_012 | Search Employee | Search employee record | Employee details should display | Pass |
| TC_013 | Update Employee | Edit employee information | Information should update | Pass |

# Leave Module Test Cases

| Test Case ID | Test Scenario | Test Steps | Expected Result | Status |
|---|---|---|---|---|
| TC_014 | Apply Leave | Submit leave request | Leave request should submit | Pass |
| TC_015 | Check Leave Status | View leave records | Status should display | Pass |
