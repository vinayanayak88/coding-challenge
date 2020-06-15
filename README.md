# java-interview-exercise



Build a backend service that handles simple cart handling process in an e-commerce 
application. You can also apply discounts items in the cart(This is optional. 
You may wish to do it if you like to)

The service contains 2 domain objects:

    Cart:
        sumTotal(sum of total prices of the products in the cart)
        products
        
    Product:
            name
            price
            quantity
    
# Use Cases:
(only end points are relevant)
 * user has to be able to create an empty cart
 * user has to be able to add a product to the cart
 * user has to be able to update the quantity of the product
 * user has to be able to delete the product from the cart
 * user can apply discount to the cart(* optional- please design your own domain model if you wish to do this)
 
# Technical Requirements:
Use SpringBoot to build this service. The service must run standalone and must not 
require any third party software to be installed. The service must communicate Json
over http (REST). Return proper status codes for the most common problems. 
The data does not have to be stored permanently, It may be handled in-memory 
during runtime.

# Things we are looking for
* a description how to build and use the service
* clean code
* use best practices
* structure of the project
* how you test your code


 