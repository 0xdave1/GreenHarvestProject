# 🌿 GreenHarvest

GreenHarvest is a full-stack agri-tech web application built as my Capstone Project at **PLP Academy**. It connects farmers directly with consumers, enabling them to showcase produce, communicate seamlessly, and build trust in a transparent digital marketplace.

👨‍💻 **Capstone Project Developer:** David Joseph

---

## 💡 Project Brief

**Goal:** Build a full-stack web application that connects farmers and consumers.

I developed GreenHarvest — a scalable and modern agricultural marketplace designed to empower farmers and give consumers an easy way to buy fresh produce directly from the source.

---

## ❗ The Problem

Farmers often face:

- ❌ No digital platform to promote their products  
- ❌ Heavy dependence on middlemen  
- ❌ Limited access to consumers  
- ❌ Lack of trust-building infrastructure  

---

## ✅ The Solution — GreenHarvest

GreenHarvest addresses these challenges through:

- 🌾 **Farmer Profiles** — Farm details, locations, and product listings  
- 🛒 **Consumer Dashboard** — Discover produce by farm or category  
- 💬 **Messaging System** — Direct farmer-to-consumer communication  
- 📦 **Order Requests** — Simple, secure order placement  
- 🛠️ **Admin Panel** — User, product, and category management  
- 🔐 **Role-Based Authentication** — Farmer, Consumer & Admin  

---

## 🧰 Technologies Used

- **Frontend:** React JS, Tailwind CSS, Redux  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** JWT  
- **Hosting:** Vercel  

---

## 🧩 Features Overview

| Role        | Features                                                                 |
|-------------|--------------------------------------------------------------------------|
| 👨‍🌾 Farmer   | Register, login, manage profile/products, view & reply to messages       |
| 🛒 Consumer | Browse products, search by category, message farmers, send order requests |
| 🛠️ Admin    | Manage users, listings, categories, and order activities                 |
| 🔐 Auth     | Secure and role-based access control                                     |

---

## 📁 Project Structure

### Frontend (`client/`)
client/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── pages/
│   ├── redux/
│   ├── App.jsx
│   └── main.jsx
├── .env
└── index.html

### Backend (`api/`)
api/
├── controllers/
├── db/
├── models/
├── routes/
├── utils/
├── .env
└── index.js

---

## 🚀 Getting Started

### Prerequisites

- Node.js  
- npm  
- MongoDB connection string  
- Code editor (VS Code recommended)  

### 1. Clone or Download Project

```bash
git clone https://github.com/yourusername/GreenHarvest.git

🛠️ Getting Started
Prerequisites

Node.js

npm

MongoDB connection string

VS Code or any editor

🟢 Running the Frontend
cd client
npm install


Create a .env file:

VITE_BACKEND_URL=http://localhost:5000


Start frontend:

npm run dev

🔵 Running the Backend
cd api
npm install


Create .env:

PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key
JWT_EXPIRE=90d


Start backend:

npm run dev

🌐 Live Demo & Repo

Add your links here once deployed:

Live Frontend:

GitHub Repository:
