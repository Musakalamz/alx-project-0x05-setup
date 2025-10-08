# 🧩 Project 0x09 — AI Image Generator (GPT-4 Image Generation Integration)

## 📘 Overview

In this project, we extend our **AI Image Generation App** to interact with the **GPT-4 Image Generation API**.  
This task introduces environment variable management for API keys, backend API routes using Next.js, and client–server communication for real-time image generation based on user input.

We’ll first configure our **local environment** to securely handle API keys and then implement a backend endpoint to send prompts to GPT-4 and display AI-generated images in the frontend.

---

## ##️⃣ Task 2 — Set Up Local Environment  
**Mandatory**

### 🎯 Objectives

- Configure a **local environment variable file (`.env.local`)** to securely store the GPT-4 API key.  
- Understand why API keys must remain private and not be exposed in source code.  
- Prepare the base environment for interacting with the GPT-4 Image Generation endpoint.  

---

### ⚙️ Instructions

#### 1️⃣ Duplicate the previous project

Duplicate your existing project from **alx-project-0x08** to a new directory:

```bash
cp -r alx-project-0x08 alx-project-0x09
cd alx-project-0x09