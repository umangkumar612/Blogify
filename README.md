# Blogify
# 📚 Blogify – A Modern Blogging Platform

Blogify is a full-stack blogging web application built using **Node.js**, **Express.js**, **MongoDB**, and **Mongoose**.  
It allows users to create, edit, delete, and read blogs with authentication and comments support.

---

## 🚀 Features

### 🔐 Authentication
- User Signup
- User Login
- Password hashing

### ✍️ Blogs
- Create a new blog
- Edit existing blog
- Delete blogs
- View blogs

### 💬 Comments
- Add comments on blogs
- View comments
- Delete comments (if admin)

### 🖼️ UI Features
- EJS templating engine for dynamic pages
- Clean and simple UI design
- Error handling pages (404, 500)

---

## 🛠️ Tech Stack

### **Backend**
- Node.js  
- Express.js  
- Mongoose  
- MongoDB  

### **Frontend**
- HTML, CSS  
- EJS Templates  

### **Tools**
- Git & GitHub  
- Postman for API testing  
- Nodemon for auto-restart  

---

## 📂 Project Folder Structure

blogify/
│── app.js
│── package.json
│── .env
│── node_modules/
│
├── routes/
├── models/
├── services/
├── middlewares/
├── public/
└── views/

yaml
Copy code

---

## ⚙️ Installation & Setup

### 1. Clone the repository
git clone https://github.com/umangkumar612/Blogify.git

shell
Copy code

### 2. Install dependencies
npm install

bash
Copy code

### 3. Add environment variables
Create a `.env` file:

MONGO_URI=your_mongodb_url
PORT=3000
SESSION_SECRET=your_secret_key

shell
Copy code

### 4. Start the server
npm start

powershell
Copy code
or (if using nodemon)
npm run dev

arduino
Copy code

Server will start at:
http://localhost:3000

yaml
Copy code

---

## 🧪 API Endpoints

### **User Routes**
| Method | Endpoint      | Description          |
|--------|--------------|----------------------|
| POST   | /signup      | Create user          |
| POST   | /login       | Login user           |

### **Blogs**
| Method | Endpoint             | Description        |
|--------|----------------------|--------------------|
| GET    | /blogs               | View all blogs     |
| POST   | /blogs               | Create blog        |
| GET    | /blogs/:id           | Single blog        |
| PUT    | /blogs/:id           | Update blog        |
| DELETE | /blogs/:id           | Delete blog        |

### **Comments**
| Method | Endpoint                      | Description       |
|--------|-------------------------------|-------------------|
| POST   | /blogs/:id/comments           | Add comment       |
| DELETE | /comments/:id                 | Delete comment    |

---

## 🤝 Contributing

Feel free to open issues or submit pull requests.

---

## 📜 License
This project is **Open Source** and available under the MIT License.

---

## 📧 Contact
**Umang Kumar**  
GitHub: [@umangkumar612](https://github.com/umangkumar612)

---
