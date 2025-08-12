# 🍕 Padre Gino's Pizza

A modern React-based pizza ordering application built with cutting-edge web technologies. This project demonstrates best practices in React development, state management, routing, and testing.

## 📚 Course Attribution

This project is inspired by and built following the **Complete Intro to React v9** course on [Frontend Masters](https://frontendmasters.com/). The course provides comprehensive coverage of modern React development practices and patterns.

## 🚀 Features

- **Pizza Menu & Ordering**: Browse available pizzas and create custom orders
- **Shopping Cart**: Add, remove, and manage pizza orders with real-time price calculations
- **Order History**: View past orders with detailed information
- **Pizza of the Day**: Featured daily pizza recommendations
- **Contact Form**: Get in touch with the restaurant
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Modal System**: Clean, accessible modal dialogs using React Portals
- **Error Boundaries**: Graceful error handling throughout the application

## 🛠 Tech Stack

- **React 18** - Modern React with Hooks and function components
- **TanStack Router** - Type-safe routing with lazy loading
- **TanStack Query** - Powerful data fetching and caching
- **Vite** - Fast build tool and development server
- **Vitest** - Fast unit testing framework
- **React Testing Library** - Component testing utilities
- **ESLint** - Code linting and style enforcement

## 🏗 Project Structure

```
src/
├── api/                    # API functions for data fetching
│   ├── getPastOrder.js    # Fetch individual order details
│   ├── getPastOrders.js   # Fetch paginated order history
│   └── postContact.js     # Submit contact form
├── routes/                 # Route components (TanStack Router)
│   ├── __root.jsx         # Root layout component
│   ├── index.lazy.jsx     # Home page
│   ├── order.lazy.jsx     # Pizza ordering page
│   ├── past.lazy.jsx      # Order history page
│   └── contact.lazy.jsx   # Contact form page
├── __tests__/             # Test files
│   └── Pizza.test.jsx     # Pizza component tests
├── App.jsx                # Main application component
├── Cart.jsx               # Shopping cart component
├── contexts.jsx           # React context definitions
├── ErrorBoundary.jsx      # Error boundary component
├── Header.jsx             # Navigation header
├── Modal.jsx              # Reusable modal component
├── Pizza.jsx              # Individual pizza display
├── PizzaOfTheDay.jsx      # Daily featured pizza
├── ShoppingCart.jsx       # Cart management component
└── usePizzaOfTheDay.jsx   # Custom hook for daily pizza
```

## 🚦 Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:

```bash
git clone <repository-url>
cd Padre-Ginos
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

## 🧪 Testing

Run the test suite:

```bash
npm run test
```

Run tests in watch mode during development:

```bash
npm run test:watch
```

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run test` - Run test suite
- `npm run lint` - Run ESLint code analysis

## 🎯 Key Learning Concepts

This project demonstrates several important React and modern web development concepts:

### React Fundamentals

- **Function Components**: Modern React development using function components exclusively
- **Hooks**: useState, useEffect, useContext, useReducer, and custom hooks
- **Props & State**: Proper data flow and state management patterns
- **Event Handling**: User interactions and form submissions

### Advanced React Patterns

- **Context API**: Global state management for shopping cart
- **Error Boundaries**: Graceful error handling and user experience
- **Portals**: Modal rendering outside the component hierarchy
- **Lazy Loading**: Code splitting with route-based lazy loading

### Modern Development Practices

- **TanStack Query**: Server state management and caching strategies
- **TanStack Router**: Type-safe, file-based routing
- **Custom Hooks**: Reusable stateful logic extraction
- **Testing**: Component testing with React Testing Library

### Performance Optimization

- **Code Splitting**: Lazy-loaded routes for better initial load times
- **Caching**: Intelligent data caching with TanStack Query
- **Optimistic Updates**: Smooth user experience during API calls

## 🌍 Internationalization

The application includes Turkish Lira (TRY) currency formatting using the Internationalization API:

```javascript
const intl = new Intl.NumberFormat("tr-TR", {
  style: "currency",
  currency: "TRY",
});
```

## 🤝 Contributing

This is a learning project, but contributions and improvements are welcome! Please feel free to:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Frontend Masters** for the excellent React course content
- **Brian Holt** for creating the comprehensive React curriculum
- **TanStack Team** for amazing React libraries (Router & Query)
- **Vite Team** for the lightning-fast build tool
- The **React Team** for continuing to innovate and improve the developer experience

---

_Built with ❤️ while learning modern React development_
