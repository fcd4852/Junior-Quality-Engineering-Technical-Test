# Acceptance Tests Pet Store

These tests validate that the Pet Store application meets the critical user needs from a business perspective. They represent **end-to-end workflows** rather than isolated functions.

---

## AT01 Successful Purchase Flow
**Given** a registered user is logged in  
**When** the user searches for a product, adds it to the cart, and completes checkout with valid payment details  
**Then** the system confirms the order and displays an order ID  

---

## AT02 New User Registration
**Given** a visitor has no existing account  
**When** the visitor registers with valid details  
**Then** the system creates the account and allows login with the new credentials  

---

## AT03 Login and Logout
**Given** a registered user exists  
**When** they log in with valid credentials and then log out  
**Then** the system grants access after login and securely ends the session on logout  

---

## AT04 Invalid Login Attempt
**Given** a registered user exists  
**When** they enter an invalid password  
**Then** the system prevents login and displays an error message  

---

## AT05 Product Search
**Given** the catalog is populated with products  
**When** the user searches for a valid keyword (e.g., "fish")  
**Then** the system returns a list of relevant products  
**And** if no match is found, displays “No products found.”  

---

## AT06 Cart Management
**Given** a user has items in their cart  
**When** they remove a product  
**Then** the cart updates and reflects the correct total  
