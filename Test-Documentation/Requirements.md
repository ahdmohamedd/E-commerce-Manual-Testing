# E-commerce Application – Requirements Document

## 1. Project Overview
This project aims to test the main functionalities of an e-commerce web application, including user authentication, product browsing, shopping cart management, and checkout.

## 2. Functional Requirements

### User Authentication

**REQ-001: Valid Login**
The system shall allow registered users to log in using valid credentials.

**REQ-002: Invalid Login**
The system shall prevent users from logging in with invalid credentials and display an appropriate error message.

**REQ-003: Logout**
The system shall allow logged-in users to log out successfully.

### Product Catalog

**REQ-004: View Products**
The system shall display the available products with their names, prices, and images.

**REQ-005: Sort Products**
The system shall allow users to sort products by:
- Name (A to Z)
- Name (Z to A)
- Price (Low to High)
- Price (High to Low)

### Shopping Cart

**REQ-006: Add Products to Cart**
The system shall allow users to add products to the shopping cart.

**REQ-007: Remove Products from Cart**
The system shall allow users to remove products from the shopping cart.

**REQ-008: Cart Information**
The system shall display the correct product information in the shopping cart, including product name and price.

**REQ-009: Cart Updates**
The system shall update the cart item count when products are added or removed.

### Checkout

**REQ-010: Checkout Process**
The system shall allow users to proceed through the checkout process and complete an order.

**REQ-011: Checkout Information Validation**
The system shall validate required customer information before allowing the user to continue.

**REQ-012: Order Confirmation**
The system shall display an order confirmation after successful checkout.

## 3. Notes and Assumptions
- These requirements are training requirements based on the SauceDemo application.
- They are not official client-approved requirements.
- Any behavior not explicitly specified should be recorded as an assumption or clarification request.
- Additional exploratory tests may be performed to identify unexpected behavior.
