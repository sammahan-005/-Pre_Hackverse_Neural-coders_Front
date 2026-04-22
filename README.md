# 🎓 StudyHub - Frontend

Welcome to the **StudyHub** frontend! This is a premium, high-performance web application designed for academic mutual aid. It features a modern, glassmorphic design system and a seamless user experience for managing academic requests and community knowledge sharing.

[![React](https://img.shields.io/badge/React-19.0-blue?style=for-the-badge&logo=react)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-8.0-646CFF?style=for-the-badge&logo=vite)](https://vitejs.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-6.0-blue?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![React Router](https://img.shields.io/badge/React_Router-7.0-CA4245?style=for-the-badge&logo=react-router)](https://reactrouter.com/)

---

## ✨ Features

- **Interactive Feed**: A dynamic, real-time feed of academic requests with intelligent sorting (Priority Score).
- **Request Lifecycle**: Full management of academic problems — from publication to "Best Answer" selection.
- **Reputation Dashboard**: Personal user profiles featuring reputation breakdown, statistics, and favorite subjects.
- **Real-time Interaction**: Integrated voting system (Upvote/Downvote) for quality control.
- **Premium UX**: 
  - **Glassmorphism Design**: Sleek, modern interface with subtle transparency and blur effects.
  - **Loading Skeletons**: Smooth perceived performance with custom-built skeleton loaders.
  - **Theming**: Full support for Dark/Light modes based on user preference.
  - **Responsive Layout**: Optimized for both desktop and mobile viewing.

---

## 🛠️ Tech Stack

- **Framework**: [React 19](https://react.dev/)
- **Build Tool**: [Vite](https://vitejs.dev/)
- **Routing**: [React Router 7](https://reactrouter.com/en/main)
- **Icons**: [Lucide React](https://lucide.dev/)
- **API Client**: Axios
- **Styling**: Vanilla CSS with custom design tokens (Academic Indigo theme).

---

## 🚀 Quick Start

### 1. Prerequisites
Ensure you have the [StudyHub Backend](file:///home/mahan-samuel/Bureau/Projets/Hackathon/Api_hackathon) running first.

### 2. Installation
```bash
# Install dependencies
npm install

# Start the development server
npm run dev
```

### 3. Environment Setup
The frontend expects the API to be running at `http://localhost:3333`. You can configure this in your API utility files.

---

## 📂 Project Structure

- `src/api`: API service layer and Axios interceptors.
- `src/components`: Reusable UI components (Buttons, Modals, Cards, Skeletons).
- `src/context`: React Context for Authentication and global state.
- `src/pages`: Main application views (Feed, Profile, RequestDetail).
- `src/styles`: Global styles, CSS variables, and design tokens.
- `src/types`: TypeScript interfaces and type definitions.

---

## 🎨 Design System

StudyHub uses a custom design system based on an **Academic Indigo & Amber** palette.

- **Primary**: Indigo (`#6366f1`) - Trust and Academic focus.
- **Secondary**: Amber (`#f59e0b`) - Attention and Achievement.
- **Background**: Deep Space (`#0c0f1a`) for Dark Mode.
- **Glass**: Semi-transparent overlays with `backdrop-filter: blur(12px)`.

---

Made with ❤️ for the Hackathon.

