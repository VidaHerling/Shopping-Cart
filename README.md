# Shopping Cart

## Description
Refactor the shopping cart to include the following functionalities:
1. Import new photos from picsum (generate a random new picture for each item each time the page is refreshed)
2. List the price and stock of each item
3. Reduce the stock each time an item is add to the shopping cart
4. Build the delete functionality: delete an item from the shopping cart will add the stock back to the item list
5. Click the Restocking button will add new items to the list (from strapi database)

## How to run
- download the files to your local machine.
- run http-server -c-1 in the folder of the files
- install Strapi (https://strapi.io/) in your local folder
- run "npm run develop" in your terminal to start localhost:1337  
- access the index.html on localhost:8080 to test the functionalities
** note: I still need to figure out how users can access my Strapi database to test the restocking functionality.

## Future improvement
1. Restocking function: Instead of adding new duplicate items, we would like to update the stock of the existing items (or add new itmes that is not currently on the list)
2. Checkout function: When Checkout button is click, the cart will be clear and the stocks of the items are permenantly removed. 
