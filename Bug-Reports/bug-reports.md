
# Bug Reports — E-commerce Website

These are practice examples of bug reports created for QA portfolio purposes.

## BR-001: Registration form accepts an invalid email address

**Environment:**
- Browser: Google Chrome
- OS: Windows 11
- Application: E-commerce website

**Preconditions:**
- The user is on the registration page.

**Steps to Reproduce:**
1. Open the registration page.
2. Enter `testemail` in the Email field.
3. Enter a valid password.
4. Click the Register button.

**Actual Result:**
The registration form accepts an invalid email address.

**Expected Result:**
The system should display a validation message and prevent registration with an invalid email address.

**Severity:** Major

---

## BR-002: Product quantity is not updated in the shopping cart

**Environment:**
- Browser: Google Chrome
- OS: Windows 11
- Application: E-commerce website

**Preconditions:**
- The shopping cart contains at least one product.

**Steps to Reproduce:**
1. Open the shopping cart.
2. Change the product quantity from 1 to 2.
3. Check the displayed quantity and total price.

**Actual Result:**
The displayed quantity remains 1.

**Expected Result:**
The product quantity should be updated to 2 and the total price should be recalculated.

**Severity:** Major

---

## BR-003: Removed product remains visible in the shopping cart

**Environment:**
- Browser: Google Chrome
- OS: Windows 11
- Application: E-commerce website

**Preconditions:**
- The shopping cart contains at least one product.

**Steps to Reproduce:**
1. Open the shopping cart.
2. Click the Remove button next to a product.
3. Check the shopping cart contents.

**Actual Result:**
The removed product is still displayed in the shopping cart.

**Expected Result:**
The removed product should disappear from the shopping cart.

**Severity:** Major
