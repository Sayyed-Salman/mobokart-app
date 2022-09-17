# MoboKart v1

## How to run

- frontend

  `cd frontend`
  <br>
  `npm install`
  <br>
  `npm start`

- backend

  create a .env file and paste [ENV file](#env-file)

  `cd backend`
  <br>
  `npm install`
  <br>
  `node index.js`

<hr>

## Views

1. Homepage
   ![](./screenshots/homepage.jpg)

2. Login
   ![](./screenshots/login.jpg)

3. Register
   ![](./screenshots/register.jpg)

4. Cart
   ![](./screenshots/cart.jpg)

5. Create Products (admin functionality)
   ![](./screenshots/create_products.jpg)

## ENV file

```
DB_URI = "mongodb+srv://epicd3055:newpassword@mobokart.9rj7lnx.mongodb.net/?retryWrites=true&w=majority"
JWT_SECRET_KEY = <>
STRIPE_KEY = sk_test_51Lig01SHdO3ee1PlCHMtkf2NJysc3EoBsJYUCqrG7YaGrif48QJcl1CUMlepQhYV2sWypgYOQd1rvSK5Tp6pu0eQ00XYd4emkv
STRIPE_WEB_HOOK = <>
CLIENT_URL = http://localhost:3000
CLOUDINARY_NAME = dqm7ig7oi
CLOUDINARY_API_KEY = 685974744966867
CLOUDINARY_API_SECRET = 5unbQryu8g90KUC4MjJ93bCT0Nk
```
