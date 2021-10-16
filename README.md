# drupal8
We wants to build ecommerce portal using Drupal 8. To sell products only on their mobile app.This website has just a listing of their products.

Each product page shows:

The product title
An Image
Product Description
App Purchase Link (Just a simple http link, don't let the word app confuse you.)

Instead of displaying the 'App Purchase Link' on the site on the product page, display the link as a QR code, such that the site visitors can quickly open the product on the XYZ app on their mobile.

We have to build custom module using GPL lib to fulfill below requirement:

- A Drupal content type to hold all their products
- A Drupal block that can be placed on any product page
- The block, when placed on any product page, automatically shows the currently displayed product's App Purchase Link as a QR code, that the site  visitors can scan using their mobile.
