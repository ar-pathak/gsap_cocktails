# 🍸 Velvet Pour - Premium Cocktail Bar Website

A modern, interactive website for Velvet Pour, an upscale cocktail bar featuring stunning animations, responsive design, and an elegant user experience.

## ✨ Features

- **Interactive Hero Section** - Animated text reveals and parallax video effects
- **Cocktail Showcase** - Dynamic cocktail menu with smooth transitions
- **Responsive Design** - Mobile-first approach with adaptive layouts
- **Smooth Animations** - GSAP-powered scroll-triggered animations
- **Modern UI/UX** - Clean, sophisticated design with premium aesthetics
- **Performance Optimized** - Built with Vite for fast development and builds

## 🚀 Tech Stack

- **Frontend Framework**: React 19.1.1
- **Build Tool**: Vite 7.1.2
- **Styling**: Tailwind CSS 4.1.12
- **Animations**: GSAP 3.13.0 with ScrollTrigger and SplitText
- **Responsive Design**: react-responsive 10.0.1
- **Development**: ESLint with React-specific rules

## 📁 Project Structure

```
velvet-pour/
├── src/
│   ├── components/
│   │   ├── Navbar.jsx          # Navigation with scroll effects
│   │   ├── Hero.jsx            # Main hero section with video
│   │   ├── Cocktails.jsx       # Cocktail showcase
│   │   ├── About.jsx           # About section
│   │   ├── Art.jsx             # Art showcase
│   │   ├── Menu.jsx            # Interactive cocktail menu
│   │   └── Contact.jsx         # Contact information
│   ├── assets/                 # Static assets
│   ├── constants/              # Data constants and mock data
│   ├── App.jsx                 # Main application component
│   ├── main.jsx                # Application entry point
│   └── index.css               # Global styles and Tailwind
├── public/
│   ├── images/                 # Website images and graphics
│   ├── videos/                 # Video assets
│   └── fonts/                  # Custom typography
├── package.json                # Dependencies and scripts
└── vite.config.js             # Vite configuration
```

## 🎯 Key Components

### Navbar
- Transparent to solid background transition on scroll
- Smooth blur effects and navigation links
- Responsive design with mobile considerations

### Hero Section
- Animated text reveals using GSAP SplitText
- Parallax video background with scroll-triggered animations
- Decorative leaf elements with scroll-based movement
- Responsive text sizing and positioning

### Cocktails & Menu
- Interactive cocktail carousel with smooth transitions
- Dynamic content loading and state management
- Responsive image galleries and descriptions
- Smooth navigation between different cocktail categories

### About & Art Sections
- Profile showcases with team information
- Feature highlights and company values
- Artistic elements and visual storytelling

### Contact Section
- Contact information and social media links
- Responsive layout for different screen sizes

## 🛠️ Getting Started

### Prerequisites
- Node.js (version 18 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd velvet-pour
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173`

### Available Scripts

- `npm run dev` - Start development server with hot reload
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint for code quality

## 🎨 Design Features

- **Typography**: Custom font combinations for premium feel
- **Color Scheme**: Sophisticated palette with gradients and transparency
- **Animations**: Smooth scroll-triggered animations throughout
- **Visual Elements**: Decorative leaves, gradients, and modern graphics
- **Responsive**: Mobile-first design with adaptive breakpoints

## 📱 Responsive Design

The website is built with a mobile-first approach and includes:
- Responsive navigation
- Adaptive layouts for different screen sizes
- Touch-friendly interactions
- Optimized images and assets for various devices

## 🚀 Performance Features

- **Vite Build**: Fast development and optimized production builds
- **Image Optimization**: Optimized images and assets
- **Lazy Loading**: Efficient resource loading
- **Smooth Animations**: Hardware-accelerated GSAP animations

## 🔧 Customization

### Adding New Cocktails
Edit `constants/index.js` to add new cocktail entries:
```javascript
const allCocktails = [
  {
    id: "unique-id",
    name: "Cocktail Name",
    country: "Country Code",
    detail: "Description",
    price: "$XX",
    imgPath: "/images/cocktail-image.png"
  }
  // ... more cocktails
];
```

### Modifying Animations
GSAP animations can be customized in individual component files:
- ScrollTrigger configurations
- Timeline animations
- Easing functions and durations

## 🌟 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This project is private and proprietary to Velvet Pour.

## 🤝 Contributing

This is a private project for Velvet Pour. For any issues or questions, please contact the development team.

## 📞 Support

For technical support or questions about the website, please reach out to the development team or contact Velvet Pour directly.

---

**Built with ❤️ for Velvet Pour** 🍸✨
