# Admin Dashboard

## Purpose
The Admin Dashboard provides authorized administrators with controls for managing the tourism system.

## Functions
- View package information
- Add travel package
- Update travel package
- Delete travel package
- View customers
- View bookings
- Monitor payment status

## Admin Access Flow
Admin Login → Credential Validation → Admin Dashboard

Invalid credentials → Access Denied

## Security Rules
- Only authorized administrators can access admin functions.
- Customer accounts must not use administrator functions.
- Sessions should be protected.
- Sensitive information should be handled securely.

## Expected Result
The administrator can manage tourism-system data from one dashboard while unauthorized users are denied access.
