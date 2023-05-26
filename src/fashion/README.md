# Fashion Guru

## FE Changes:
1. take a text as input which pertains to the user query
2. display 1 column and three rows for top, bottom, accessory which describes a given outfit suggestion given by the backend
3. create a horizontal scroll to alternate between choices amongst top (and similarly for bottom and accessory) for a given outfit idea
4. create a vertical scroll to alternate between different outfit ideas
5. create a render box to display the mini details of the product and allows the user to visit the product or bookmark it in its shopping list.

## BE Changes:
1. create outfit ideas repository layer which given a user query suggests various outifts
2. create product repository layer which given the item description for the outfit ideas fetch matching products from google shopping
3. integrate google auth screen and allow user to add the products in their outfit list
