# 🤖 Robotics

A full-stack web application built on an e-commerce logic, consisting of a **JavaScript** frontend and a **Node.js/Express + MongoDB** backend.


---

## 📖 About

This project is an online store platform that lets users search for products, sort them, and view their details, while giving admin users the ability to manage products (add/delete).

---

## ✨ Features

### Frontend
- 🔍 **Search** — Search products by their titles.
- 📊 **Sort by price** — Sort products by price.
- 📄 **Product details** — View a detailed page for each product.
- ➕ **Add product** — Add new products from the admin panel.
- ❤️ **Favorites** — Users can add products to their favorites.
- 🗑️ **Delete product** — Admin users can delete products.

### Backend
- ⚙️ **Node.js & Express** — Used for server-side handling.
- 🗄️ **MongoDB** — Used to store product and user data.
- 🔁 **CRUD operations** — Supports creating, deleting, updating, and listing products.
- 🔗 **API integration** — Data exchange between frontend and backend is handled through an API.

---

## 🛠️ Tech Stack

| Layer | Technologies |
|---|---|
| Frontend | JavaScript, SCSS/CSS, HTML |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| Deployment | Vercel |

---

## 📁 Project Structure

```
Robotics/
├── backend/     # Express server, API endpoints, MongoDB models
├── frontend/    # User interface (UI)
└── README.md
```

---

## 🚀 Getting Started

Follow these steps to run the project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/Gultekinn/Robotics.git
   cd Robotics
   ```

2. **Set up and run the backend**
   ```bash
   cd backend
   npm install
   ```
   Create a `.env` file inside the `backend` folder and add your MongoDB connection string, for example:
   ```
   MONGO_URI=your_mongodb_connection_string
   PORT=5000
   ```
   Then start the server:
   ```bash
   npm start
   ```

3. **Set up and run the frontend**
   ```bash
   cd ../frontend
   npm install
   npm start
   ```

4. Open in your browser: `http://localhost:3000`

