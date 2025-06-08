# 🛍️ Efashion – MERN Stack E-Commerce Web Application

Efashion is a full-featured e-commerce web application built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**. The platform supports user authentication, product management, cart functionality, secure checkout, and admin dashboard features.

## 🚀 Features

- 🔐 User Registration & Login (with JWT Auth)
- 🛒 Product Browsing and Filtering
- 🧺 Cart Management
- 💳 Razorpay Payment Integration
- 📦 Order Placement & Tracking
- 🛠️ Admin Panel for Managing Products, Orders, and Users
- 🖼️ Cloudinary Integration for Product Images
- 📱 Responsive Design with Tailwind CSS

## 🛠️ Tech Stack

- **Frontend**: React.js, Tailwind CSS, Axios, React Router
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Others**: Razorpay API, Cloudinary, JWT, Postman (for API testing)

## 📂 Folder Structure

```bash
client/       # React frontend
 └── src/
server/       # Express + Node backend
 └── controllers/
 └── models/
 └── routes/
 └── config/
🧪 Setup Instructions
Prerequisites
Node.js

MongoDB

Cloudinary account

Razorpay account

1. Clone the repository
bash
Copy
Edit
git clone https://github.com/aayuc710/efashion-mern-app.git
cd efashion-mern-app
2. Backend Setup
bash
Copy
Edit
cd server
npm install
Create a .env file inside server/ and add:

env
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
RAZORPAY_KEY_ID=your_razorpay_key
RAZORPAY_SECRET_KEY=your_razorpay_secret
bash
Copy
Edit
npm start
3. Frontend Setup
bash
Copy
Edit
cd ../client
npm install
npm start
📷 Screenshots
Landing Page	Product View	Admin Panel

✨ Highlights
Clean, modular codebase

API-first backend architecture

Scalable design with separation of concerns

Focused on real-world features and user experience

🤝 Contributing
Feel free to fork this repo, raise issues, and submit PRs!

📬 Contact
Ayushi Patel
📧 patelaayushi1003@gmail.com
🔗 LinkedIn
