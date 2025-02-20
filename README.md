# 📌 Task Management Application

This is a **Task Management Application** built using the **MERN stack** (MongoDB, ExpressJS, ReactJS, NodeJS). It enables users to efficiently manage their tasks with authentication, task categorization, deadlines, priority levels, and real-time updates. It follows **RESTful API** principles for seamless frontend-backend communication and enhances user experience with modern UI components.

---

## 🚀 Features

- **User Authentication** (JWT-based login/signup)
- **Task Management:** Create, Read, Update, and Delete (CRUD) tasks
- **Mark Tasks as Completed** with real-time updates
- **Categorization & Labels** for easy organization
- **Priority Levels**: High, Medium, and Low for better task planning
- **Deadline Reminders** with notifications
- **Search & Filter Tasks** by status, priority, and labels
- **Drag & Drop Interface** for easy task management
- **Dark Mode Support** for better accessibility
- **Secure Backend** using ExpressJS & MongoDB
- **RESTful API Architecture**

---

## 🛠️ Tech Stack

- **Frontend:** ReactJS, Redux (for state management), Tailwind CSS
- **Backend:** NodeJS, ExpressJS
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)
- **Real-Time Updates:** WebSockets (Socket.io for live task updates)
- **Notifications:** Toastr for frontend alerts & Email notifications

---

## 🔧 Installation

### 1️⃣ Clone the Repository

```sh
git clone https://github.com/githubsowmyajs/Task-Management-Application-Using-RESTful-API.git
cd Task-Manager_Using_RESTAPI
```

### 2️⃣ Install Dependencies

#### Backend:

```sh
cd backend
npm install
```

#### Frontend:

```sh
cd frontend
npm install
```

### 3️⃣ Set Up Environment Variables

Create a **.env** file in the `backend` folder and add:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
EMAIL_SERVICE=your_email_service_provider
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password
```

### 4️⃣ Start the Application

#### Start Backend:

```sh
cd backend
nodemon server.js
```

#### Start Frontend:

```sh
cd frontend
npm start
```

---

## 🎯 Usage

1. **Sign up or log in** to your account.
2. **Create a new task** with a title, description, category, and priority level.
3. **Set a deadline** and receive **email reminders** before due dates.
4. **Use drag & drop** to reorganize tasks based on priority.
5. **Filter & search** for tasks based on category, status, or priority.
6. **Mark tasks as completed** and track progress.

---

## 🔗 API Endpoints

| Method | Endpoint                          | Description              |
| ------ | --------------------------------- | ------------------------ |
| POST   | `/api/auth/signup`                | User Signup              |
| POST   | `/api/auth/login`                 | User Login               |
| GET    | `/api/tasks`                      | Get all tasks            |
| POST   | `/api/tasks`                      | Create a new task        |
| PUT    | `/api/tasks/:id`                  | Update a task            |
| DELETE | `/api/tasks/:id`                  | Delete a task            |
| GET    | `/api/tasks/search?query=...`     | Search tasks by title    |
| GET    | `/api/tasks/filter?priority=high` | Filter tasks by priority |

---

## 🎨 UI Preview



## 🤝 Contributing

We welcome contributions! Follow these steps:

1. Fork the repository 🍴
2. Create a new branch 🌿
3. Commit your changes 💾
4. Open a pull request ✅

---

## 📜 License

This project is licensed under the **MIT License**.

---

### 🏆 Contributors

Made by Jeevaraj Shetty S, Sneha V Jagade,Sangeeta H and Sowmya J S

Feel free to **star** ⭐ the repository if you like this project!

