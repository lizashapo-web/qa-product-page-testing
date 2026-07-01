# Test Cases — “Men’s Polo Shirt” Product Page

## TC-001: Verifying Removal of an Item from the Cart

# Preconditions
1. The “Men’s Polo Shirt” item has been added to the cart.
2. The cart page or tab is open.
3. The “Men’s Polo Shirt” item is displayed in the cart.
4. The “Remove from Cart” button is displayed in the cart.

# Steps
1. Click the “Remove from Cart” button in the cart.
2. Confirm the removal if a confirmation window appears.

# Expected result
The “Men’s Polo Shirt” item is removed from the shopping cart.  
The item is no longer displayed in the shopping cart.  
If this was the only item in the shopping cart, a message indicating that the shopping cart is empty is displayed.


## TC-002: Verify that an empty review cannot be submitted

# Preconditions:
1. The “Men’s Polo Shirt” product page is open.
2. The page contains a “Reviews” tab or section.
3. The “Reviews” tab or section is open.
4. The form for adding a review is displayed.
5. The form contains a field for entering review text and a submit button.

# Steps:
1. Leave the review text field blank.
2. Do not enter a rating if a rating is required.
3. Click the submit button.

# Expected result:
The review is not submitted.
An error message appears, or the required fields are highlighted.
The user remains on the review submission form.
An empty review is not displayed in the list of reviews.


## TC-003: Verifying the Opening and Closing of an Enlarged Product Image

# Preconditions:
1. The “Men’s Polo Shirt” product page is open.
2. The product image is displayed on the page.
3. The product image is clickable.

# Steps:
1. Click on the product image.
2. Verify that the image opens in enlarged view.
3. Click the close button or click outside the image window, if closing in this way is supported.

# Expected result:
After clicking on the product image, it opens in enlarged view.
The enlarged image displays correctly.
After pressing the close button or clicking outside the window, the enlarged image closes.
The user returns to the “Men’s Polo Shirt” product page.
The product page does not reload and displays correctly.