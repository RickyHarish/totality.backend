Mainly Our Folder Structure is
backend=>
  config=>db.js---This File is used connect to the MongoDB Database by using mongoose to get the Data by connection string
  controllers=>orderController.js--- This file is used to control the orders from users
            =>productController.js -- This file is used to control the access from users based on their accessibilit like admin and user
            =>userController.js --- This file is used to control the Authentication like login and registeration
  data=> products.js
          users.js ---- These Both files used to add initial data to the database for access

   middleware=>authMiddleware.js ---- This moddleware is used to control the authentication
             => errorMiddleware.js --- This is used to handle the errors
  models=> Models used for all the schemas
  routes=> These routes will handle all the routes according to user interactions
  uploads=> Will take the input images from the user
  utils=>this directory used to generate JWT Token for authentication and authorization


----Routes----
https://totality-backend-8mc6.onrender.com   This is the URL for backend deployement

Rooutings are--

/api/products/${id}`
`/api/orders`
.
.
.


So many routes are added to access the backend CRUD Operations
