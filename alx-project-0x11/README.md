# 🧠 Image Generation App — Track Images Generated  
**Project:** Application of State (Advanced State Management)  
**Directory:** `alx-project-0x11`  
**Repository:** `alx-project-0x05-setup`  

---

## 📘 Overview
This stage of the **Image Generation App** focuses on enhancing the user experience by **tracking all images generated** during a session. Using React’s `useState` hook, we now store a history of generated images dynamically.  
Each new image generated from the user’s prompt is displayed immediately and also added to a **scrollable thumbnail gallery**, allowing users to revisit previously generated images easily.  

---

## 🎯 Objectives
- Extend the app to **maintain a history of generated images**.
- Use React hooks (`useState`) to manage dynamic state changes.
- Display previously generated images in a responsive grid layout.
- Allow users to **click on thumbnails** to re-display an image.

---

## 🧩 Project Setup
### 1. Duplicate the Previous Project
Duplicate the existing project **`alx-project-0x10`** to create a new directory called **`alx-project-0x11`**:
```bash
cp -r alx-project-0x10 alx-project-0x11

---

## 🧱 Folder Structure 

alx-project-0x11/
├── components/
│   └── common/
│       └── ImageCard.tsx
│   └── layouts/
│       ├── Header.tsx
│       ├── Footer.tsx
│       └── Layout.tsx
├── constants/
│   └── index.ts
├── interfaces/
│   └── index.ts
├── pages/
│   ├── api/
│   │   └── generate-image.ts
│   ├── _app.tsx
│   └── index.tsx  ← (Modified file)
├── public/
├── styles/
│   └── globals.css
├── .env.local
├── .gitignore
├── package.json
└── README.md 