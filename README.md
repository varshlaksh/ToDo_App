TaskPro – ToDo App Backend
A RESTful API built using Node.js, Express.js, and MongoDB to manage users and their tasks efficiently. It allows users to register, log in, create tasks, assign priorities, mark them as completed, and delete them.

🌟 Features
✅ User Registration & Login with JWT Authentication

✅ Password hashing using bcryptjs

✅ Protected Task Management APIs

✅ Create, Read, Update, and Delete (CRUD) tasks

✅ Assign Priority to tasks (High, Medium, Low)

✅ Mark tasks as Completed

✅ User-specific task data (secured via JWT)



📁 Project Structure
├── models/
│   ├── userModel.js
│   └── taskModel.js
├── routes/
│   ├── userRoutes.js
│   └── taskRoutes.js
├── controllers/
│   ├── userController.js
│   └── taskController.js
├── middlewares/
│   └── authMiddleware.js
├── .env
├── server.js
└── package.json

🔐 Environment Variables (.env)
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key


▶️ How to Run the Project
1. Clone the repository
git clone https://github.com/yourusername/TaskPro.git
cd TaskPro

3. Install dependencies
npm install

5. Create a .env file
Add your MongoDB URI and JWT secret in .env file as shown above.

6. Start the server
npm run dev
Server runs at: http://localhost:5000

