# 📋 Task Manager

A clean and responsive task manager built with React + Vite, styled using Tailwind CSS, and powered by localStorage. Easily add, update, delete, search, filter, and manage tasks — including overdue tracking!


## 🚀 Live Demo

https://task-management-react-mu.vercel.app/



## 📦Features

- ✅ Create and edit tasks  
- ✅ Mark tasks as Pending or Done  
- ✅ Filter tasks by status: Pending, Done, Overdue  
- ✅ Search by title or description  
- ✅ Paginated task list (5 per page)  
- ✅ LocalStorage persistence  
- ✅ Toast notifications for success/error  
- ✅ Fully responsive design (mobile-friendly)  



## 🛠️ Tech Stack

- ⚛️ React (with Vite)  
- 💨 Tailwind CSS  
- 🧭 React Router  
- 🔔 React Toastify  
- 💾 LocalStorage 


## 📁 Project Structure


```bash
task-manager/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── Pagination.jsx
│   │   ├── SearchBar.jsx
│   │   ├── TaskForm.jsx
│   │   └── TaskTable.jsx
│   ├── hooks/
│   │   └── useForm.js 
│   ├── pages/
│   │   ├── CreateTask.jsx
│   │   ├── EditTask.jsx
│   │   └── Home.jsx
│   ├── utils/
│   │   └── localStorage.js
│   ├── App.jsx
│   ├── main.jsx
│   ├── index.css
│   └── tailwind.config.js
├── postcss.config.js
├── tailwind.config.js
├── package.json
└── vite.config.js
```



##🚀 Getting Started:

1. Clone the repo:
   https://github.com/AkilaJayasurya/Task-management-react.git
   cd task-management-react

2. Install dependencies:
   npm install

3. Run the app locally:
   npm run dev

