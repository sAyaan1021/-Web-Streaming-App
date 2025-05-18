# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

# 🎬 Web Streaming App

A modern web application for browsing and discovering movies, built with **React**, **Vite**, and **TMDB API**. Users can search, filter, and explore movie details in a sleek, responsive interface.

## 🚀 Features

- 🔍 **Search & Filter** movies by genre and rating
- 📄 **Movie Details** view with extended information
- 🎞️ Clean UI with responsive layout
- ⚡ Built with **Vite** for fast development and build times
- 📦 Component-based architecture using **React**

## 🛠️ Tech Stack

- **Frontend**: React, Vite
- **API**: TMDB (The Movie Database)
- **Styling**: CSS Modules / Tailwind (if included)
- **Tooling**: ESLint, Git

## 📁 Project Structure

web-streaming-app-main/
├── public/ # Static files
├── src/
│ ├── api/ # TMDB API integration
│ ├── components/ # Reusable components (e.g. MovieCard, Header)
│ ├── pages/ # Page-level components (Home, MovieDetails)
│ ├── App.jsx # Main App component
│ └── main.jsx # App entry point
├── index.html # HTML template
├── package.json # Project metadata & dependencies
├── vite.config.js # Vite configuration
└── README.md

