# Checklist for Checkout Process	
## Functional testing(positive)	
* Click Checkout from cart page. Verify that checkout information form opens. There is no navigation error.
## Functional testing(positive)	
* Click Checkout from cart page. Enter valid First Name, Last Name, Zip Code. Click Continue. Verify that Checkout overview page opens. Should not happen: Form submission fails
## Functional testing(positive)	
* Open checkout overview page. Verify that selected products, prices and total are displayed. There are no missing product or incorrect price.
## Functional testing(negative)
* Click Checkout from cart page. Leave fields empty. Click Continue. Verify that error message appears "Error: First Name is required". Should not happen: checkout proceeds.
## Functional testing(negative)	
* Open checkout overview page without adding the products. Clicl "Checkout" with empty cart. Verify that checkout should not proceed
