# 💼 Payroll Management System

A web-based Payroll Management System for managing employee salaries, expenses, and payroll records efficiently with role-based access for Admins and Employees.

---

## 🧩 Project Overview

This system allows:

- **Admins** to manage employees, salaries, and expenses  
- **Employees** to view salary slips, submit expenses, and track payment history  
- Role-based dashboards with secure access  

---

## 🛠 Tech Stack

| Layer         | Technology             | Reason for Choice                                                                 |
|--------------|------------------------|-----------------------------------------------------------------------------------|
| Frontend     | React.js + Tailwind CSS| Fast, component-based UI; Tailwind provides responsive and modern styling easily |
| State Mgmt   | Redux Toolkit          | Efficient global state management for user info, expenses, and salary data       |
| Backend      | Node.js + Express.js   | Lightweight, scalable, easy to create REST APIs                                  |
| Database     | MongoDB                | Flexible NoSQL database for dynamic payroll and employee data                    |
| Authentication | JWT (JSON Web Token) | Secure token-based authentication for role-based access                          |
| API Calls    | Axios                  | Simplified HTTP requests for client-server communication                         |

---

## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/Himanshubhadoria11/Payroll-Management-System.git
cd payroll-management

Setup Instructions
1. Clone the repository
git clone https://github.com/Himanshubhadoria11/Payroll-Management-System.git
cd payroll-management

2. Backend Setup
cd backend
npm install
cp .env.example .env        # Set your environment variables
nodemon or npm start         # Start backend server


Required .env variables(backend):

PORT=7777
MONGO_URI=mongodb+srv://himanshubhadoria22:Hsb81996@cluster0.9qck1zf.mongodb.net/payroll_management_system?retryWrites=true&w=majority
FRONTEND_URL=https://payrollfrontend.onrender.com
JWT_SECRET=himanshu

3. Frontend Setup
cd frontend
npm install
npm run dev

Required .env variables(frontend):
.env=VITE_API_BASE_URL=https://payrollbackend-s29z.onrender.com                  # Start frontend server


Access:

Open http://localhost:3000 in your browser.



## 🚀 Approach & Features

### 🔐 Role-Based Dashboards
- **Admin:** Manage all employees, salary details, and expense reports  
- **Employee:** View personal salary and expenses  

### 💸 Expense Management
- Employees can submit expenses  
- Admins can approve, reject, or view all expenses  

### 🧾 Salary & Payroll Management
- **Admin:** Generate salary slips, manage allowances and deductions  
- **Employee:** View/download salary slips  

### 🗃️ Data Persistence & State Management
- Redux Toolkit for global state  
- MongoDB for storing employee, salary, and expense data  

### 🔒 Security
- JWT-based authentication  
- Role-based route protection


Folder Structure
/backend
 ├─ models/
 ├─ routes/
 ├─ controllers/
 ├─ middleware/
 └─ server.js

/client
 ├─ src/
 │   ├─ components/
 │   ├─ pages/
 │   ├─ redux/
 │   └─ App.js

 ## 🔐 Demo Login

### Admin
- **Email:**:  hire-me@anshumat.org
 
- **Password:**:  HireMe@2025! 

### Employee
- **Email:**:  hhire-me@anshumat.org
- **Password:**:  HireMe@2025! 

---

## 🚀 Approach & Features

### 🔐 Role-Based Dashboards
- **Admin:** Manage all employees, salary details, and expense reports  
- **Employee:** View personal salary and expenses  

### 💸 Expense Management
- Employees can submit expenses  
- Admins can approve, reject, or view all expenses  

### 🧾 Salary & Payroll Management
- **Admin:** Generate salary slips, manage allowances and deductions  
- **Employee:** View/download salary slips  

### 🗃️ Data Persistence & State Management
- Redux Toolkit for global state  
- MongoDB for storing employee, salary, and expense data  

### 🔒 Security
- JWT-based authentication  
- Role-based route protection


 