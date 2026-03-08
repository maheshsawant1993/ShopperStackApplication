# ShopperStackApplication

BDD Test Scenario – End-to-End Purchase Flow

This project includes an automated Behavior Driven Development (BDD) test scenario that 
validates the end-to-end purchase flow of the ShopperStack application. The test ensures that 
a registered user can successfully log in, search for a product, add it to the cart, initiate the 
purchase process, and log out of the application.


Flow 
Login → Search Product → Add to Cart → Buy Now → Logout

1. login page
2. Product page(search product,add product to cart)
3. cart page
4. Logout page


Scenario: User creates an account, logs in, searches for a product, buys it, and logs out
Given User navigates to "https://shoppersstack.com/"
And the user clicks on the "Login" button
And User enters username "sojan99@gmail.com" and password "Sojan@1234"
And the user clicks on the Login button
And the user logs in with the registered credentials
And the user searches for a valid product
And the user adds the product to the cart
And the user clicks on the Buy Now button
Then the order process should be initiated successfully
And the user logs out successfully
And the user should be redirected to the login page again




