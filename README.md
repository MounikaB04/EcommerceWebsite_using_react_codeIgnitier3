# EcommerceWebsite_using_react_codeIgnitier3

Project Overview

Developed a basic eCommerce website where users can browse products, add them to a cart, and complete a purchase. The project will have a React frontend, a CodeIgniter backend API, and MySQL database. Tailwind or Bootstrap will be used for styling, and free templates are encouraged to keep the design attractive and mobile-friendly.
Key Features
1. User Roles

    Guest User: Can view products, categories, and search.
    Registered User: Can add products to cart, checkout, and view order history.
    Admin: Can manage products and view orders.

2. User Authentication

    Login/Register: Simple email and password-based login and registration.
    Admin Access: Admin role should have access to product management and order views.

3. Product Management (Admin)

    Add/Edit Products: Admin can add new products and edit existing ones (only basic fields like name, price, and description).
    View Orders: Admin can view a list of orders placed by users.

4. Product Catalog

    Product Listing: Display a list of products with essential information (name, price, image).
    Product Detail Page: Show product details on a separate page (description, larger image).
    Search: Basic search bar to find products by name.

5. Shopping Cart

    Add to Cart: Allow users to add items to their cart.
    View/Edit Cart: Users can view cart items, adjust quantities, and remove items.

6. Checkout

    Order Summary: Display a simple summary of items items ordered by the user in apdf format and also admin can see the all the orders done by the users in pdf and excel format and admin also can see a individual order in pdf format.

7. Payment
	
	I have used the RazorPay for completing the purchase and after the payment it update the orders table as it loads the payment method and payment status update from pending to completed.


Steps to connect:

step1: https://kinsta.com/knowledgebase/install-react/ go through this url to download the react app in (windows/linux)
step2: https://www.codeigniter.com/ to download a codeIgniter3
step3: open the application folder 
step4: open the application/config.php file add the base_url of your project
step5: open the application/database.php connect through your database created in the XAMPP server
step6: To run the react app use the command $npm start. 
