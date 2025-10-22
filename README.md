# 🎨 React Native Color Picker

A beautiful, interactive web application for exploring and copying color values in multiple formats. Perfect for React Native developers and designers who need quick access to color codes.

## ✨ Features

- **147 Named Colors**: Browse through a comprehensive collection of standard web colors
- **Multiple Color Formats**: Get color values in Hex, RGB, HSL, HWB, and integer formats
- **Real-time Search**: Filter colors instantly by name (try "blue", "dark", or "light")
- **One-Click Copy**: Click any color value to copy it to your clipboard
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Visual Color Preview**: See colors at a glance with hover effects and animations
- **Modal Details**: Click any color card to see all available formats in a detailed modal

## 🚀 Quick Start

### Local Development

1. **Clone or download** this repository
2. **Open** `index.html` in your web browser
3. **Start exploring** colors immediately!

No build process or dependencies required - it's a pure HTML/CSS/JavaScript application.

### Vercel Deployment

This app is optimized for deployment on Vercel:

1. **Connect** your GitHub repository to Vercel
2. **Deploy** - Vercel will automatically detect this as a static site
3. **Access** your live color picker at your custom domain

The app works perfectly with Vercel's static site hosting and requires no special configuration.

## 📋 Supported Color Formats

Each color provides values in multiple formats:

### Named Colors
- Standard color names (e.g., "aliceblue", "darkslategray")

### Hexadecimal
- **Hex**: `#f0f8ff` (standard format)
- **Short Hex**: `#f0f` (when possible)
- **Hex with Alpha**: `#f0f8ffff` (includes transparency)

### RGB (Red Green Blue)
- **RGB (comma)**: `rgb(240, 248, 255)`
- **RGB (space)**: `rgb(240 248 255)`
- **RGBA (comma)**: `rgba(240, 248, 255, 1)`
- **RGBA (slash)**: `rgba(240 248 255 / 1)`

### HSL (Hue Saturation Lightness)
- **HSL (comma)**: `hsl(208, 100%, 97%)`
- **HSL (space)**: `hsl(208 100% 97%)`
- **HSLA (comma)**: `hsla(208, 100%, 97%, 1)`
- **HSLA (slash)**: `hsla(208 100% 97% / 1)`

### HWB (Hue Whiteness Blackness)
- **HWB (comma)**: `hwb(208, 94%, 0%)`
- **HWB (space)**: `hwb(208 94% 0%)`

### Integer Format
- **Integer**: `0xff0f8fff` (hex values as integers)

## 🎯 Use Cases

- **React Native Development**: Perfect for finding and copying color values for your React Native apps
- **Web Development**: Great for web designers and developers who need color codes
- **Design Systems**: Useful for maintaining consistent color palettes across projects
- **Learning Colors**: Educational tool for understanding color relationships and formats

## 🔍 Search Tips

The search functionality supports partial matches:
- Search "blue" to find all blue-related colors
- Search "dark" for dark variants
- Search "light" for light variants
- Search "red" for all red shades

## 📱 Mobile Support

The app is fully responsive and works great on mobile devices:
- Touch-friendly interface
- Optimized layout for small screens
- Easy color selection with touch

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript**: No frameworks or build tools required
- **Modern CSS**: Uses CSS Grid, Flexbox, and CSS animations
- **Web APIs**: Utilizes Clipboard API for copying (with fallback support)
- **Keyboard Navigation**: Press Escape to close modals
- **Performance Optimized**: Efficient rendering and search algorithms

## 🌟 Special Features

- **Toast Notifications**: Visual feedback when copying colors
- **Hover Effects**: Interactive animations on color cards
- **Modal Overlays**: Clean, focused view of color details
- **Accessibility**: Keyboard navigation and screen reader friendly
- **Cross-browser Compatible**: Works in all modern browsers

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Made with ❤️ for React Native developers and color enthusiasts!**