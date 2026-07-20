# 🎵 Spotify Backend API

A Spotify-inspired **Backend REST API** built using **Node.js**, **Express.js**, and **MongoDB**. 
This project demonstrates backend development concepts such as secure authentication, RESTful API design, database integration, and scalable application architecture using the MVC pattern.

---

## 🚀 Features

- 🔐 JWT Authentication & Authorization
- 👤 User Registration & Login
- 🎵 Song Management
- 💿 Album Management
- 📂 Playlist Management
- ✍️ Complete CRUD Operations
- 🌐 RESTful API Design
- 🗄️ MongoDB Database Integration
- 📦 Mongoose ODM
- 🏗️ MVC Architecture
- ⚡ Error Handling & Validation
- 🧪 API Testing using Postman

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| JavaScript | Programming Language |
| Node.js | Runtime Environment |
| Express.js | Backend Framework |
| MongoDB | NoSQL Database |
| Mongoose | MongoDB ODM |
| JWT | Authentication & Authorization |
| Postman | API Testing |
| Git & GitHub | Version Control |

---

## 📂 Project Structure

```
spotify-backend-api/
│
├── src/
│   ├── controllers/
│   ├── db/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── app.js
│
├── server.js
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

---

## 🔐 Authentication

The application uses **JSON Web Tokens (JWT)** to secure protected routes.

Authentication Flow:

- User Registration
- User Login
- JWT Token Generation
- Protected Routes
- Authorization Middleware

---

## 📡 REST API

Some of the implemented APIs include:

### Authentication

- Register User
- Login User

### User

- Create User
- Update User
- Delete User
- Get User Details

### Playlist

- Create Playlist
- Update Playlist
- Delete Playlist
- Get Playlist

### Songs

- Add Song
- Update Song
- Delete Song
- Get Songs

### Albums

- Create Album
- Update Album
- Delete Album
- Get Albums

---

## 💻 Installation

Clone the repository

```bash
git clone https://github.com/LipunNahak/spotify-backend-api.git
```

Move to the project folder

```bash
cd spotify-backend-api
```

Install dependencies

```bash
npm install
```

Create a `.env` file

```env
PORT=3000
MONGODB_URI=Your MongoDB Connection String
JWT_SECRET=Your Secret Key
```

Start the server

```bash
npm start
```

---

## 🧪 API Testing

All API endpoints were tested using **Postman**.

---

## 📚 What I Learned

- Backend Development with Node.js & Express.js
- Designing RESTful APIs
- JWT Authentication & Authorization
- MongoDB Database Design
- Mongoose ODM
- MVC Architecture
- Git & GitHub Workflow
- API Testing using Postman

---

## 👨‍💻 Author

**Lipun Nahak**

- LinkedIn: linkedin.com/in/lipun-nahak-0b2286249   
- GitHub: https://github.com/LipunNahak

---

## ⭐ Support

If you found this project helpful, consider giving it a **⭐ Star** on GitHub.
