# Checklist for add to cart functionality	
## Functional testing(positive)	
* Log in with valid credentials. Open the Products page. Click Add to cart on any product. Verify that product is added to cart and on the card icon appears image with amount of added items. Page shouldn't reload unexpectedly and button is clickable.
## Functional testing(positive)	
* Log in with valid credentials. Open the Products page. Click Add to cart on any product. Verify that cart icon shows correct number of added items. Should not happen: counter on the card icon doesn't update.
## Functional testing(positive)	
* Log in with valid credentials. Open the Products page. Click Add to cart on any product. Click card icon. Verify that cart page opens with added items. Should not happen: empty cart after items were added to the card.
## Functional testing(positive)	
* Log in with valid credentials. Open the Products page. Click on the product image or product name. Verify that product details page opens. Should not happen: broken link, navigation error, blank page.
## Functional/UI/UX testing(positive)	
* Log in with valid credentials. Open the Products page. Click Add to cart on any product. Verify that button text changes from "Add to cart" to "Remove". Should not happen: Button remains unchanged.
## Functional/UI/UX testing(positive)	
* Log in with valid credentials. Open the Products page. Click Add to cart on any product. Button text changes from "Add to cart" to "Remove". Click "Remove" button. Verify that button text changes from "Remove" to "Add to cart". Should not happen: Button remains unchanged, product remains in cart.

