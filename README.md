Node.js E-commerce App with MongoDB

This is a Node.js application that provides basic e-commerce functionality, including user authentication (login and register), product management (add, update, view), user profile management, shopping cart functionality, and order placement. The application uses a MongoDB database for storing data and uses the EJS templating engine for the frontend.

Prerequisites
Before running the application, make sure you have the following prerequisites installed on your system:

Node.js (v12 or higher)
MongoDB
Docker (optional)

Installation
1- Clone the repository or download the source code: git clone https://github.com/AhmedKhaleda998/Shop-App
2- Navigate to the project directory: cd Shop-App
3- Install the dependencies: npm install
4- Build and run the application: node app.js
5- The application will be accessible at http://localhost:8888

Usage

Register
Visit http://localhost:8888/signup to create a new user account.
Fill in the required information (username, email, password), and click on the "Register" button.
Upon successful registration, you will be redirected to the login page.

Login
Visit http://localhost:8888/login to log in to your account.
Enter your credentials (username/email and password), and click on the "Login" button.
Upon successful login, you will be redirected to the home page.

Home Page
The home page displays a list of products available for purchase.
You can view the details of each product by clicking on its title or image.
The products can be filtered by price using the provided filter options.

Profile Page
After logging in, you can visit http://localhost:8888/admin/profile to view and update your user profile.
The profile page displays your username, email address, and other details.
You can edit your profile information and save the changes.

Shopping Cart
While browsing the products, you can add items to your shopping cart.
Click on the "Add to Cart" button on a product page to add it to your cart.
The shopping cart icon in the navigation bar displays the current number of items in your cart.
Visit http://localhost:8888/cart to view the contents of your cart.
You can remove items from the cart or proceed to place an order.

Place Order
On the shopping cart page, click on the "Place Order" button to proceed with the checkout process.
Enter the required shipping details and confirm the order.
Upon successful order placement, you will receive a confirmation message.

Search
The application allows you to search for products based on their title or description.
Use the search bar provided in the navigation to enter your search query.
The search results will be displayed on a separate page.

Dockerization
The application can be easily containerized using Docker and Docker Compose. To build and run the application with Docker, follow these steps:
Install Docker on your system.

Open a terminal, navigate to the project directory, and run the following command to start the application using Docker Compose:
$ docker-compose build
$ docker-compose up -d
$ docker-compose logs api
The application will be accessible at http://localhost:8888
