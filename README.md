# 💰 Ledger – Full-Stack Expense Tracker

A modern **MERN Stack Expense Tracker** that helps users securely manage their personal finances. Ledger provides authentication, transaction management, insightful reports, and interactive dashboards through a clean, responsive user interface.

---

## 🌐 Live Demo

**Frontend:**  
https://expense-tracker-nine-rho-67.vercel.app

---

# 📖 Overview

Ledger is a full-stack personal finance management application that enables users to:

- Securely create an account
- Track income and expenses
- Categorize transactions
- Analyze spending habits
- View financial reports with interactive charts
- Manage all transactions from a responsive dashboard

The application uses **JWT Authentication** for security and stores user data securely in **MongoDB Atlas**.

---

# ✨ Features

## 🔐 Authentication

- User Registration
- User Login
- JWT Authentication
- Protected Routes
- Password Hashing using bcrypt
- Persistent Login Sessions

---

## 📊 Dashboard

- Current Balance
- Total Income
- Total Expenses
- Monthly Spending
- Recent Transactions

---

## 💵 Transaction Management

- Add Transactions
- Edit Transactions
- Delete Transactions
- Income & Expense Support
- Search Transactions
- Filter by Category
- Filter by Type
- Filter by Date Range
- Pagination

---

## 📈 Reports & Analytics

- Monthly Income vs Expense Bar Chart
- Category-wise Expense Doughnut Chart
- Spending Distribution
- Recent Transaction Summary

---

## 📱 Responsive User Interface

- Mobile Friendly
- Tablet Friendly
- Desktop Optimized
- Responsive Sidebar
- Clean Ledger-inspired Theme
- Interactive Charts

---

# 🛠 Tech Stack

## Frontend

- React
- Vite
- Tailwind CSS
- Axios
- React Router
- Chart.js

---

## Backend

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- JWT
- bcrypt
- Express Validator

---

## Deployment

| Service | Platform |
|----------|----------|
| Frontend | Vercel |
| Backend | Render |
| Database | MongoDB Atlas |

---

# 📂 Project Structure

```text
expense-tracker/
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── components/
│   ├── pages/
│   ├── context/
│   ├── api/
│   └── ...
│
├── backend/
│   ├── config/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── utils/
│   └── ...
│
└── README.md
```

---

# 🚀 Installation

## 1. Clone Repository

```bash
git clone https://github.com/berwincr/expense-tracker.git

cd expense-tracker
```

---

## 2. Backend Setup

```bash
cd backend

npm install
```

Create a **.env** file

```env
PORT=5000

MONGO_URI=YOUR_MONGODB_CONNECTION_STRING

JWT_SECRET=YOUR_SECRET_KEY

JWT_EXPIRES_IN=7d

CLIENT_URL=http://localhost:5173
```

Run the backend

```bash
npm run dev
```

or

```bash
npm start
```

Backend runs at

```
http://localhost:5000/api
```

Health Check

```
GET /api/health
```

---

## 3. Frontend Setup

```bash
cd frontend

npm install
```

Create

```env
VITE_API_URL=http://localhost:5000/api
```

Run

```bash
npm run dev
```

Visit

```
http://localhost:5173
```

---

# 📡 API Endpoints

## Authentication

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | `/api/auth/register` | Register User |
| POST | `/api/auth/login` | Login User |
| GET | `/api/auth/me` | Get Current User |
| POST | `/api/auth/logout` | Logout |

---

## Transactions

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | `/api/transactions` | Get Transactions |
| POST | `/api/transactions` | Create Transaction |
| GET | `/api/transactions/:id` | Get Transaction |
| PUT | `/api/transactions/:id` | Update Transaction |
| DELETE | `/api/transactions/:id` | Delete Transaction |

---

## Dashboard

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | `/api/dashboard/summary` | Dashboard Summary |
| GET | `/api/dashboard/monthly-summary` | Monthly Report |
| GET | `/api/dashboard/category-summary` | Category Report |
| GET | `/api/dashboard/recent` | Recent Transactions |

---

# 🔒 Security

- Passwords are hashed using **bcrypt**
- JWT Authentication
- Protected API Routes
- Express Validator
- Mongoose Validation
- Secure Environment Variables
- MongoDB Atlas Cloud Database

---


# 🌱 Future Enhancements

- Budget Planning
- Export Reports as PDF
- Excel Export
- Email Verification
- Recurring Transactions
- Notifications
- Multi-Currency Support
- Dark Mode
- AI Spending Insights
- OCR Receipt Scanner

---

# 🎯 Learning Outcomes

Through this project, I gained hands-on experience with:

- Full-Stack MERN Development
- REST API Design
- JWT Authentication
- MongoDB Data Modeling
- React State Management
- Secure Password Hashing
- CRUD Operations
- Deployment using Vercel & Render
- Environment Variable Management
- Cross-Origin Resource Sharing (CORS)
- Debugging Production Deployment Issues

---

# 👨‍💻 Author

**Berwin CR**

B.Tech Information Technology  
College of Engineering, Guindy

GitHub:
https://github.com/berwincr

---

# ⭐ Support

If you found this project useful, consider giving it a **⭐ Star** on GitHub!

It helps others discover the project and supports future development.

---

## 📄 License

This project is licensed under the **MIT License**.

Feel free to use and modify it for learning purposes.
