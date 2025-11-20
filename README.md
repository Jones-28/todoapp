# todoapp
User Management DashBoard
A modern, responsive, and user-friendly To-Do List Application built using the MERN stack (MongoDB, Express, React, Node.js).
This project demonstrates CRUD operations, RESTful API handling, state management, and clean UI design—perfect for portfolio or internship tasks.
🌟 Features

✔️ Create new tasks
✔️ View all tasks
✔️ Edit & update tasks
✔️ Delete tasks
✔️ Fully responsive UI
✔️ REST API using Express.js
✔️ MongoDB database using Mongoose
✔️ Clean component-based React design
✔️ Error handling & validations
Tech Stack
🧩 Frontend

React.js

Axios

Tailwind CSS / CSS (based on your setup)

React Hooks

🔧 Backend

Node.js

Express.js

Mongoose

MongoDB Atlas
mern-todo-app
│
├── backend
│   ├── server.js
│   ├── models/
│   │     └── Todo.js
│   ├── routes/
│   │     └── todoRoutes.js
│   ├── controllers/
│   │     └── todoController.js
│   └── .env
│
└── frontend
    ├── src/
    │   ├── App.jsx
    │   ├── components/
    │   │     ├── TodoForm.jsx
    │   │     └── TodoItem.jsx
    │   ├── api.js
    │   └── styles.css
    └── package.json
⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/yourusername/mern-todo-app.git
cd mern-todo-app
🛠️ Backend Setup
2️⃣ Navigate to backend
cd backend
3️⃣ Install dependencies
npm install
4️⃣ Create .env file
MONGO_URI=your_mongodb_connection_string
PORT=5000
5️⃣ Start backend server
npm start


Backend runs at:
👉 http://localhost:5000
💻 Frontend Setup
6️⃣ Navigate to frontend
cd ../frontend

7️⃣ Install dependencies
npm install

8️⃣ Start frontend
npm run dev


Frontend runs at:
👉 http://localhost:5173

🚧 Upcoming Enhancements

🔹 Mark tasks as completed
🔹 Add categories & priority tags
🔹 Pagination for large lists
🔹 Authentication with JWT
🔹 Dark/Light mode
🔹 Deploy frontend to Vercel & backend to Render



dotenv

CORS
