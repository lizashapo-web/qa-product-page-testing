# Test Session Report — “Men’s Polo Shirt” Product Page

# Environment
- Device: PC
- OS: Windows 10
- Browser: Opera
- Page: “Men’s Polo Shirt” product page

# Scope
- Shopping cart
- Product information
- Product photos
- Reviews
- Favorites
- Color and size

# Out of scope
- Registration
- Payment
- Shipping
- Login

## Checklist

# General Information
1. Verify that the product page loads. — Passed
2. Verify that the product price is displayed on the page. — Passed
3. Verify that the product name is displayed on the page. — Passed

# Product Photo
4. Verify that the product photo is displayed on the page. — Passed
5. Verify that the product photo opens in an enlarged view. — Passed
6. Verify that the product photo can be closed. — Passed

# Color and Size
7. Verify that the product image changes when the product color is changed. — Passed
8. Verify that the product size selection is displayed on the page. — Passed
9. Verify that the product color selection is displayed on the page. — Passed
10. Verify that a product cannot be added to the cart without selecting a size. — Blocked  
Comment: A product size is selected by default; there is no way to reset the size selection.

# Cart
11. Verify that the “Add to Cart” button is displayed on the page. — Passed
12. Verify that a notification appears when a product is added to the cart. — Failed  
Comment: No notification appears after adding a product to the cart.
13. Verify that the product’s size, color, quantity, and price are displayed correctly in the cart. — Passed
14. Verify that the item can be removed from the cart. — Passed

# Bugs found
1. BUG-001: The notification that the item has been added to the cart does not appear after clicking the “Add to Cart” button.

# Summary
During the test session, the “Men’s Polo Shirt” product page was tested .

Most of the main functions work correctly: the page opens, the photo is displayed, size and color can be selected, and the item can be added to and removed from the cart.

One bug was found. One test was blocked: it is impossible to test adding an item without selecting a size, since a size is selected by default.