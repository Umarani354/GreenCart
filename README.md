# 🥗 GreenCart – Organic Food Ordering Website

GreenCart is a **MERN stack** food ordering application that allows users to browse food items, add them to their cart, and place orders.  It also includes an **admin dashboard** for managing items, tracking orders, and updating the menu in real-time.

                         
<p align="center">
  <img src="https://github.com/Umarani354/GreenCart/blob/main/frontend/src/assets/logo.png" alt="GreenCart Logo" width="480">
</p>

## 🌐 Live Demo
[![User Panel](https://img.shields.io/badge/%20User%20Panel-Render-brightgreen?style=for-the-badge&logo=render)](https://greencart-frontend-8xv9.onrender.com)

[![Admin Panel](https://img.shields.io/badge/%20Admin%20Panel-Render-blue?style=for-the-badge&logo=render)](https://greencart-admin.onrender.com)
##   ✨ Features

 👤 **User Panel**
- Login / Signup
- Logout
- Add to Cart
- Place Order
- Filter Food Products
- Stripe Payment Integration

🛠 **Admin Panel**
- Order Management
- Products Management
- Filter Food Products
  
 🔐 **Security**
- JWT Authentication
- Password Hashing with Bcrypt
- Authenticated APIs




## ⚙️ Run on Local Environment

Clone the project

```bash
  git clone https://github.com/Umarani354/GreenCart.git
```

Go to the project directory

```bash
  cd GreenCart
```

Install dependencies(admin)

```bash
  cd admin
  npm install
```
Install dependencies(frontend)

```bash
  cd frontend
  npm install
```

Install dependencies(backend)

```bash
  cd backend
  npm install
```


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`JWT_SECRET  =  YOUR_SECRET_TEXT`

`MONGO_URL   =   YOUR_DATABASE_URL`

`STRIPE_SECRET_KEY  =   YOUR_KEY`


### Setup the Frontend and Backend URL

- App.jsx in Admin folder const url = YOUR_BACKEND_URL

- StoreContext.js in Frontend folder const url = YOUR_BACKEND_URL

- orderController in Backend folder const frontend_url = YOUR_FRONTEND_URL
 

Start the Backend server

```bash
  node server.js
```

Start the Frontendserver

```bash
  npm run dev 
```

 Start the Admin server

```bash
  npm run dev
```
## 💻 Tech Stack

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) 
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) 
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white) 
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white) 
![Stripe](https://img.shields.io/badge/Stripe-008CDD?style=for-the-badge&logo=stripe&logoColor=white) 
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

## Deployment

The application is deployed on Render.

## Feedback

If you have any feedback, please reach out to me <a href="linkedin.com/in/umarani-bharamanaikar">here</a>

