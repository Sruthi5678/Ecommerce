# 🛍️ Forever E-Commerce Platform

A full-stack E-Commerce web application built using React.js, Node.js, Express.js, and MongoDB. The platform allows users to browse products, create accounts, manage carts,
place orders, and provides an admin panel for product management.

## 🚀 Live Demo

Frontend: https://ecommerce-bice-three-90.vercel.app

Backend API: https://ecommerce-p6cw.onrender.com

## 📌 Features

### User Features
- User Registration & Login
- JWT Authentication
- Browse Products
- Search Products
- Add to Cart
- Update Cart Quantity
- Place Orders (COD)
- View Order History
- Responsive UI

### Admin Features
- Admin Authentication
- Add Products
- Delete Products
- View All Orders
- Update Order Status
- Product Image Upload with Cloudinary

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Vite
- Context API
- Axios
- React Router DOM
- React Toastify

### Backend
- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- JWT Authentication
- Cloudinary
- Multer

### Deployment
- Frontend: Vercel
- Backend: Render
- Database: MongoDB Atlas

---

# 📂 Project Structure

```bash
Forever-Ecommerce/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── context/
│   │   ├── pages/
│   │   ├── App.jsx
│   │   └── main.jsx
│   │
│   ├── package.json
│   └── vite.config.js
│
├── backend/
│   ├── config/
│   │   ├── cloudinary.js
│   │   └── mongodb.js
│   │
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   ├── package.json
│   └── .env
│
└── README.md
```

---

# ⚙️ Environment Variables

Create a `.env` file inside the backend folder.

```env
PORT=4000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=sruthi

ADMIN_EMAIL=admin@example.com

ADMIN_PASSWORD=sruthi5678

CLOUDINARY_NAME=your_cloudinary_name

CLOUDINARY_API_KEY=998634514425239

CLOUDINARY_SECRET_KEY=your_cloudinary_secret_key
```

---

# 💻 Installation & Setup

## Clone Repository

```bash
git clone https://github.com/Sruthi5678/Ecommerce.git
```

```bash
cd Ecommerce
```

---

## Backend Setup

```bash
cd backend
```

Install dependencies:

```bash
npm install
```

Start Backend:

```bash
npm run server
```

or

```bash
npm start
```

Backend runs on:

```bash
http://localhost:4000
```

---

## Frontend Setup

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Create `.env` file:

```env
VITE_BACKEND_URL=http://localhost:4000
```

Run frontend:

```bash
npm run dev
```

Frontend runs on:

```bash
http://localhost:5173
```

---

# 🔐 Authentication Flow

1. User registers an account.
2. Password is securely hashed before storage.
3. JWT token is generated upon login.
4. Protected routes verify user authentication.
5. Admin routes require admin credentials.

---

# 📦 API Endpoints

### User

```http
POST /api/user/register
POST /api/user/login
POST /api/user/admin
```

### Product

```http
GET /api/product/list
POST /api/product/add
POST /api/product/remove
GET /api/product/single
```

### Cart

```http
POST /api/cart/add
POST /api/cart/update
POST /api/cart/get
```

### Order

```http
POST /api/order/place
POST /api/order/list
POST /api/order/status
POST /api/order/userorders
```

---

# 🌟 Future Improvements

- Razorpay Integration
- Stripe Integration
- Wishlist Feature
- Product Reviews & Ratings
- Coupon System
- Order Tracking
- Email Notifications

---

# 👩‍💻 Author

**Sruthi Vaddadi**

- B.Tech CSE, NIT Durgapur
- Aspiring Software Engineer

GitHub:
https://github.com/Sruthi5678

---

# ⭐ Support

If you found this project useful, consider giving it a star on GitHub.

```bash
⭐ Star this repository
```
