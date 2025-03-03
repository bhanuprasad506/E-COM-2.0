# Ecommerce Applications

## Milestone 1: Project Overview
Authentication : login logout signup
Product page: All the products
Orders page : Shows orders for each user
Payment gateway

## Milestone 2:
Setting up of the frontend with following commands and packages

tailwind CSS
React (npm create vite@latest frontend)
setting up of the backend with following commands and packages npm init || npm init -y

express (npm i express)
mongoose (npm i mongoose)
cors (npm i cors)
nodemon (npm i nodemon)

## Milstone 3
Setting up of nodejs sevrer and handling the api requests.
Connect your application to MongoDB to store and manage data.
connetion between Database and server.
Error Handler (these handler rectify where has the error occured filename.js)

## Milestone 4
User Model for our database, (Done)
setting up controllers to handle user-related data,
enabling file uploads using Multer.

## Milestone 5
Created a signup page
Created validation Object using RegEx
Setup React-Router for the Present Pages

## Milestone 6
Created a multer file for the upload functionality
When we click submit button, the data will be reflected in console as a json format
the images will be stored under the uploads 





## Milestone 7 :


In this milestone, we implemented a login endpoint in the backend to validate user credentials. We updated the frontend (Login.jsx) to send a POST request with email and password, handled errors, and displayed success messages. The backend (user.js) verifies user credentials using bcrypt and returns a success response.


## Milestone 8 :


 Implemented the Product Page and Home Page by creating a reusable Product.jsx component with prop validation and a responsive design using Tailwind CSS. Developed Home.jsx to dynamically display multiple products in a grid layout. Updated Routes.jsx to include the Home component and modified App.jsx to integrate the / route for seamless navigation between Home, Login, and Signup pages.


 ## Milestone 9 : 


 In this milestone, we implemented a Create Product page where users can input product details, including name, description, category, tags, price, stock, email, and images. We used a dropdown for category selection and allowed multiple image uploads with previews. Additionally, we created a new route for this page and integrated it into the app by updating routes.jsx and App.jsx. This milestone enhances product management by enabling users to add new products seamlessly. 


 ## Milestone 10 :


 In Milestone 10, we create the backend endpoint for the "Create Product" page. This involves setting up a product schema, handling form submissions in the frontend, and validating product data before storing it in the database. We configure Multer for image uploads, ensure user verification via email, and integrate the route into Express.js. Finally, we update App.js to connect the new API endpoint.