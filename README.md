# 🍽️ Multi-Restaurant Food Delivery Website

A full-stack food delivery platform where users can browse multiple restaurants, explore menus, add items to their cart, place orders, and track delivery in real-time — all through a smooth and modern web experience.

---

## 🚀 Features

- 🏪 **Multi-Restaurant Support** — Browse and order from various restaurants.
- 🍕 **User Registration & Secure Login**
- 📖 **Restaurant & Food Menu Browsing**
- 🛒 **Cart System with Quantity Control**
- 💳 **Order Placement & Payment Workflow**
- 📦 **Order History & Live Status Tracking**
- 💬 **Feedback System** — Available only for delivered orders.
- 🧑‍💻 **Role-based Dashboards**
  - Customer Frontend
  - Restaurant Partner Panel
  - Admin Panel for managing restaurants, orders, and users.
- 💡 **Fully Responsive Design** for mobile and desktop.

---

## ⚙️ Tech Stack

- **Frontend**: React.js, Tailwind CSS, Axios, React Router
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose ODM)
- **Authentication**: JWT (JSON Web Token)

---

## 💻 Installation

1. **Clone the repository**

```bash
git clone https://github.com/avipatel2004/QuickBites-Food-Delivery-Website
```

2. **Install dependencies for each part**

```bash
cd Backend
npm install

cd ../Client_Frontend
npm install

cd ../Admin_Frontend
npm install

cd ../Restaurant_Frontend
npm install
```

3. **Run all development servers**

```bash
cd Backend
npm run dev

cd ../Client_Frontend
npm run dev

cd ../Admin_Frontend
npm run dev

cd ../Restaurant_Frontend
npm run dev
```

---

## 📂 Project Structure

```
├── Admin_Frontend/           # Admin Dashboard for platform management
├── Client_Frontend/          # Customer Application (Multiple Restaurant Browser)
├── Restaurant_Frontend/      # Restaurant Partner Panel (Order & Menu management)
├── Backend/                  # Node.js API Server (Authentication, Orders, Payments, Feedback)
```

Happy Coding! 🚀
