# Travel Agency Management System — GitHub Storyboard

## 🎯 Project Story

**Problem:** Customers need an easy way to discover travel packages, make bookings and complete payments, while administrators need to manage packages and bookings.

**Goal:** Develop a simple Tourism Management / Travel Agency system with separate customer and admin functions.

---

## 🧩 Storyboard — Development Journey

| Stage | Story / Task | GitHub Issue | Status |
|---|---|---:|---|
| 1 | Identify the tourism-management problem | #1 | ✅ Done |
| 2 | Collect and analyze system requirements | #2 | ✅ Done |
| 3 | Design the system, actors and data flow | #3 | ✅ Done |
| 4 | Build customer registration and login | #4 | 🔄 In Progress |
| 5 | Create and manage travel packages | #5 | 🔄 In Progress |
| 6 | Allow customers to search packages | #6 | 🔄 In Progress |
| 7 | Implement package booking | #7 | ⏳ To Do |
| 8 | Implement payment processing | #8 | ⏳ To Do |
| 9 | Build the administrator dashboard | #9 | ⏳ To Do |
| 10 | Test all major functions | #10 | ⏳ To Do |
| 11 | Complete project documentation | #11 | ⏳ To Do |

---

## 🗺️ Story Flow

```
┌──────────────────────┐
│ 1. Problem           │
│ Identification       │
└──────────┬───────────┘
           ↓
┌──────────────────────┐
│ 2. Requirement       │
│ Analysis              │
└──────────┬───────────┘
           ↓
┌──────────────────────┐
│ 3. System Design     │
└──────────┬───────────┘
           ↓
┌──────────────────────┐
│ 4. Customer          │
│ Management            │
└──────────┬───────────┘
           ↓
┌──────────────────────┐
│ 5. Travel Package    │
│ Management            │
└──────────┬───────────┘
           ↓
┌──────────────────────┐
│ 6. Package Search    │
└──────────┬───────────┘
           ↓
┌──────────────────────┐
│ 7. Booking           │
│ Management            │
└──────────┬───────────┘
           ↓
┌──────────────────────┐
│ 8. Payment           │
│ Management            │
└──────────┬───────────┘
           ↓
┌──────────────────────┐
│ 9. Admin Dashboard   │
└──────────┬───────────┘
           ↓
┌──────────────────────┐
│ 10. Testing          │
└──────────┬───────────┘
           ↓
┌──────────────────────┐
│ 11. Documentation    │
└──────────────────────┘
```

---

## 👥 User Stories

### Customer
- As a customer, I want to register and log in so that I can use the travel system.
- As a customer, I want to search travel packages so that I can find suitable destinations.
- As a customer, I want to view package details so that I can choose a trip.
- As a customer, I want to book a package so that I can reserve my trip.
- As a customer, I want to make a payment so that my booking can be confirmed.

### Administrator
- As an administrator, I want to add travel packages so that customers can see new trips.
- As an administrator, I want to update package details so that information stays current.
- As an administrator, I want to delete packages so that unavailable trips are removed.
- As an administrator, I want to manage bookings so that customer reservations can be monitored.

---

## 📊 Current Progress

### ✅ DONE
- #1 Problem Identification
- #2 Requirement Analysis
- #3 System Design

### 🔄 IN PROGRESS
- #4 Customer Management
- #5 Travel Package Management
- #6 Package Search

### ⏳ TODO
- #7 Booking Management
- #8 Payment Management
- #9 Admin Dashboard
- #10 Testing
- #11 Documentation

---

## 🔄 Development Workflow

**Problem Identification → Requirements → Design → Development → Testing → Documentation**

Each GitHub Issue represents one development task. The issue can be moved from **To Do → In Progress → Done** as the work is completed.

---

## 🧪 Test Case Storyboard

| ID | Module | Test | Expected Result |
|---|---|---|---|
| TC01 | Registration | Valid customer details | Account created |
| TC02 | Registration | Invalid/empty details | Validation error shown |
| TC03 | Login | Valid credentials | Customer logged in |
| TC04 | Login | Wrong password | Login rejected |
| TC05 | Packages | View packages | Available packages shown |
| TC06 | Packages | Search destination | Matching packages shown |
| TC07 | Booking | Book available package | Booking created |
| TC08 | Booking | Book unavailable package | Booking rejected |
| TC09 | Booking | Cancel existing booking | Booking cancelled |
| TC10 | Admin | Add package | Package added |
| TC11 | Admin | Update package | Package updated |
| TC12 | Admin | Delete package | Package deleted |
| TC13 | Payment | Valid payment details | Payment confirmed |
| TC14 | Payment | Invalid payment details | Payment rejected |
| TC15 | Security | Access admin page without login | Access denied |

---

## 🏁 Completion Goal

The storyboard is complete when all 11 GitHub Issues have moved to **DONE** and the test cases have been executed successfully.
