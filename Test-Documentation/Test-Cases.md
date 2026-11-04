
### TC-001 Verify that the user can add one product to the cart

Scenario: TS-001

**Preconditions:**

- User is logged in successfully.
- Products page is displayed.
- Shopping cart is empty.

**Test Data:**

- Product: Sauce Labs Backpack.

**Test Steps:**

1. Locate Sauce Labs Backpack.
2. Click the Add to Cart button.
3. Click the shopping cart icon.

**Expected Result:**

- The product should be added successfully.
- The product should appear in the shopping cart.
- The cart badge should display 1.
Actual Result: To be filled during execution.

**Status:**: Not Run

### TC-002: Verify that the user can add multiple products to the cart

**Scenario ID:** TS-002

**Preconditions:**
- User is logged in successfully.
- Products page is displayed.
- Shopping cart is empty.

**Test Data:**
- Sauce Labs Backpack
- Test.allTheThings() T-Shirt (Red)
- Sauce Labs Onesie

**Test Steps:**
1. Locate Sauce Labs Backpack.
2. Click the Add to Cart button.
3. Locate Test.allTheThings() T-Shirt (Red).
4. Click the Add to Cart button.
5. Locate Sauce Labs Onesie.
6. Click the Add to Cart button.
7. Click the shopping cart icon.

**Expected Result:**
1. All three products should be added successfully.
2. All three selected products should appear in the shopping cart.
3. Each product should display the correct name and price.
4. The cart badge should display 3.

**Actual Result:** To be filled during test execution.

**Status:** Not Run

### TC-003: Verify that the added product appears in the cart with the correct name and price

**Scenario ID:** TS-004

**Preconditions:**
- User is logged in successfully.
- Products page is displayed.
- Shopping cart is empty.

**Test Data:**
- Product: Sauce Labs Backpack.

**Test Steps:**
1. Locate Sauce Labs Backpack on the Products page.
2. Note its displayed name and price.
3. Click the Add to Cart button.
4. Click the shopping cart icon.
5. Verify the product name in the cart.
6. Verify the product price in the cart.

**Expected Result:**
- The product name in the cart should match the name displayed on the Products page.
- The product price in the cart should match the price displayed on the Products page.

**Actual Result:** To be filled during execution.

**Status:** Not Run
