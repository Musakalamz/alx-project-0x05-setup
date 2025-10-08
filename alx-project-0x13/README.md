# 🧠 Image Generation App — Custom Hook  
**Project:** Application of State (Reusable Logic with Custom Hooks)  
**Directory:** `alx-project-0x12`  
**Repository:** `alx-project-0x05-setup`  

---

## 📘 Overview  
In this stage, we refactor our image generation app to use a **custom React hook**.  
By creating a custom hook named **`useFetchData`**, we extract the API request logic into a reusable function that can be used across multiple components.  

This approach improves **code organization**, **reusability**, and **maintainability**, making the application cleaner and easier to extend.  

---

## 🎯 Objectives  
- Create a **custom React hook** to handle API requests.  
- Refactor the main component to use the custom hook.  
- Maintain dynamic state for loading, error, and image data.  
- Track and display previously generated images.  

---
## 🧱 Folder Structure

alx-project-0x12/
├── components/
│   └── common/
│       └── ImageCard.tsx
│   └── layouts/
│       ├── Header.tsx
│       ├── Footer.tsx
│       └── Layout.tsx
├── constants/
│   └── index.ts
├── hooks/
│   └── useFetchData.ts   ← (New custom hook)
├── interfaces/
│   └── index.ts
├── pages/
│   ├── api/
│   │   └── generate-image.ts
│   ├── _app.tsx
│   └── index.tsx         ← (Modified file)
├── public/
├── styles/
│   └── globals.css
├── .env.local
├── .gitignore
├── package.json
└── README.md

---

## 🧩 Project Setup  

### 1️⃣ Duplicate Previous Project  
Duplicate the existing project `alx-project-0x11` to a new directory called `alx-project-0x12`:  
```bash
cp -r alx-project-0x11 alx-project-0x12