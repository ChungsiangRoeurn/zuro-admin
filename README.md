# 🚀 Modern Admin Dashboard (React + TailwindCSS)

A fully responsive and modern **Admin Dashboard UI** built using **ReactJS**, **TailwindCSS**, and **React Icons**.

This project focuses on clean architecture, reusable components, responsive layout, and a toggleable sidebar for better user experience.

---

![image alt](https://github.com/ChungsiangRoeurn/ReactJS_Tailwind_Dashboard/blob/458d311c47f95e36a7d8156d3e1917a6546fce83/image_demo.png)

## ✨ Features

* 🔐 Login & Register UI (Static for now)
* 🖥 Modern Admin Dashboard UI
* 📱 Fully Responsive Design
* 🎨 Clean & Professional Layout
* 📂 Collapsible / Toggle Sidebar
* 🎯 Active Route Highlighting
* 🌙 Smooth Transitions & Animations
* 🔧 Reusable Components Structure

> Note: Authentication is currently static. You can directly access the admin panel via `/admin` route.

---

## 🛠 Tech Stack

* **ReactJS** – Frontend Library
* **React Router DOM** – Routing System
* **TailwindCSS** – Utility-first CSS Framework
* **React Icons** – Icon Library

---

## 📁 Project Structure

```
src/
│
├── assets/
│   ├── images/
│   ├── gifs/
│   └── icons/
│
├── api/
│   ├── axios.ts          # axios instance
│   ├── auth.api.ts
│   ├── product.api.ts
│   ├── order.api.ts
│   └── user.api.ts
│
├── types/
│   ├── auth.types.ts
│   ├── product.types.ts
│   ├── order.types.ts
│   └── user.types.ts
│
├── services/
│   ├── auth.service.ts
│   ├── product.service.ts
│   └── order.service.ts
│
├── components/
│   ├── layout/
│   │   ├── Header.tsx
│   │   └── Sidebar.tsx
│   │
│   └── ui/
│       ├── Button.tsx
│       ├── Card.tsx
│       └── Input.tsx
│
├── layouts/
│   ├── AdminLayout.tsx
│   └── AuthLayout.tsx
│
├── pages/
│   ├── auth/
│   │   ├── Login.tsx
│   │   └── Register.tsx
│   │
│   ├── admin/
│   │   ├── Dashboard.tsx
│   │   ├── Stores.tsx
│   │   ├── Products.tsx
│   │   ├── Users.tsx
│   │   ├── Orders.tsx
│   │   └── Settings.tsx
│   │
│   └── Home.tsx
│
├── routes/
│   └── AppRoutes.tsx
│
├── utils/
│   └── helpers.ts
│
├── App.tsx
├── main.tsx
└── index.css
```

This structure keeps the project simple and organized:

* `components/` → Reusable layout components like Header and Sidebar
* `layouts/` → Layout wrappers such as AdminLayout
* `pages/admin/` → All admin dashboard pages
* `pages/` → Public pages like Login, Register, and Home
* `assets/` → Static resources (images, GIFs, etc.)

---

## 🔐 Authentication (Static)

Currently:

* Login & Register pages are UI only.
* No backend authentication yet.
* You can manually navigate to:

```
/admin
```

to access the admin dashboard.

Future improvement:

* JWT Authentication
* Protected Routes
* Role-based Access Control

---

## 🧭 Sidebar Features

* Toggle open / close
* Smooth width transition
* Icon-only mode when collapsed
* Active route highlight
* Logout button
* User info section

---

## 📱 Responsive Design

This dashboard is fully responsive:

* Desktop → Full sidebar
* Tablet → Collapsible sidebar
* Mobile → Compact layout

Built using Tailwind’s responsive utilities.

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/ChungsiangRoeurn/ReactJS_Tailwind_Dashboard
cd ReactJS_Tailwind_Dashboard
```

### 2️⃣ Install Dependencies

```bash
pnpm install
```

or

```bash
yarn install
```

### 3️⃣ Start Development Server

```bash
pnpm dev
```

or

```bash
pnpm start
```

---

## 🎨 UI Highlights

* Gradient overlays
* Background GIF effects for dynamic visuals
* Glassmorphism design elements
* Smooth hover animations
* Clean spacing & typography
* Modern toggle sidebar interaction

---

## 🎥 Animated GIF Background

This project uses **animated GIF backgrounds** in both the Header and Sidebar to create a modern and dynamic UI experience.

### Why GIF Background?

* Adds movement and depth to the interface
* Makes the dashboard feel futuristic and alive
* Enhances visual engagement without heavy animation libraries
* Combined with dark overlay (`bg-black/60`, `bg-black/70`) for better readability

### Implementation Strategy

* GIF is placed using `position: absolute`
* Overlay layer added for contrast
* Content wrapped inside `relative z-10`
* Uses `object-cover` for full coverage
* Optimized for responsiveness

This approach keeps the UI modern while maintaining performance and clean structure.

---

## 🔮 Future Improvements

* Backend Integration (Node.js / Laravel / NestJS)
* Database Integration
* Real Authentication System
* Dashboard Charts (Recharts / Chart.js)
* Dark Mode Toggle
* API Data Integration

---

## 👨‍💻 Author

**Chungsiang Roeurn**
Full Stack Developer | React Enthusiast

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!

---

### 💡 Built with passion for modern UI and clean frontend architecture.
