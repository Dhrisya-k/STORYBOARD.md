# Requirements Specification

## Functional Requirements
- FR1: The system shall allow new customers to create an account.
- FR2: The system shall authenticate registered customers.
- FR3: The system shall display available travel packages.
- FR4: Customers shall be able to search packages by destination or criteria.
- FR5: Customers shall be able to book an available package.
- FR6: Customers shall be able to cancel eligible bookings.
- FR7: The system shall process valid payment information.
- FR8: Administrators shall be able to add, update and delete packages.
- FR9: Administrators shall be able to manage customer information.
- FR10: Administrator functions shall be restricted to authorized users.

## Non-Functional Requirements
- Usability: simple and understandable interface.
- Performance: normal operations should respond quickly.
- Security: credentials and payment information must be protected.
- Reliability: booking information should be stored consistently.
- Maintainability: modules should be separated for easier updates.
- Availability: authorized users should be able to access the system during normal operation.

## Actors
| Actor | Responsibilities |
|---|---|
| Customer | Register, login, search, book, cancel, pay |
| Administrator | Manage packages, customers and bookings |
