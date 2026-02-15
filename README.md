# 🌐 Client - Modern Blog App Frontend

Sample User Interface for the Modern Blog App, built using React, Vite, and TailwindCSS. This frontend interacts seamlessly with the backend API to provide a smooth user experience.

## ✨ Features

- **Responsive Design**: Crafted with [Tailwind CSS](https://tailwindcss.com/) for a sleek, modern look on all devices.
- **Rich Text Editor**: Integrated with [Quill](https://quilljs.com/) for writing and formatting blog posts effortlessly.
- **Authentication**: Secure login and registration using JWT, plus **Google OAuth** integration via `@react-oauth/google`.
- **Admin Dashboard**: dedicated tools for administrators to manage blogs, comments, and view platform statistics.
  - **Blog Management**: Create, edit, delete, and publish blogs.
  - **Comment Moderation**: Review and approve user comments.
- **Dynamic Content**:
  - Blog listing with infinite scroll or pagination (implementation dependent).
  - Detailed blog view with rendered HTML content.
  - Interactive comment section.
- **Notifications**: Real-time feedback using [react-hot-toast](https://react-hot-toast.com/).
- **Animations**: Smooth transitions powered by [Motion](https://motion.dev/).

## 🛠️ Tech Stack

- **Framework**: [React](https://react.dev/) (v19)
- **Build Tool**: [Vite](https://vitejs.dev/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) (v4)
- **Routing**: [React Router](https://reactrouter.com/) (v6)
- **State Management**: Context API
- **HTTP Client**: [Axios](https://axios-http.com/)
- **Utilities**:
  - `marked`: Markdown parsing
  - `moment`: Date formatting
  - `quill`: Rich text editing

## 🚀 Getting Started

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

### 3. Environment Variables

Create a `.env` file in the `client` directory and add the following configuration:

```env
# Backend API URL
VITE_BASE_URL=http://localhost:3000

# Google OAuth Client ID
VITE_GOOGLE_CLIENT_ID=your_google_client_id
```

> **Note:** Ensure `VITE_BASE_URL` points to your running backend server.

### 4. Run Locally

Start the development server:

```bash
npm run dev
```

The application will be available at `http://localhost:5173`.

### 5. Build for Production

To create a production-ready build:

```bash
npm run build
```

To preview the production build locally:

```bash
npm run preview
```

## 📂 Project Structure

```
client/
├── public/              # Static assets
├── src/
│   ├── assets/          # Images, fonts, etc.
│   ├── components/      # Reusable UI components
│   │   ├── admin/       # Admin-specific components
│   │   └── ...
│   ├── context/         # React Context (State Management)
│   ├── pages/           # Application pages (Home, Blog, Admin Dashboard)
│   │   ├── admin/       # Admin pages
│   │   └── ...
│   ├── App.jsx          # Main application component & Routing
│   ├── main.jsx         # Entry point
│   └── index.css        # Global styles & Tailwind imports
├── .env                 # Environment variables
├── index.html           # HTML template
├── package.json         # Dependencies and scripts
├── vite.config.js       # Vite configuration
└── README.md            # Project documentation
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the ISC License.
