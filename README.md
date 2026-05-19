# ✅ Next.js Todo App

A modern and responsive **Todo Application** built using **Next.js**, **TypeScript**, and **MongoDB**.  
This project helps users manage daily tasks efficiently with full CRUD functionality and persistent database storage.

# 🚀 Tech Stack

| Technology | Purpose |
|------------|----------|
| Next.js | Frontend & Backend Framework |
| TypeScript | Type Safety |
| MongoDB | Database Storage |
| Mongoose | MongoDB ODM |
| Tailwind CSS | Styling |
| React Hooks | State Management |

# ✨ Features

## 📝 Task Management
- Add new tasks
- Edit existing tasks
- Delete tasks
- Mark tasks as completed
- View pending/completed tasks

## 💾 Database Integration
- MongoDB database storage
- Persistent task saving
- Real-time CRUD operations

## ⚡ Modern UI
- Responsive design
- Clean interface
- Fast navigation
- Interactive components

## 🔒 Type Safety
- Fully built with TypeScript
- Strong typing for APIs and components

# 📂 Project Structure

```bash
todo-app/
│
├── app/
│   ├── api/
│   │   └── tasks/
│   ├── components/
│   ├── page.tsx
│   └── layout.tsx
│
├── lib/
│   └── mongodb.ts
│
├── models/
│   └── Task.ts
│
├── public/
├── styles/
├── .env.local
├── package.json
└── README.md
```

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/nextjs-todo-app.git
```

## 2️⃣ Navigate to Project

```bash
cd nextjs-todo-app
```

## 3️⃣ Install Dependencies

```bash
npm install
```

# 🍃 MongoDB Setup

Create a `.env.local` file in the root directory:

```env
MONGODB_URI=your_mongodb_connection_string
```

Example:

```env
MONGODB_URI=mongodb+srv://username:password@cluster.mongodb.net/todo-app
```

# ▶️ Run Development Server

```bash
npm run dev
```

Open:

```bash
http://localhost:3000
```

# 📡 API Routes

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/tasks` | Fetch all tasks |
| POST | `/api/tasks` | Create new task |
| PUT | `/api/tasks/:id` | Update task |
| DELETE | `/api/tasks/:id` | Delete task |

# 📦 Dependencies

```bash
npm install mongoose
```

```bash
npm install -D typescript @types/node @types/react
```

# 🎨 UI Features

- Mobile responsive layout
- Task completion toggle
- Loading states
- Empty state handling
- Modern card-based design

# 🔥 Upcoming Features

- 🔐 User Authentication
- 🌙 Dark Mode
- 📅 Due Dates & Reminders
- 🏷️ Task Categories
- 📊 Productivity Dashboard
- 🔔 Notifications
- ☁️ Cloud Sync
- 📱 PWA Support
- 👥 Multi-user Collaboration

# ☁️ Deployment

## Frontend Deployment
Recommended platforms:

- Vercel
- Netlify

## Database Hosting
- MongoDB Atlas

# 🛠️ Build for Production

```bash
npm run build

# 📸 Screenshots

_Add project screenshots here_

# 👨‍💻 Author

Developed using:

- Next.js
- TypeScript
- MongoDB
- Tailwind CSS

# 📄 License

This project is licensed under the MIT License.

# ⭐ Support

If you like this project, give it a ⭐ on GitHub.

---
