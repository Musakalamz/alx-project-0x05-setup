# 🧩 Project 0x07 — Advance Image Generation App

## 📘 Overview

This task introduces the foundational structure of the **AI Image Generation App**.  
Here, we begin by setting up a **Next.js + TypeScript** application and implementing core layout components — **Header**, **Footer**, and **Layout** — while exploring the fundamentals of **React Hooks**, specifically the `useState` Hook.

This project serves as the starting point for a progressive series (0x07 → 0x13) that builds a complete AI-powered image generation web app.

---

## 🎯 Objectives

- Understand how **React Hooks** manage temporary state in functional components.  
- Set up a **Next.js** project following best practices and modular folder structure.  
- Create and reuse layout components (`Header`, `Footer`, `Layout`).  
- Pass child components using **TypeScript interfaces** for type safety.  
- Run and preview the base layout of the Image Generation App.

---

## ⚙️ Setup Instructions

### 1️⃣ Create the Next.js Project

```bash
npx create-next-app@latest alx-project-0x07 --typescript
cd alx-project-0x07
npm install


---

alx-project-0x07/
├── components/
│   └── layouts/
│       ├── Header.tsx
│       ├── Footer.tsx
│       └── Layout.tsx
├── interfaces/
│   └── index.ts
├── pages/
│   ├── _app.tsx
│   └── index.tsx
└── styles/
    └── globals.css