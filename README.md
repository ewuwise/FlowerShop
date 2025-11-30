# 🌸 Blooming Flowers - React Native E-Commerce App

A beautiful, fully-featured flower shop mobile application built with React Native and Expo. Features a modern UI, smooth animations, and complete e-commerce functionality.

![React Native](https://img.shields.io/badge/React_Native-0.72.0-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-49.0.0-000020?style=for-the-badge&logo=expo&logoColor=white)
![Platform](https://img.shields.io/badge/Platforms-iOS%20%7C%20Android%20%7C%20Web-4BC51D?style=for-the-badge)

## 📱 App Preview

| Home Screen | Product Details | Shopping Cart |
|-------------|-----------------|---------------|
| <img src="https://images.unsplash.com/photo-1463043254199-7a3efd782ad1?w=300" width="200"> | <img src="https://images.unsplash.com/photo-1579847621515-b40fcc20831e?w=300" width="200"> | <img src="https://images.unsplash.com/photo-1556742049-0cfed4f6a45d?w=300" width="200"> |

## ✨ Features

- 🛍️ **Complete E-Commerce** - Product catalog, shopping cart, and checkout flow
- 🔍 **Smart Search** - Real-time filtering of flower products
- 🎨 **Beautiful UI** - Modern design with smooth animations
- 📱 **Cross-Platform** - Works on iOS, Android, and Web
- 🛒 **Cart Management** - Add, remove, and update quantities
- 🌟 **Categories** - Featured, Mother's Day, Anniversary collections
- ⚡ **Performance** - Optimized with React Navigation and Context API
- 🎭 **Animations** - Smooth fade-in and slide animations

## 🚀 Quick Start

### Prerequisites

- Node.js (v14 or newer)
- npm or yarn
- Expo CLI

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ewuwise/FlowerShop.git
   cd FlowerShop
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npx expo start
   ```

4. **Run on your preferred platform**
   ```bash
   # iOS Simulator (macOS only)
   npx expo start --ios

   # Android Emulator
   npx expo start --android

   # Web Browser
   npx expo start --web
   ```

## 📁 Project Structure

```
FlowerShop/
├── App.js                 # Main application component
├── app.json              # Expo configuration
├── package.json          # Dependencies and scripts
├── babel.config.js       # Babel configuration
├── context/
│   └── CartContext.js    # Global cart state management
└── components/
    ├── FlowerLandingPage.js  # Main landing page
    ├── ProductDetailScreen.js # Product details screen
    ├── CartScreen.js     # Shopping cart screen
    └── styles.js         # Shared styling
```

## 🛠 Technologies Used

- **Frontend Framework**: React Native 0.72.0
- **Development Platform**: Expo SDK 49
- **Navigation**: React Navigation v6
- **State Management**: React Context API
- **Styling**: React Native StyleSheet
- **Animation**: React Native Animated API

## 📦 Dependencies

### Core Dependencies
```json
{
  "expo": "~49.0.0",
  "react": "18.2.0",
  "react-native": "0.72.0",
  "@react-navigation/native": "^6.1.0",
  "@react-navigation/stack": "^6.3.0",
  "react-native-screens": "~3.22.0",
  "react-native-safe-area-context": "4.6.0"
}
```

## 🎯 Usage

### Adding Products
Products are defined in `FlowerLandingPage.js` and include:
- High-quality images from Unsplash
- Descriptive names and pricing
- Detailed product descriptions
- Categorized organization

### Cart Functionality
- Add items to cart from product cards or detail screen
- Adjust quantities in the cart
- Remove items individually
- Real-time total calculation

### Navigation Flow
1. **Home** → Browse flower categories
2. **Product Details** → View full product information
3. **Cart** → Review and manage selections
4. **Checkout** → Complete purchase (UI ready)

## 🔧 Customization

### Adding New Product Categories
Edit the `flowerSections` array in `FlowerLandingPage.js`:

```javascript
const flowerSections = [
  {
    title: "New Category",
    flowers: [
      {
        id: 11,
        name: "New Flower",
        price: 50,
        image: "image-url",
        description: "Product description"
      }
    ]
  }
];
```

### Modifying Styles
Update the `styles.js` file to change colors, spacing, or overall theme:

```javascript
export const styles = StyleSheet.create({
  // Modify primary color
  primary: '#YourColorHere',
  // Adjust card styling
  card: {
    // Your custom styles
  }
});
```

## 🌐 Expo Snack

You can also run this project directly in your browser using Expo Snack:

1. Visit [Expo Snack](https://snack.expo.dev/)
2. Click "Import Git Repository"
3. Paste: `https://github.com/ewuwise/FlowerShop.git`
4. Run on Android, iOS, or Web tabs

## 📸 Screenshots

<div align="center">
  
**Home Screen** | **Product Details** | **Shopping Cart**
:-------------------------:|:-------------------------:|:-------------------------:
![Home](https://images.unsplash.com/photo-1463043254199-7a3efd782ad1?w=250) | ![Details](https://images.unsplash.com/photo-1579847621515-b40fcc20831e?w=250) | ![Cart](https://images.unsplash.com/photo-1556742049-0cfed4f6a45d?w=250)

</div>

## 🤝 Contributing

We welcome contributions! Please feel free to submit issues, feature requests, or pull requests.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Flower images provided by [Unsplash](https://unsplash.com)
- Icons from [Font Awesome](https://fontawesome.com)
- Built with [Expo](https://expo.dev) and [React Native](https://reactnative.dev)

## 📞 Support

If you have any questions or need help with setup, please open an issue or contact the maintainers.

---

<div align="center">

**Made with ❤️ and React Native**

⭐ Star this repo if you found it helpful!

</div>
