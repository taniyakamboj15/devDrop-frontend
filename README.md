# DevDrop Frontend

This is the frontend client for **DevDrop**, a modern, responsive, real-time file-sharing application designed for seamless user experience. It interacts with the DevDrop backend to provide secure authentication and instant file transfer capabilities.

## Backend Repository

The backend server for DevDrop (Node.js + Express + TypeScript + Socket.io) is available here:

🔗 https://github.com/taniyakamboj15/devDrop-backend


## Features

-   **Modern UI/UX**: Built with React and Tailwind CSS for a sleek, responsive design.
-   **Theme Support**: Fully integrated Dark/Light mode switcher.
-   **Authentication Flow**:
    -   Complete Signup/Login pages with validation.
    -   Forgot/Reset Password flows.
    -   Protected Routes ensuring only authenticated access to core features.
-   **File Sharing Dashboard**:
    -   **Drag & Drop Upload**: Intuitive upload panel.
    -   **Real-time Progress**: Visual progress bar for active uploads.
    -   **User Selection**: Dropdown to select specific online users for private sharing or broadcast to all.
    -   **Live Feed**: Instant updates when new files are shared.
-   **State Management**: Redux Toolkit for managing auth state and global app data.
-   **Real-time Updates**: Socket.io client integration for live user status and file notifications.

## Tech Stack

-   **Framework**: React (Vite)
-   **Language**: TypeScript
-   **Styling**: Tailwind CSS
-   **State Management**: Redux Toolkit
-   **Routing**: React Router DOM (v6+)
-   **HTTP Client**: Axios
-   **Real-time**: Socket.io-client
-   **Icons**: Lucide React

## Folder Structure

```
src/
├── components/      # Reusable UI components (Navbar, Button, etc.)
│   ├── fileshare/   # Specific components for file sharing feature
│   └── icons/       # SVG Icon components
├── context/         # React Contexts (Theme, Toast, Socket)
├── hooks/           # Custom hooks (useFileUpload, useAuth, etc.)
├── pages/           # Main page views (Login, Profile, FileShare)
├── slices/          # Redux slices (authSlice)
├── store.ts         # Redux store configuration
└── utils/           # Helper functions
```

## Installation

1.  Navigate to the frontend directory:
    ```bash
    cd frontend
    ```
2.  Install dependencies:
    ```bash
    npm install
    ```

## Running the App

-   **Development Server**:
    ```bash
    npm run dev
    ```
    The app will typically run at `http://localhost:5173`.

-   **Build for Production**:
    ```bash
    npm run build
    ```
    The output will be in the `dist` folder.

