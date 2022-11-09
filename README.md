# Cart Restock

In this exercise, the user can take items from the <i>virtual shelf</i> (items in stock as generated from Strapi API) simply by clicking on the item's <b>submit</b> button. As the user's cart fills will items, their total will change accordingly. If the user decides to remove items from their cart, the item will return to the <i>virtual shelf</i>. The amount <b>instock</b> of any particular item will depend on how many of that item are in the cart. 

When the items instock are zero, the user can restock the items back to the orginial amount by clicking the <b>restock</b> button next to the API url at the bottom of the browser page.

## Cart.jsx

The <b>cart.jsx</b> file is where all of the magic happens. Specifically note the functions <i>addToCart()</i> and <i>deleteCartItem</i> as they change the total amount of items in stock. 

## Moving Forward

I would like to improve upon the project by allowing the user to restock specific amounts of in stock items as opposed to generating the same object properties. Furthmore, it would be interesting to add more features such as <i>wishlists</i>.
