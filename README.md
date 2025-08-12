# 🍕 Papa Gino's Pizza - Full Stack Application

A modern full-stack pizza ordering application featuring a React frontend and Fastify API backend. This project demonstrates best practices in modern web development with a complete pizza restaurant ordering system.

## 🏗 Project Structure

```
├── api/                    # Backend API server
│   ├── server.js          # Fastify server with SQLite database
│   ├── pizza.sqlite       # Pizza menu and orders database
│   └── public/            # Static assets (images, fonts, styles)
└── Padre-Ginos/           # Frontend React application
    ├── src/               # React components and routes
    └── index.html         # Main HTML entry point
```

## 🚀 Features

- **Pizza Menu & Ordering**: Browse pizzas and create custom orders
- **Shopping Cart**: Real-time cart management with price calculations
- **Order History**: View past orders with detailed information
- **Pizza of the Day**: Daily featured pizza recommendations
- **Contact Form**: Customer support and inquiries
- **Responsive Design**: Mobile and desktop optimized
- **RESTful API**: Backend server with SQLite database

## 🛠 Tech Stack

### Frontend (Padre-Ginos/)

- **React 18** with modern hooks and function components
- **TanStack Router** for type-safe routing
- **TanStack Query** for data fetching and caching
- **Vite** for fast development and building
- **Vitest** for unit testing

### Backend (api/)

- **Fastify** for high-performance HTTP server
- **SQLite** for lightweight database storage
- **Static file serving** for pizza images and assets

## 🚦 Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm package manager

### Installation & Setup

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   cd PapaGino-s
   ```

2. **Start the API server:**

   ```bash
   cd api
   npm install
   npm run dev
   ```

   API will be available at `http://localhost:3000`

3. **Start the frontend (in a new terminal):**
   ```bash
   cd Padre-Ginos
   npm install
   npm run dev
   ```
   Frontend will be available at `http://localhost:5173`

## 📱 Application Features

- **Home Page**: Featured pizzas and daily specials
- **Order Page**: Browse full menu and add items to cart
- **Cart Management**: Review and modify orders before checkout
- **Order History**: View past orders and reorder favorites
- **Contact**: Customer support and feedback form

## 🙏 Acknowledgments

This project is built following the **Complete Intro to React v9** course on Frontend Masters, demonstrating modern React development practices and full-stack application architecture.

---

_Built with ❤️ using modern web technologies_
