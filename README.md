
# 🚀 Task Management Application

## 📋 Overview

A modern, full-stack Task Management Application built with React and Node.js, designed to help users efficiently organize and track their tasks.

## ✨ Features

### 🔐 Authentication
- User registration
- Secure login
- JWT-based authentication
- Password encryption

### 📝 Task Management
- Create tasks
- View task list
- Edit existing tasks
- Delete tasks
- Filter tasks by status
- Responsive design

## 🛠 Tech Stack

### Frontend
- React
- React Hooks
- React Icons
- Axios
- CSS3 with custom styling
- PropTypes for type checking

### Backend
- Node.js
- Express.js
- SQLite
- JWT Authentication
- Bcrypt for password hashing

## 🌐 Project Structure
```
task-management-application/
│
├── client/ # React Frontend
│   ├── public/
│   └── src/
│       ├── components/
│       │   ├── Auth/
│       │   ├── Tasks/
│       │   └── Common/
│       ├── services/
│       ├── styles/
│       └── App.js
│
└── server/ # Node.js Backend
    ├── config/
    ├── controllers/
    ├── middleware/
    ├── routes/
    └── models/
```

## 🔧 Prerequisites

- Node.js (v14+)
- npm (v6+)

## 💻 Installation

### Clone Repository
```bash
git clone https://github.com/BasavarajuVB/Task-Management-Application.git
cd task-management-application
```

### Backend Setup
```bash
cd server
npm install
```

### Frontend Setup
```bash
cd ../client
npm install
```

### 🔒 Environment Configuration
**Backend (.env)**
```bash
PORT=5000
JWT_SECRET=your_secret_key
```

## 🚀 Running the Application

### Start Backend
```bash
cd server
npm start
```

### Start Frontend
```bash
cd client
npm start
```

## 🌟 Key Components

### Authentication Flow
- `/login`: User authentication
- `/register`: New user registration
- Protected routes with JWT

### Task Management
- Create new tasks
- Update existing tasks
- Delete tasks
- Filter and sort tasks

## 🔍 API Endpoints

### Authentication
- `POST /api/auth/register`
- `POST /api/auth/login`

### Tasks
- `GET /api/tasks`
- `POST /api/tasks`
- `PUT /api/tasks/:id`
- `DELETE /api/tasks/:id`

## 🛡️ Security Features
- Password hashing
- JWT token authentication
- Input validation
- Error handling
- Secure route protection

## 💡 Key React Components
### Authentication
- Login Form
- Registration Form
- Authentication Context

### Tasks
- TaskList
- TaskItem
- TaskForm
- Modal Component

## 🎨 Styling Approach
- CSS Modules
- Responsive Design
- Flexbox and Grid Layouts
- Custom color palette
- Smooth transitions and animations

## 📊 Performance Optimization
- Lazy loading
- Memoization
- Efficient state management
- Minimal re-renders

## 🚧 Future Roadmap
- [ ] Add task priority
- [ ] Implement task categories
- [ ] Create user profile management
- [ ] Add advanced search functionality
- [ ] Implement task sharing

## 🤝 Contribution Guidelines
1. Fork the repository
2. Create feature branch
3. Commit changes
4. Push to branch
5. Open pull request

### Commit Message Convention
- `feat:` New feature
- `fix:` Bug fix
- `docs:` Documentation update
- `style:` Code formatting
- `refactor:` Code restructuring

## 📦 Package Dependencies

### Frontend
- `react`
- `react-dom`
- `react-router-dom`
- `axios`
- `react-icons`
- `prop-types`

### Backend
- `express`
- `sqlite3`
- `jsonwebtoken`
- `bcryptjs`
- `cors`
- `dotenv`

## 📝 License
This project is open-source and available under the MIT License.

## 📞 Contact
**VB Basavaraju**  
Email: bellamvadde0393@gmail.com 
Project Link: [GitHub Repo](https://github.com/BasavarajuVB/Task-Management-Application.git)

## 🌈 Acknowledgements
- Create React App
- Express.js
- React Community
- Open-source contributors
```
