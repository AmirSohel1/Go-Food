# 🍔 Go-Food - Online Restaurant Website

**Go-Food** is a full-stack restaurant website that enables users to browse food items, place orders, and manage their cart with a smooth and modern interface. Built using **React** on the frontend and **Express.js + MongoDB** on the backend, Go-Food delivers a fast, responsive, and user-friendly food ordering experience.

---

## 📌 Features

- 🧑‍🍳 Browse food categories and menus
- 🛒 Add items to cart and manage orders
- 🔐 User authentication (signup & login)
- 💳 Checkout and order confirmation
- 📦 Backend API with Express and MongoDB
- 🎨 Responsive UI with React & CSS
- 🔎 Search/filter food items
- 🧾 Order history and user profile

---

## 🛠️ Tech Stack

### 💻 Frontend (React)

- **React.js** (CRA - `npx create-react-app`)
- **React Router DOM** for navigation
- **Axios** for API integration
- **Bootstrap** / **CSS Modules** for styling
- **Context API** or Redux (optional) for cart state

### 🧠 Backend (Express + MongoDB)

- **Express.js** REST API
- **MongoDB** & **Mongoose** for database
- **JWT** for authentication
- **bcrypt.js** for password hashing
- **dotenv** for secure config

---

## 🗂️ Project Structure

go-food/
├── backend/
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── middleware/
│ ├── .env
│ └── server.js
│
└── frontend/
└── go-food-client/
├── public/
├── src/
│ ├── components/
│ ├── pages/
│ ├── App.js
│ └── index.js
├── package.json
└── .env

---

## 🔐 .env Configuration

### 📍 Backend `.env`

```env
PORT=5000
MONGO_URI=mongodb://localhost:27017/gofood
JWT_SECRET=your_jwt_secret_key

REACT_APP_API_URL=http://localhost:5000

cd backend
npm install
npm start


cd my-app
npm install
npm start
```
