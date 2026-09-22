# Booking Management

## Purpose
Booking Management allows customers to reserve available travel packages and manage their bookings.

## Booking Flow
Customer Login → Select Package → Check Availability → Enter Booking Details → Confirm Booking → Payment → Booking Confirmation

## Booking Information
- Booking ID
- Customer ID
- Package ID
- Booking date
- Number of travelers
- Total amount
- Booking status

## Cancellation
1. Customer opens booking history.
2. Selects an active booking.
3. Requests cancellation.
4. System validates the request.
5. Booking becomes cancelled when allowed.

## Validation
- Customer must be logged in.
- Package must be available.
- Number of travelers must be valid.
- Cancelled bookings must not remain active.

## Expected Result
Valid bookings are created and recorded, while invalid or unavailable bookings are rejected.
