
# Test Cases — E-commerce Website

## Module: Shopping Cart

### TC-001: Add a product to the shopping cart

**Preconditions:**
- The user opens the e-commerce website.
- At least one product is available.

**Steps:**
1. Open the product page.
2. Click the "Add to Cart" button.
3. Open the shopping cart.

**Expected Result:**
- The product is successfully added to the shopping cart.
- The product name, price, and quantity are displayed correctly.

### TC-002: Remove a product from the shopping cart

**Preconditions:**
- The shopping cart contains at least one product.

**Steps:**
1. Open the shopping cart.
2. Click the "Remove" button next to the product.

**Expected Result:**
- The product is removed from the shopping cart.

### TC-003: Update product quantity

**Preconditions:**
- The shopping cart contains a product.

**Steps:**
1. Open the shopping cart.
2. Change the product quantity to 2.
3. Update the quantity.

**Expected Result:**
- The product quantity is updated to 2.
- The total price is recalculated correctly.

### TC-004: Verify the shopping cart total

**Preconditions:**
- The shopping cart contains at least one product.

**Steps:**
1. Open the shopping cart.
2. Check the product price and quantity.
3. Verify the total amount.

**Expected Result:**
- The total amount is calculated correctly based on product prices and quantities.

### TC-005: Add multiple products to the shopping cart

**Preconditions:**
- At least two products are available.

**Steps:**
1. Open the first product page.
2. Click "Add to Cart".
3. Open another product page.
4. Click "Add to Cart".
5. Open the shopping cart.

**Expected Result:**
- Both products are displayed in the shopping cart.
- Product details and prices are correct.
