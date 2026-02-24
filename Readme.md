Create a file named:

README.md

Then paste this 👇

# 🚀 Todo App Backend (MERN Stack)

This is the backend API for the Todo Application built using **Node.js, Express, and MongoDB**.

It provides RESTful APIs to create, read, update, and delete notes (jobs).  
The database is hosted on MongoDB Atlas and the backend is ready for deployment on Render.

---

## 🛠️ Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- dotenv
- CORS

---

## 📁 Project Structure


Backend/
│-- index.js
│-- package.json
│-- .env
│-- README.md


---

## 🔐 Environment Variables

Create a `.env` file in the root directory and add:


MONGO_URL=your_mongodb_atlas_connection_string
PORT=3000


⚠️ Never commit your `.env` file to GitHub.

---

## 📦 Installation & Setup

### 1️⃣ Clone the repository


git clone https://github.com/Jaid-Khan/Todo_app_backend.git


### 2️⃣ Navigate into project folder


cd Backend


### 3️⃣ Install dependencies


npm install


### 4️⃣ Start development server


npm run dev


Or start normally:


npm start


Server will run at:


http://localhost:3000


---

## 📌 API Endpoints

### 🔹 Get All Notes

GET /jobs


### 🔹 Create New Note

POST /jobs

Body:
{
"job": "Title",
"desc": "Description"
}


### 🔹 Update Note

PUT /jobs

Body:
{
"id": "note_id",
"job": "Updated Title",
"desc": "Updated Description"
}


### 🔹 Delete Note

DELETE /jobs

Body:
{
"id": "note_id"
}


---

## 🌍 Deployment

Backend is production-ready and can be deployed on:

- Render (Web Service)
- MongoDB Atlas (Cloud Database)

---

## 👨‍💻 Author

Mohammad Jaid  
Frontend & MERN Stack Developer

---

## 📄 License

This project is open-source and free to use.