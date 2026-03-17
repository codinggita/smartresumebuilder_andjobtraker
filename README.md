# 🚀 Smart Resume Builder & Job Tracker

A modern **full stack web application** that enables users to **create professional resumes** and **track job applications efficiently** in one unified platform.

---

## 📌 Problem Statement

Job seekers often face challenges such as:

* Creating well-structured and professional resumes
* Managing multiple versions of resumes
* Tracking job applications across different platforms

This application provides a **centralized solution** to streamline the entire process.

---

## 🎯 Objective

To build a complete full stack application that allows users to:

* Create and manage resumes
* Track job applications
* Organize career-related data efficiently

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Tailwind CSS
* React Router

### Backend

* Node.js
* Express.js

### Database

* MongoDB

---

## ⚙️ Features

### 🔐 Authentication System

* User Signup & Login
* Password validation
* LocalStorage-based authentication
* Protected routes

---

### 🏠 Dashboard

* Overview of resumes
* Job application summary
* Quick navigation

---

### 📄 Resume Builder

* Create, edit, and delete resumes (CRUD)
* Structured sections:

  * Personal Information
  * Education
  * Experience
  * Skills
  * Projects
* Live preview while editing

---

### 💼 Job Tracker

* Add job applications
* Update application status (Applied / Interview / Rejected)
* Delete job entries
* Track all applications in one place

---

### 🔍 Search, Filter & Sort

* Search resumes and job applications
* Filter by category or status
* Sort by date or relevance

---

### ⚡ Debouncing

* Optimized search functionality
* Reduces unnecessary API calls

---

### 📄 Pagination

* Paginated resume list
* Paginated job application list
* Backend pagination using MongoDB (`limit` & `skip`)

---

### 🎨 Theme Support

* Dark Mode / Light Mode toggle
* Persistent theme preference

---

### 🔄 State Management

* Context API / Redux Toolkit
* Used for:

  * User authentication
  * Theme management
  * Shared application data

---

### 🔗 API Integration

* RESTful APIs built with Express.js
* Proper error handling
* Loading states during API calls

---

### 🧾 Form Handling & Validation

* Controlled components
* Input validation
* User-friendly error messages

---

### 📱 Responsive UI

* Fully responsive design using Tailwind CSS
* Optimized for:

  * Mobile
  * Tablet
  * Desktop

---

### ⚠️ Error Handling

* Backend error handling using try-catch
* Frontend error display
* Proper API error responses

---

## 🧠 React Hooks Used

* `useState` – State management
* `useEffect` – Side effects & API calls
* `useRef` – DOM access and focus handling
* `useContext` – Global state management

---

## 🗄️ Database Schema (Overview)

### Users

* name
* email
* password

### Resumes

* userId
* title
* personalInfo
* education
* experience
* skills
* projects
* createdAt

### Jobs

* userId
* company
* role
* status
* appliedDate

---

## 📁 Project Structure

```
client/
  src/
    components/
    pages/
    context/
    hooks/
    services/

server/
  controllers/
  models/
  routes/
  middleware/
  config/
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/resume-builder.git
cd resume-builder
```

---

### 2. Install Dependencies

#### Frontend

```bash
cd client
npm install
npm run dev
```

#### Backend

```bash
cd server
npm install
npm start
```

---

## 🔐 Environment Variables

Create a `.env` file inside the `server` directory:

```
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

---

## 🌟 Future Enhancements

* Resume download as PDF
* Multiple resume templates
* AI-based resume suggestions
* Email notifications
* Cloud storage integration

---

## 🏆 Conclusion

This project demonstrates a **complete full stack application**, including:

* Frontend development using React
* Backend API development with Node.js & Express
* MongoDB database integration
* Authentication & state management
* Advanced features like filtering, pagination, and debouncing

---

## 👨‍💻 Author

**Your Name**

---

## 📄 License

This project is developed for **educational and hackathon purposes**.
