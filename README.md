# 💸 ExpenseFlow – MERN Stack Expense & Payment Tracker

**ExpenseFlow** is a full-stack web application built with the powerful **MERN** stack (MongoDB, Express.js, React.js, Node.js). It simplifies **expense tracking** for individuals and groups, offering a streamlined interface to manage, monitor, and get reminders for payments.

---

## 🚀 Features

- ➕ Add, ✏️ Edit, and ❌ Delete expenses
- 📊 Track payment status (Paid / Unpaid)
- ⏰ Set due dates and receive automated reminders
- 🔐 Secure user authentication with JWT & Bcrypt
- 🌐 RESTful API with Express & MongoDB
- 🖥️ Responsive frontend using React

---

## 🛠️ Tech Stack

**Frontend**  
- React.js  
- React Router  
- Axios  
- Context API  

**Backend**  
- Node.js  
- Express.js  
- MongoDB & Mongoose  
- JWT for auth  
- Bcrypt for password hashing  
- dotenv, cors, body-parser  

---

## 📁 Project Structure

ExpenseFlow/
├── backend/               
│   ├── controllers/       # Business logic
│   ├── middleware/        # Auth & error handling
│   ├── models/            # Mongoose schemas
│   ├── routes/            # API endpoints
│   ├── scheduler/         # Automated reminders
│   ├── server.js          # Entry point
│   └── .env.example       # Environment variable template
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/    # Reusable UI components
│   │   ├── pages/         # Route-level pages
│   │   ├── context/       # Global state & auth context
│   │   ├── utils/         # Helper functions
│   │   └── App.js         # Main app component
│   └── package.json
│
├── README.md
└── .gitignore

## 🔐 Authentication Flow

1. **User Registration & Login**  
   Users sign up and log in securely.

2. **JWT Token Generation**  
   Tokens are issued upon login and used for subsequent requests.

3. **Protected Routes**  
   Backend APIs verify JWTs for protected endpoints.

4. **Frontend Auth State**  
   React manages the auth state using Context API & localStorage.



