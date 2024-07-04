Full-Stack E-Commerce Application
Overview
This project is a basic e-commerce application with user authentication, product listing, and a shopping cart. It demonstrates proficiency in both frontend and backend development.

Features
Backend (Node.js and Express)
User Authentication:

POST /register: Register a new user.
POST /login: Authenticate a user and return a JWT.
Product Management:

GET /products: Retrieve a list of products.
GET /products/:id: Retrieve details of a specific product.
POST /products: Add a new product (admin only).
PUT /products/:id: Update an existing product (admin only).
DELETE /products/:id: Delete a product (admin only).
Shopping Cart:

GET /cart: Retrieve the user's shopping cart.
POST /cart: Add an item to the cart.
DELETE /cart/:id: Remove an item from the cart.
Frontend (React)
Components:

AuthForm: Registration and login forms.
ProductList: Display a list of products.
ProductDetail: Display details of a selected product.
Cart: Display the user's shopping cart and allow item removal.
State Management: Use Redux for managing user authentication state and shopping cart state.

Routing: Use React Router to navigate between pages (e.g., home, product details, cart, login).

Additional Features
Order Management (Optional): Users can place orders, view order history, and order details.
Product Search and Filtering (Optional): Search products by name and filter by category or price.
Persistent Storage (Optional): Save the user's cart to local storage to persist across sessions.
Setup Instructions
Backend
Clone the repository.
Install dependencies: npm install.
Set up MongoDB and configure the database connection.
Run the backend server: npm start.
Frontend
Navigate to the client directory.
Install dependencies: npm install.
Start the React app: npm start.
Usage
Register a new user or log in with existing credentials.
Browse products, view details, and add items to your cart.
Admin users can add, update, or delete products.
View and manage the shopping cart.
Technologies Used
Backend: Node.js, Express, MongoDB.
Frontend: React, Redux, React Router.
