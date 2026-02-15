# 🍔 Event-Based Food Ordering Web App (Demo)

A modern, mobile-responsive food ordering web application inspired by food delivery platforms, adapted specifically for **event-based ordering**. This project demonstrates a multi-role, multi-vendor architecture where customers can order food at events, vendors can manage menus, drivers can fulfill deliveries, and admins can oversee the platform.

> ⚠️ This repository contains a **live demo only** (no public source code).  
> The application is deployed on Vercel for demonstration purposes.

👉 Live Demo: https://foodapp-delivery-ruddy.vercel.app/

---

## 🚀 Overview

This project simulates a full event-based food delivery ecosystem with multiple user roles and a scalable frontend architecture. It is designed to showcase UI/UX, state management, and application structure for a production-ready platform.

**Core User Roles:**

- Customers – Browse events & order food  
- Vendors – Manage menus & incoming orders  
- Drivers – Accept and deliver orders  
- Event Organizers – Manage event locations  
- Admin – Platform oversight & management  

---

## 🛠 Core Tech Stack

- **React 18** – UI library  
- **TypeScript** – Type safety across the app  
- **Vite** – Fast build tool & dev server  
- **Tailwind CSS** – Utility-first styling  
- **Framer Motion** – Animations & transitions  
- **Lucide React** – Icon library  
- **Sonner** – Toast notifications  

---

## 📁 Project Architecture

/src
├── main.tsx # App entry point
├── app/App.tsx # Main layout & routing logic
├── app/store.tsx # Global state management (Context API)
├── app/data.ts # Mock data (events, vendors, orders)
├── app/components/ # Reusable UI components
├── app/pages/ # Role-based views & dashboards


---

## 🧠 State Management

Uses **React Context API** for global state.

Key State:

- userRole (customer, vendor, driver, admin)  
- cart (items, quantities, totals)  
- deliveryType (delivery / pickup)  
- orders (active orders & status)  

---

## 🧩 Key Components

- **Navbar** – Address selector, search, role switcher, delivery/pickup toggle  
- **BottomNav** – Mobile-first navigation  
- **DeliveryToggle** – Animated switch between delivery & pickup  
- **ui/** – Buttons, cards, inputs, sheets, badges  

---

## 📄 Pages & Views

### Customer
- Events List  
- Vendor List  
- Menu Page  
- Cart  
- Order Tracking  

### Dashboards
- Vendor Dashboard  
- Driver Dashboard  
- Admin Dashboard  

---

## ✨ Functionality Highlights

- Mobile-first responsive layout  
- Role switching without re-login  
- Smooth animations  
- Cart validation (single-vendor ordering)  
- Real-time style order flow (UI simulation)  
- Modular, scalable architecture  

---

## 🔮 Future Expansion

- Connect to real backend (Supabase / Firebase / custom API)  
- Authentication & user accounts  
- Real-time database & WebSockets  
- Payments integration  
- Push notifications  

---

## 📌 Purpose

This project serves as a **portfolio demo** showcasing frontend architecture, UI/UX design, and system planning for marketplace-style applications.

---

Built for demonstration & portfolio purposes.
