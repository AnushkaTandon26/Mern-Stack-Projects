# MERN Stack Projects Collection

## Overview

This repository is a collection of full-stack web applications built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It showcases multiple projects covering real-world use cases such as social media platforms, file sharing systems, productivity tools, and e-commerce solutions.

The purpose of this repository is to demonstrate practical implementation of full-stack development, REST APIs, authentication systems, and modern frontend design.

---

## Tech Stack

### Frontend

* React.js
* HTML5, CSS3, JavaScript
* Axios
* Bootstrap / Custom CSS

### Backend

* Node.js
* Express.js

### Database

* MongoDB

### Tools & Platforms

* Git & GitHub
* Vercel (Frontend Deployment)
* Postman (API Testing)

---

## Projects Included

### 1. Blog Website

A full-featured blogging platform where users can create, edit, and delete posts.

Features:

* CRUD operations for blogs
* Responsive UI
* REST API integration

---

### 2. CRUD Application

A basic application demonstrating Create, Read, Update, Delete operations.

Features:

* Simple UI
* API-based data handling
* MongoDB integration

---

### 3. E-Commerce Website

An online shopping platform with product listings and cart functionality.

Features:

* Product display
* Add to cart
* Basic UI for shopping flow

---

### 4. File Sharing App

A system to upload and share files securely.

Features:

* File upload system
* Link-based file sharing
* Backend file handling

Note:
Uploads and sensitive files are excluded from this repository for security reasons.

---

### 5. Gmail Clone

A simplified email interface inspired by Gmail.

Features:

* Email UI layout
* Navigation and design replication

---

### 6. Google Docs Clone

A collaborative document editing interface.

Features:

* Rich text editor
* Document UI

---

### 7. Instagram Clone

A social media application inspired by Instagram.

Features:

* Post creation
* Feed UI
* User interaction design

---

### 8. WhatsApp Clone

A real-time messaging UI inspired by WhatsApp.

Features:

* Chat interface
* Contact list UI

---

### 9. Tesla Clone

A frontend clone of Tesla’s official website.

Features:

* Landing page design
* Smooth UI components

---

### 10. To-Do List

A task management application.

Features:

* Add and delete tasks
* Simple and clean UI

---

## Project Structure

```
MERN-Stack-Projects/
│
├── Blog-Website/
├── CRUD-Application/
├── ECommerce-Website/
├── file-sharing-app/
├── gmail-clone/
├── google-docs-clone/
├── instagram-clone/
├── Whatsapp-Clone/
├── tesla-clone/
├── todo-list/
└── .gitignore
```

---

## Getting Started

### Clone the Repository

```
git clone https://github.com/AnushkaTandon26/MERN-Stack-Projects.git
cd MERN-Stack-Projects
```

---

### Install Dependencies (for each project)

Navigate into a project folder:

```
cd project-folder
```

For backend:

```
cd server
npm install
```

For frontend:

```
cd client
npm install
```

---

### Run the Application

Backend:

```
npm start
```

Frontend:

```
npm start
```

---

## Environment Variables

Create a `.env` file in backend folders where required.

Example:

```
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

Important:
Do not upload `.env` files to GitHub.

---

## Security Note

Sensitive files such as:

* `.env`
* uploads
* API keys

are excluded using `.gitignore` to maintain security and best practices.

---

## Future Improvements

* Add authentication (JWT)
* Improve UI/UX design
* Deploy backend services
* Add real-time features (Socket.io)
* Optimize performance

---
