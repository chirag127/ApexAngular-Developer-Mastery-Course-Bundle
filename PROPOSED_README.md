# AngularCore Enterprise Website Template

[![Build Status](https://img.shields.io/github/actions/workflow/status/your-username/your-repo/ci.yml?branch=main&style=flat-square&label=build)](https://github.com/your-username/your-repo/actions/workflows/ci.yml)
[![License](https://img.shields.io/github/license/your-username/your-repo?color=informational&style=flat-square)](LICENSE)
[![TypeScript](https://img.shields.io/badge/Language-TypeScript-blue?style=flat-square&logo=typescript)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-v7-purple?style=flat-square&logo=vite)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v4-blue?style=flat-square&logo=tailwind-css)](https://tailwindcss.com/)

A modern, frontend-only, AI-native enterprise website template built with Vite, TypeScript, and Tailwind CSS. This template is designed for high-performance, scalable, and maintainable web applications, adhering to the principles outlined in `AGENTS.md`.

## ✨ Features

*   **Frontend-Only Architecture:** No backend required. All logic runs in the browser, making it easy to deploy and scale.
*   **AI-Native:** Designed for easy integration with large language models and other AI services.
*   **Modern Tech Stack:** Vite, TypeScript, and Tailwind CSS for a fast, modern, and enjoyable development experience.
*   **Spatial-Adaptive UI:** A modern user interface that adapts to different screen sizes and devices.
*   **User-Provided API Keys:** Users can bring their own API keys for AI services, ensuring security and control.
*   **Static Hosting:** Deployable to any static hosting provider, such as GitHub Pages, Vercel, or Netlify.

## 🚀 Getting Started

### Prerequisites

*   Node.js (v18 or higher)
*   npm (v9 or higher)

### Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/your-repo.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd your-repo
    ```
3.  Install the dependencies:
    ```bash
    npm install
    ```

### Development

To start the development server, run the following command:

```bash
npm run dev
```

This will start the Vite development server and open the application in your default browser.

### Build

To build the application for production, run the following command:

```bash
npm run build
```

This will create a `dist` directory with the production-ready files.

##  architectural-principles-the-laws-of-physics Architectural Principles

This project adheres to the architectural principles outlined in the `AGENTS.md` file, including:

*   **Frontend-Only:** All code runs in the browser.
*   **Direct API Calls:** AI services are called directly from the frontend using REST APIs.
*   **User-Provided Keys:** API keys are provided by the user at runtime.
*   **Client-Side Processing:** All data processing and state management is done on the client.
*   **Static Hosting:** The application is designed to be deployed to a static hosting provider.

## 📜 License

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International Public License (CC BY-NC 4.0). See the [LICENSE](LICENSE) file for more details.
