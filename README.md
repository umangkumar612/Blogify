# 📚 Blogify – Modern Full Stack Blogging Platform

Blogify is a full-stack blogging web application built using Node.js, Express.js, MongoDB, and Mongoose.  
It allows users to create, edit, delete, and read blogs with secure authentication and comments support.

---

# 🚀 Features

## 🔐 Authentication & Security
- User Signup & Login
- JWT Authentication
- Password Hashing using bcrypt
- Protected Routes
- Session Management
- Input Validation & Error Handling

---

## ✍️ Blog Management
- Create Blogs
- Edit Blogs
- Delete Blogs
- Read Single Blog
- View All Blogs

---

## 💬 Comments System
- Add Comments
- View Comments
- Delete Comments (Admin/User Authorization)

---

## 🖼️ UI Features
- EJS Templating Engine
- Responsive UI
- Dynamic Rendering
- Custom Error Pages (404 & 500)

---

# 🛠️ Tech Stack

## Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcrypt.js

## Frontend
- HTML
- CSS
- JavaScript
- EJS Templates

## Tools & Deployment
- Git & GitHub
- Postman
- Nodemon
- Railway / Render
- MongoDB Atlas

---

# 📂 Project Structure

```bash
blogify/
│
├── app.js
├── package.json
├── .env
├── README.md
│
├── config/
├── controllers/
├── middlewares/
├── models/
├── routes/
├── services/
├── utils/
│
├── public/
│
└── views/
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/umangkumar612/Blogify.git
cd Blogify
```

---

## 2️⃣ Install Dependencies

```bash
npm install
```

---

## 3️⃣ Configure Environment Variables

Create a `.env` file in root directory:

```env
MONGO_URI=your_mongodb_url
PORT=8000
JWT_SECRET=your_secret_key
SESSION_SECRET=your_session_secret
```

---

## 4️⃣ Run the Project

### Production

```bash
npm start
```

### Development Mode

```bash
npm run dev
```

Server starts at:

```bash
http://localhost:8000
```

---

# 🧪 API Endpoints

# 🔐 Authentication APIs

| Method | Endpoint | Description |
|--------|-----------|-------------|
| POST | /signup | Register User |
| POST | /login | Login User |

---

# ✍️ Blog APIs

| Method | Endpoint | Description |
|--------|-----------|-------------|
| GET | /blogs | Get All Blogs |
| GET | /blogs/:id | Get Single Blog |
| POST | /blogs | Create Blog |
| PUT | /blogs/:id | Update Blog |
| DELETE | /blogs/:id | Delete Blog |

---

# 💬 Comment APIs

| Method | Endpoint | Description |
|--------|-----------|-------------|
| POST | /blogs/:id/comments | Add Comment |
| DELETE | /comments/:id | Delete Comment |

---

# 🔒 Security Practices

- JWT-based Authentication
- Password Hashing using bcrypt
- Protected Middleware Routes
- Input Validation
- Secure Environment Variables
- MongoDB Schema Validation

---

# 📖 API Documentation

API testing and documentation available using:

- Postman Collection
- Swagger API Docs

---

# 🌐 Deployment

## Frontend
Deploy on:
- Vercel

## Backend
Deploy on: due to low credits the project is not working properly
- Railway 
https://optimistic-sparkle-production.up.railway.app/
## Database
- MongoDB Atlas

---

# 📈 Scalability Notes

- Modular MVC Architecture
- RESTful API Design
- Scalable MongoDB Database Structure
- JWT Stateless Authentication
- Easy Microservices Migration
- Redis Caching can be integrated
- Load Balancing supported using Nginx
- Deployment Ready Architecture

---

# ✅ Evaluation Criteria Covered

✔ REST API Design  
✔ CRUD Operations  
✔ JWT Authentication  
✔ Password Hashing  
✔ Secure Middleware  
✔ MongoDB Schema Design  
✔ Frontend Integration  
✔ API Documentation  
✔ Deployment Readiness  
✔ Scalable Architecture  

---

# 🤝 Contributing

Feel free to fork the repository and create pull requests.

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

## Umang Kumar

GitHub: https://github.com/umangkumar612

Portfolio: https://silly-mousse-15f111.netlify.app/
