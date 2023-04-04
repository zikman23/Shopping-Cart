# restock-shopping-cart

Module 19 - Shopping Cart Exercise - Refactor with Restocking Functionality

## Project Overview

Shopping cart exercise from Module 19.

Basic functionality includes adding and removing products from your shopping cart. 

Application has been refactored to include additional features, including: 
- Resetting the stock by making a call to a Strapi API to get a fresh list of available products.

Here’s how the reset stock feature works:

- There’s an input field on the page that contains the URL to the Strapi back end
- When a user clicks the “ReStock Products” button, a call is made to the Strapi back end specified in the input field, using "doFetch" function.
- The result of this call is an updated list of products

## How to Run

1. Navigate to project root in terminal
2. run http-server
3. open the localhost server on your preffered browser

## Improvements 

- Styling improvements to follow. 

## Technologies Used

- React, Javascript, CSS, HTML
- Bootstrap 

## License

[MIT License](LICENSE)
