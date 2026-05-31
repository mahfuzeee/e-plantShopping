# Paradise Nursery Shopping Application

A modern, interactive React-based e-commerce platform for browsing and purchasing a wide variety of plants. Built with React, Redux Toolkit, and Vite for optimal performance.

**Repository:** [e-plantShopping](https://github.com/mahfuzeee/e-plantShopping)

---

## 🎯 Overview

Paradise Nursery is your one-stop destination for all your plant needs. Browse through carefully curated collections of air-purifying plants, aromatic fragrant plants, insect repellent plants, medicinal herbs, and low-maintenance greenery. Manage your shopping cart seamlessly with our Redux-powered state management system.

---

## ✨ Features

- 🛍️ **Browse Plant Categories** - Air Purifying, Aromatic Fragrant, Insect Repellent, Medicinal, and Low Maintenance plants
- 🛒 **Shopping Cart Management** - Add, remove, and update plant quantities with Redux state management
- 🎨 **Responsive Design** - Beautiful UI optimized for desktop and mobile devices
- ⚡ **Fast Performance** - Built with Vite for lightning-fast development and production builds
- 📱 **User-Friendly Interface** - Smooth transitions and intuitive navigation
- ℹ️ **About Us Section** - Learn about Paradise Nursery and our mission

---

## 🛠️ Tech Stack

- **Frontend Framework:** React 18.2.0
- **State Management:** Redux Toolkit 2.2.3
- **Build Tool:** Vite 5.2.0
- **CSS Styling:** CSS3 with custom components
- **Package Manager:** npm

---

## 📁 Project Structure

```
e-plantShopping/
├── public/                 # Static assets
├── src/
│   ├── App.jsx            # Main application component
│   ├── App.css            # App styling
│   ├── ProductList.jsx    # Product listing component
│   ├── ProductList.css    # Product list styling
│   ├── CartItem.jsx       # Shopping cart item component
│   ├── CartItem.css       # Cart item styling
│   ├── CartSlice.jsx      # Redux cart state management
│   ├── AboutUs.jsx        # About Us page component
│   ├── AboutUs.css        # About Us styling
│   ├── store.js           # Redux store configuration
│   ├── main.jsx           # React entry point
│   └── index.css          # Global styles
├── index.html             # HTML template
├── vite.config.js         # Vite configuration
├── package.json           # Project dependencies
└── README.md             # This file
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/e-plantShopping.git
   cd e-plantShopping
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Start the development server:**

   ```bash
   npm run dev
   ```

4. **Open your browser:**
   Navigate to `http://localhost:5173` (or the URL shown in your terminal)

---

## 📦 Available Scripts

| Command           | Description                                            |
| ----------------- | ------------------------------------------------------ |
| `npm run dev`     | Start the development server with hot module reloading |
| `npm run build`   | Build the project for production                       |
| `npm run preview` | Build and preview the production build locally         |
| `npm run lint`    | Run ESLint to check code quality                       |

---

## 🌱 Plant Categories

### Air Purifying Plants

- Snake Plant
- Spider Plant
- Peace Lily
- Boston Fern
- Rubber Plant
- Aloe Vera

### Aromatic Fragrant Plants

- Lavender
- Jasmine
- Rosemary
- Mint
- Lemon Balm
- And more...

### Additional Categories

- Insect Repellent Plants
- Medicinal Plants
- Low Maintenance Plants

---

## 🎨 Component Overview

### App.jsx

Main component handling the landing page and navigation between home and product listing views.

### ProductList.jsx

Displays categorized plants with detailed information including images, descriptions, and pricing. Contains cart visibility toggle.

### CartItem.jsx

Represents individual items in the shopping cart with quantity management controls.

### CartSlice.jsx

Redux slice managing cart state with actions for:

- Adding items to cart
- Removing items from cart
- Updating item quantities

### store.js

Redux store configuration using Redux Toolkit's `configureStore`.

---

## 🔧 Redux State Management

The application uses Redux Toolkit for predictable state management:

```javascript
// Store structure
{
  cart: {
    items: []; // Array of cart items
  }
}
```

---

## 📝 Usage

1. **Browse Plants:** Click "Get Started" on the landing page
2. **View Details:** Scroll through different plant categories
3. **Add to Cart:** Select plants and add them to your shopping cart
4. **Manage Cart:** Update quantities or remove items from your cart
5. **Return Home:** Click the home button to go back to the landing page

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👥 About Paradise Nursery

We believe in bringing the beauty of nature into every home. Our carefully selected collection of plants helps you create a healthier, more vibrant living space. Whether you're looking to purify the air, add fragrance, or simply enjoy the therapeutic benefits of plants, Paradise Nursery has something for everyone.

---

## 📞 Support

For questions, issues, or suggestions, please open an issue on the [GitHub repository](https://github.com/yourusername/e-plantShopping/issues).

---

## 🌍 Connect With Us

- Website: [Paradise Nursery](#)
- Email: contact@paradisernsery.com
- Social Media: [@ParadiseNursery](#)

---

**Happy Planting! 🌿💚**
