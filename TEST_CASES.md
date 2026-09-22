# Test Cases

## Travel Agency / Tourism Management System

| ID | Module | Test Scenario | Test Data / Action | Expected Result |
|---|---|---|---|---|
| TC01 | Registration | Valid registration | Enter valid customer details | Account is created |
| TC02 | Registration | Invalid registration | Leave required fields empty | Validation error is displayed |
| TC03 | Login | Valid login | Enter correct credentials | Customer is logged in |
| TC04 | Login | Wrong password | Enter incorrect password | Login is rejected |
| TC05 | Packages | View packages | Open package list | Available packages are displayed |
| TC06 | Search | Search destination | Search for Goa | Matching packages are displayed |
| TC07 | Booking | Book available package | Select available package | Booking is created |
| TC08 | Booking | Book unavailable package | Select unavailable package | Booking is rejected |
| TC09 | Booking | Cancel booking | Cancel existing booking | Booking is cancelled |
| TC10 | Admin | Add package | Enter valid package data | Package is added |
| TC11 | Admin | Update package | Change package details | Package is updated |
| TC12 | Admin | Delete package | Delete existing package | Package is deleted |
| TC13 | Payment | Valid payment | Enter valid payment information | Payment is confirmed |
| TC14 | Payment | Invalid payment | Enter invalid payment information | Payment is rejected |
| TC15 | Security | Unauthorized admin access | Open admin page without authorization | Access is denied |

## Test Result Template

| Test ID | Actual Result | Status |
|---|---|---|
| TC01-TC15 | Record during execution | Pending |

## Testing Notes
Test normal cases, invalid input, authorization, booking availability and payment outcomes.
