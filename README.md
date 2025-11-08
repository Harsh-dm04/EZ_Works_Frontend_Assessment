# 🌟 EZ Works Contact Form Application

A modern and lightweight contact form application built using **React**, **Vite**, **Tailwind CSS**, and **React Hook Form**.  
This project is designed to collect user queries with proper validation and send them securely to a backend API using **Axios**.

---

## 📸 Screenshot

Below is a preview of the application interface 👇  

![App Screenshot]([/EZ_Works_Frontend_Assessment/blob/main/Assessment_Screenshot.png))

---

## 🚀 Features

- ✅ Built with **React functional components**
- ✅ Clean and responsive UI using **Tailwind CSS**
- ✅ Fast development environment powered by **Vite**
- ✅ Form state management & validation using **React Hook Form**
- ✅ API integration handled by **Axios**
- ✅ Email and phone number validation
- ✅ Organized project structure following a simple MVVM approach

---

## 📟 Tech Stack

| Technology        | Purpose |
|------------------|---------|
| React            | UI Components |
| Vite             | Build & Dev Server |
| Tailwind CSS     | Styling |
| React Hook Form  | Form Handling & Validation |
| Axios            | API Requests |

---

## 📌 Prerequisites

Ensure the following are installed:

- **Node.js 14+**
- **npm** or **yarn**

---

## 🛠️ Getting Started

### 1️⃣ Install Dependencies

```bash
cd client
npm install
```

###2️⃣ Start Development Server

```bash
npm run dev
```
Your app will be live at:
👉 http://localhost:5173

---

## 🏗️ Build for Production

```bash
npm run build
```

## 🌐 API Integration

The form submits user messages to the following endpoint:

```ruby
POST https://vernanbackend.ezlab.in/api/contact-us/
```

## 📁 Project Structure

``` css
src/
│── views/
│   ├── App.jsx
│   └── components/
│
│── viewmodels/
│   └── ContactViewModel.js
│
└── api/
    └── ContactApi.js
```

---

## 📂 Folder Details

views/ → Contains main UI screens and reusable components

viewmodels/ → Includes form logic & state management using React Hook Form

api/ → Axios API request functions

---

## ✅ How the App Works

User fills the contact form

React Hook Form validates input fields

Valid data is sent to the backend API

User receives success or error feedback

---

