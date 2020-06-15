# java-interview-exercise

Build backend services that handles simple cart handling process in an e-commerce application.

# The domain objects:

    Cart:
        totalPrice (sum of total prices of the products in the cart)
        items
        
    Item:
        product
        quantity
        
    Product:
            name
            price
            
# The micro services:
* CartService (responsible for the domain objects: Cart + Item)
* ProductService (responsible for the domain object: Product)

# Use Cases:
(Provide implementation to the following end-points)
 * basic CRUD operations for Product
 * basic CRUD operations for Cart
 * basic CRUD operations for a cart Item, but an item cannot exist without a cart and once you create an item you can only update its quantity, not the product
 
# Technical Requirements:
Use SpringBoot to build this. The services must run standalone and must not 
require any third party software to be installed. The services must communicate Json
over http (REST). Return proper status codes for the most common problems. 
The data can be stored in in-memory db.

# Things we are looking for
* a description how to build and use the service
* clean code
* use of best practices
* structure of the project
* tests for your code


 
