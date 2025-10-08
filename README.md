# 🧠 ProDev Frontend — HookMastery: Unleashing the Power of Hooks

A modular and responsive **AI Image Generation Web Application** built with **Next.js**, **TypeScript**, and **Tailwind CSS**.  
This project demonstrates the power of **React Hooks**, **custom hooks**, and **API integration** using the **GPT-4 Image Generation API**.  
It evolves across multiple stages (0x07 → 0x13), each introducing advanced frontend development concepts and best practices.

---

## 🚀 Overview

This multi-stage project enables users to generate **AI-powered images** from natural language prompts.  
It integrates securely with the **GPT-4 Image Generation API** through Next.js API routes.

Each phase progressively introduces:
- React state management and interactivity  
- Secure environment variables  
- API request handling  
- Image gallery and history tracking  
- Custom hooks for reusable data fetching logic  

---

## 🧩 Repository Structure

### 📁 Root Layout
The repository is organized into multiple project directories, each representing a progressive version of the same application.

- **`alx-project-0x07/`** — Base setup with Next.js, TypeScript, and Tailwind CSS.  
- **`alx-project-0x08/`** — Introduces `useState` for prompt and image state management.  
- **`alx-project-0x09/`** — Adds environment variables for secure API key handling.  
- **`alx-project-0x10/`** — Implements GPT-4 Image Generation API route.  
- **`alx-project-0x11/`** — Adds image tracking and dynamic gallery display.  
- **`alx-project-0x12/`** — Introduces a reusable custom hook (`useFetchData`).  
- **`alx-project-0x13/`** — Final refactored and production-ready version.

---

### 📂 Detailed Folder Structure

```text
alx-project-0x07-setup/
│
├── alx-project-0x07/               # Base layout and setup
│   ├── components/
│   │   └── layouts/
│   │       ├── Header.tsx
│   │       ├── Footer.tsx
│   │       └── Layout.tsx
│   ├── interfaces/
│   │   └── index.ts
│   ├── pages/
│   │   ├── _app.tsx
│   │   └── index.tsx
│   ├── styles/
│   │   └── globals.css
│   └── README.md
│
├── alx-project-0x08/               # Adds state management with useState
│   ├── components/
│   │   ├── common/
│   │   │   └── ImageCard.tsx
│   │   └── layouts/
│   │       ├── Header.tsx
│   │       ├── Footer.tsx
│   │       └── Layout.tsx
│   ├── interfaces/
│   │   └── index.ts
│   ├── pages/
│   │   └── index.tsx
│   └── styles/
│       └── globals.css
│
├── alx-project-0x09/               # Introduces environment configuration
│   ├── constants/
│   │   └── index.ts
│   ├── pages/
│   │   └── index.tsx
│   └── .env.local (example)
│
├── alx-project-0x10/               # GPT-4 API integration
│   ├── pages/
│   │   ├── api/
│   │   │   └── generate-image.ts
│   │   └── index.tsx
│   ├── constants/
│   │   └── index.ts
│   └── interfaces/
│       └── index.ts
│
├── alx-project-0x11/               # Image history and gallery management
│   ├── components/
│   │   └── common/
│   │       └── ImageCard.tsx
│   ├── pages/
│   │   └── index.tsx
│   └── styles/
│       └── globals.css
│
├── alx-project-0x12/               # Custom hook (useFetchData) abstraction
│   ├── hooks/
│   │   └── useFetchData.ts
│   ├── pages/
│   │   └── index.tsx
│   ├── interfaces/
│   │   └── index.ts
│   └── styles/
│       └── globals.css
│
└── alx-project-0x13/               # Final refactored implementation
    ├── components/
    │   ├── common/
    │   │   └── ImageCard.tsx
    │   └── layouts/
    │       ├── Header.tsx
    │       ├── Footer.tsx
    │       └── Layout.tsx
    ├── constants/
    │   └── index.ts
    ├── hooks/
    │   └── useFetchData.ts
    ├── interfaces/
    │   └── index.ts
    ├── pages/
    │   ├── api/
    │   │   └── generate-image.ts
    │   ├── _app.tsx
    │   └── index.tsx
    ├── public/
    ├── styles/
    │   └── globals.css
    └── README.md

---

## ⚙️ Tech Stack

| Category | Tools & Libraries |
|-----------|------------------|
| **Framework** | [Next.js 13+](https://nextjs.org/) |
| **Language** | [TypeScript](https://www.typescriptlang.org/) |
| **Styling** | [Tailwind CSS](https://tailwindcss.com/) |
| **API Integration** | [GPT-4 Image Generation API](https://rapidapi.com) via RapidAPI |
| **State Management** | React Hooks (`useState`, `useEffect`, Custom Hooks) |
| **Deployment Ready** | Supports `.env.local`, API routes, and responsive layout |

---

## 🧠 Learning Objectives

By completing this multi-stage project, you will:
- Understand and apply React’s core Hooks (`useState`, `useEffect`)
- Create and manage reusable **custom hooks**
- Work securely with **environment variables** in Next.js
- Implement **API routes** for backend integration
- Manage and render **dynamic application state**
- Structure scalable and maintainable React applications
- Develop **responsive UIs** with Tailwind CSS
- Ensure **type safety** across components and API responses

---

## 🪄 Key Features

- 🧩 **Text-to-Image Generation:** Create AI-generated images from user text prompts  
- 🔁 **Dynamic State Management:** Track and display generated images in real-time  
- 🧠 **Custom Hooks:** Centralize and reuse API-fetching logic  
- 💾 **Environment Security:** Protect API keys using `.env.local`  
- 🧱 **Clean Architecture:** Reusable components, modular structure, and TypeScript interfaces  
- 📱 **Responsive UI:** Works seamlessly across devices with Tailwind CSS  

---

## 🔐 Environment Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/alx-project-0x07-setup.git
   cd alx-project-0x07-setup 

