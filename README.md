# java-interview-exercise

Build backend services that handles simple cart handling process in an e-commerce 
application.

The services contains 2 domain objects:

    Cart:
        sumTotal(sum of total prices of the products in the cart)
        items
        
    Item:
        productId
        quantity
        
    Product:
            name
            price
            
# Build 2 micro services:
* Cart + Item
* Product

# Use Cases:
(Provide implementation to the following end-points)
 * user has to be able to create an empty cart
 * user has to be able to add a product to the cart
 * user has to be able to update the quantity of the product
 * user has to be able to delete the product from the cart


 
# Technical Requirements:
Use SpringBoot to build this service. The services must run standalone and must not 
require any third party software to be installed. The services must communicate Json
over http (REST). Return proper status codes for the most common problems. 
The data can be stored in in-memory db.

# Things we are looking for
* a description how to build and use the service
* clean code
* use best practices
* structure of the project
* how you test your code


 
