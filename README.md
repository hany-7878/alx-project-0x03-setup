<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/2ac6b4f6-8540-4833-a55e-39dd5557f455" />
# 🌊 Splash App — Next.js Project

A modern **Next.js** application built to demonstrate real-world web development practices including shared layouts, component architecture, routing, responsive UI, and TypeScript integration. This project serves as a solid foundation for building scalable AI-powered applications.

---

## 🚀 Project Overview

Splash App is designed to show how professional applications are structured.
It focuses on:

* Clean and reusable components
* Consistent layout using DRY principles
* Imperative routing with Next.js
* Type-safe development using TypeScript
* Responsive, modern UI with Tailwind CSS
* Custom 404 pages for improved user experience

This foundation can easily be extended to build AI tools like:

* Text generation apps
* Text-to-image applications
* Interactive AI dashboards

---

## 🎯 Learning Objectives

* Implement shared layouts (Header, Footer, Layout)
* Use Google Fonts inside Tailwind global styles
* Build reusable UI components (Button)
* Use TypeScript interfaces for maintainability
* Organize project files for scalable development
* Implement imperative routing with `useRouter`
* Create custom 404 error pages
* Ensure responsive design across multiple screen sizes

---

## 📚 Key Concepts Covered

### 🧱 Layout Components

Reusable components structured under:

```
components/layouts/
- Header.tsx
- Footer.tsx
- Layout.tsx
```

### 🎨 Component Architecture

Reusable UI elements like:

```
components/common/Button.tsx
```

### 🔀 Routing

* Declarative routing with `<Link>`
* Imperative routing using `useRouter().push()`

### 💅 Styling

* Tailwind CSS
* Google Fonts (Montserrat)
* Responsive classes

### 🛡️ TypeScript

* Interface extraction
* Centralized interface management
* Strict type safety

### ❌ Error Handling

Custom 404 page (`pages/404.tsx`) with styling and icons.

---

## 🛠️ Tools & Libraries

| Tool             | Purpose                              |
| ---------------- | ------------------------------------ |
| **Next.js**      | File-based routing, server rendering |
| **Tailwind CSS** | Fast UI styling                      |
| **TypeScript**   | Type-safe development                |
| **React Icons**  | Icon support                         |
| **Google Fonts** | Custom font integration              |

---

## 🗂️ Project Structure

```
alx-project-0x03/
├── components/
│   ├── common/
│   │   └── Button.tsx
│   └── layouts/
│       ├── Header.tsx
│       ├── Footer.tsx
│       └── Layout.tsx
├── interfaces/
│   └── index.ts
├── pages/
│   ├── index.tsx
│   └── 404.tsx
├── styles/
│   └── global.css
└── (other Next.js files)
```

---

## 📌 Features Implemented

### 1️⃣ Shared Layout (Header, Footer, Layout)

All pages share a consistent layout using the Layout component.

### 2️⃣ Custom Google Font

Montserrat imported globally in `global.css`.

### 3️⃣ Imperative Routing

Homepage buttons navigate using:

```ts
router.push("/page-name")
```

### 4️⃣ Organized Interfaces

All interfaces moved to `interfaces/index.ts`.

### 5️⃣ Custom 404 Page

Friendly error page with icons and gradient background.

---

## ▶️ Getting Started

### **1. Clone the repository**

```bash
git clone https://github.com/<your-username>/alx-project-0x03-setup
```

### **2. Install dependencies**

```bash
npm install
```

### **3. Run the development server**

```bash
npm run dev
```

### **4. Open in browser**

```
http://localhost:3000
```

If you'd like, I can also **generate a custom GitHub banner image** for your README.
