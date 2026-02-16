# 🌐 Modern Blog App Frontend

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge)](https://blog-app-frontend-liart-omega.vercel.app/)
[![Backend Repo](https://img.shields.io/badge/Backend-Repository-blue?style=for-the-badge)](https://github.com/Abhi6294-jais/Blog-app-backend)

A stunning, responsive, and feature-rich frontend for a modern blogging platform. Built with **React**, **Vite**, and **Tailwind CSS**, this application provides a seamless user experience for reading, writing, and managing blogs.

It is fully integrated with a robust backend (Dockerized & deployed) and leverages AI for content generation.

---

## 🚀 Live Demo

- **Frontend (UI):** [https://blog-app-frontend-liart-omega.vercel.app/](https://blog-app-frontend-liart-omega.vercel.app/)
- **Backend API:** [https://blog-app-frontend-ap4s.vercel.app/](https://blog-app-frontend-ap4s.vercel.app/)

---

## ✨ Features

- **🎨 Modern & Responsive Design**: Crafted with [Tailwind CSS](https://tailwindcss.com/) for a sleek look across all devices (Mobile, Tablet, Desktop).
- **✍️ Rich Text Editor**: Integrated [Quill](https://quilljs.com/) editor for effortless blog writing and formatting.
- **🔐 Secure Authentication**:
  - Google OAuth integration for one-click login.
  - Email/Password authentication using JWT.
- **🤖 AI-Powered Writing**: Generate blog content automatically using **Google Gemini AI** directly from the editor.
- **🛡️ Admin Dashboard**:
  - Manage all blogs (Edit, Delete, Publish/Unpublish).
  - Comment moderation system (Approve/Delete user comments).
  - view platform statistics.
- **💬 Interactive Comments**: Engage with users through a comment system.
- **⚡ High Performance**: Optimized build with Vite and smooth animations using [Motion](https://motion.dev/).

---

## 🛠️ Tech Stack

- **Framework**: [React](https://react.dev/) (v19)
- **Build Tool**: [Vite](https://vitejs.dev/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) (v4)
- **State Management**: React Context API
- **Routing**: [React Router](https://reactrouter.com/) (v6)
- **HTTP Client**: [Axios](https://axios-http.com/)
- **Utilities**: `marked` (Markdown), `moment` (Dates), `react-hot-toast` (Notifications)

---

## 🔗 Backend Integration

This frontend is designed to work with the **Modern Blog App Backend**.

- **Repository**: [github.com/Abhi6294-jais/Blog-app-backend](https://github.com/Abhi6294-jais/Blog-app-backend)
- **Features**: Dockerized, AWS Ready, Gemini AI, ImageKit Storage, MongoDB.

---

## 🚀 Getting Started Locally

Follow these steps to set up the project locally.

### Prerequisites

- **Node.js** (v18 or higher)
- **npm** or **yarn**

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/blog-app-frontend.git
cd blog-app-frontend/client
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Environment Configuration

Create a `.env` file in the `client` root directory. You can point `VITE_BASE_URL` to the live backend or your local backend server.

```env
# Point to the live backend or http://localhost:3000 for local dev
VITE_BASE_URL="https://blog-app-frontend-ap4s.vercel.app"

# Google OAuth Client ID (Required for Login)
VITE_GOOGLE_CLIENT_ID="your_google_client_id"
```

### 4. Run Development Server

```bash
npm run dev
```

The app will be available at `http://localhost:5173`.

---

## 📂 Project Structure

```
client/
├── public/              # Static assets
├── src/
│   ├── assets/          # Images, fonts
│   ├── components/      # Reusable UI (Navbar, Footer, BlogCards)
│   ├── context/         # App State (Auth, Blog Data)
│   ├── pages/           # Pages (Home, BlogDetails, Admin Dashboard)
│   ├── App.jsx          # Routing Setup
│   └── main.jsx         # Entry Point
├── .env                 # Env variables
└── vite.config.js       # Vite Config
```

## 🤝 Contributing

Contributions are welcome! Please fork the repo, create a feature branch, and submit a Pull Request.

## 📄 License

This project is licensed under the ISC License.
