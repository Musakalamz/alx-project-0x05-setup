# 🧩 Project 0x08 — Application of State

## 📘 Overview

This project builds upon the previous task **(Project 0x07 — Advance Image Generation App)** by introducing **React state management** using the `useState` hook.  

Here, we enhance the app to dynamically track user input (prompt), generated images, and loading state — creating a more interactive and responsive user interface.

You’ll learn how to manage multiple states within a React component and display dynamic content based on these states.

---

## 🎯 Objectives

- Duplicate and extend your previous project (`alx-project-0x07`) to `alx-project-0x08`.  
- Use the **React `useState` Hook** to manage multiple dynamic states:
  - `prompt` (text input value)
  - `imageUrl` (generated image link)
  - `generatedImages` (list of generated results)
  - `isLoading` (loading indicator)
- Implement a reusable **ImageCard** component.
- Pass and manage component props using **TypeScript interfaces** for type safety.
- Render UI dynamically based on component states.

---

## ⚙️ Project Setup

### 1️⃣ Duplicate Previous Project

Duplicate your previous project directory:

```bash
cp -r alx-project-0x07 alx-project-0x08
cd alx-project-0x08
npm install


---

Project Structure


alx-project-0x08/
├── components/
│   ├── common/
│   │   └── ImageCard.tsx
│   └── layouts/
│       ├── Header.tsx
│       ├── Footer.tsx
│       └── Layout.tsx
├── interfaces/
│   └── index.ts
├── pages/
│   ├── _app.tsx
│   └── index.tsx
├── styles/
│   └── globals.css
├── package.json
└── README.md
