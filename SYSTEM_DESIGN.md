# System Design

## High-Level Architecture

    +---------------------------+
    |       User Interface      |
    | Customer / Administrator  |
    +-------------+-------------+
                  |
                  v
    +---------------------------+
    |     Application Layer     |
    | Login | Search | Booking  |
    | Payment | Admin Functions |
    +-------------+-------------+
                  |
                  v
    +---------------------------+
    |        Data Layer         |
    | Customers | Packages      |
    | Bookings  | Payments      |
    +---------------------------+

## Customer Flow

Customer → Login/Registration → Search Package → Select Package → Booking → Payment → Confirmation

## Administrator Flow

Administrator → Admin Login → Dashboard → Manage Packages / Customers / Bookings

## Main Entities
- Customer
- TravelPackage
- Booking
- Payment
- Administrator

## Relationships
- A customer can make multiple bookings.
- A travel package can have multiple bookings.
- A booking belongs to a customer and a travel package.
- A booking can have a payment record.
