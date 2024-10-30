# "Cart" functionality
  
 ## Description: As an online store customer, I want to be able to add products to my cart so that I can purchase the products I am interested in.
   ### Acceptance criteria:
    1. Adding a product to the cart is possible from the Product Card by clicking the “Add to cart” button. This is the only way to add a product to the cart. 
    2. The functionality of adding a product to the cart is available in desktop and mobile view mode. 
    3. The screen preceding the screen informing about adding a product to the cart is the screen of currently available discounts for the selected product. 
    4. The “Product added to cart” screen displays information about the products in the cart (product name, price) and the total number of products in the cart. 
    5. There are 3 interaction options on the “Product added to cart” screen: 
      a. "Return to shopping" button
      b. "Go to cart" button
      c. “X” button closing the screen
    6. After selecting the “Close screen” option, the user remains on the Product Card page. 
    7. After selecting the “Return to shopping” option, the user is redirected to the home page (redirection takes place in the same tab).
    8. After selecting the "Go to cart" option, the user is redirected to the Cart.

##  Description: As a customer, I want to have access to the Shopping Cart so that I can edit its content and/or finalize my purchase.
  ###  Acceptance criteria: 
    1. The cart screen contains information about the next steps that complete the order: graphical visualization showing the stages,
      icons of the cart, deliveries, payments.
    2. The current ordering step is highlighted from the others.
    3. A single item of the product list on the cart screen consists of: 
      a. linked product name with a product image 
      b. product price
      c. number of products 
      d. value of products 
      e. "delete" button referring to a single product
    4. The "number" field is editable. 
    5. Editing the number of products in the cart is done in two ways: 
      a. manually entering a value for the "number" field
      b. using the "up" or "down" arrow buttons to change the field by +1 or -1
    6. Changing the number of products in the cart leads to an update of the product value and the total value of the cart. 
    7. The "number" field accepts only values ​​from the range of integers, additionally:
      a. the number is a maximum of 3 digits = 1-999 
      b. letters, special characters cannot be entered
    8. Removing a product from the cart is confirmed by an appropriate "toast message":
      a. toast message located at the top of the screen; it is represented by white lettering on a red background
      b. text "Product removed from cart" 
      c. toast display time: 3 seconds / disappears automatically when the time is up
      d. no "X" button to close the toast 
    9. The cart has a limit on the total value of products in the cart:
      a. amount limit: PLN 40,000 
      b. quantity limit: 15 products 
      c. the quantity limit applies to 15 different products 
    10. The customer is informed about exceeding the Cart value limit with an appropriate message:
      a. orange toast message located at the top of the screen 
      b. text “Value limit exceeded”
      c. toast display time: 3 seconds / disappears automatically when the time is up
      d. no "X" button to close the toast 
      e. attempt to exceed the limit is blocked
    11. The customer is informed about exceeding the limit of the number of products in the Cart with an appropriate message on the Product Card screen:
      a. orange toast message located at the top of the screen
      b. text “Products limit exceeded” 
      c. toast display time: 3 seconds / disappears automatically when the time is up
      d. no "X" button to close the toast 
      e. attempt to exceed the limit is blocked

## Description: As a customer, I want to be able to move products from the cart to the "Saved" section, so that I can make a purchase decision at a later time.
  ### Acceptance criteria:
    1. The "Move product to saved" button is located under the name of a given product in the Cart. 
    2. The ability to move a product to the "Saved" section is possible for both logged-in and non-logged-in users. "Saved" section life cycle for an unlogged user is 24h 
    3. After moving a product to the "Saved" section, the product is automatically removed from the Cart.
    4. The "Saved" section is located on the top navigation bar to the left of the Cart icon.

## Description: As a customer, I want to be charged free shipping above a certain order value so that the value of my purchases is rewarded.
  ### Acceptance criteria:
    1. Free shipping is charged from the total Cart value above PLN 500. 
    2. The customer is informed about the free shipping charge with an green toast message:
      a. toast message located at the top of the screen 
      b. text "You get free shipping" 
      c. toast display time: 3 seconds / disappears automatically when the time is up
      d. no "X" button to close the toast

## Description: As a customer, I want to be able to share my Cart, to pass on the configuration of my cart to another customer.
  ### Acceptance criteria:
    1. The "Share your cart" button is located at the bottom of the list of products in the Cart. 
    2. After clicking the cart sharing button, the user is redirected to the Cart sharing screen. 
    3. Cart sharing is done in two modes:
      a. public offer 
      b. private offer 
    4. In the “Public offer” mode, a link to the shared Cart is generated. 
    5. The link to the shared Cart can be passed on in 3 ways: 
      a. by copying it to the clipboard 
      b. sending by e-mail 
      c. sharing via Messenger (Messanger button redirecting to the application and selecting a person from the contact list) 
    6. Clicking the “Back to cart” button moves the customer from the shared cart screen to the classic cart screen.

## Description: As a customer, I want to be able to choose a delivery and payment method so that I can decide how to fulfill my order.
  ### Acceptance criteria:
    1. Selecting "Continue" takes the user to the delivery and payment method selection screen.
