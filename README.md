
<div align="center">
  
# 🌟 Mustafa Khizar - 3D Portfolio
  
![Portfolio Banner](https://img.shields.io/badge/Portfolio-3D%20Interactive-ff69b4?style=for-the-badge&logo=three.js&logoColor=white)
![Status](https://img.shields.io/badge/Status-Live-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

**A stunning 3D interactive portfolio showcasing modern web development skills**

</div>

---

## ✨ Features

### 🎨 **Interactive 3D Experience**
- **Three.js Integration** - Immersive 3D scenes and animations
- **Smooth Scrolling** - Seamless navigation with asscroll library
- **Dynamic Lighting** - Realistic lighting effects and shadows
- **Responsive 3D Models** - Optimized GLB models with Draco compression

### 🌙 **Theme System**
- **Dark/Light Mode** - Toggle between themes with smooth transitions
- **Persistent Settings** - Theme preference saved locally
- **Smooth Animations** - GSAP-powered transitions

### 📱 **Responsive Design**
- **Mobile-First** - Optimized for all device sizes
- **Touch-Friendly** - Intuitive mobile interactions
- **Performance Optimized** - Fast loading on all devices

### 🎯 **Modern UI/UX**
- **Clean Typography** - Poppins font family
- **Smooth Animations** - Engaging micro-interactions
- **Professional Layout** - Well-structured content sections
- **Accessibility** - WCAG compliant design

---

## 🛠️ Tech Stack

<div align="center">

| Frontend | 3D Graphics | Build Tools | Styling |
|----------|-------------|-------------|---------|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | ![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=three.js&logoColor=white) | ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) | ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | ![WebGL](https://img.shields.io/badge/WebGL-990000?style=flat-square&logo=webgl&logoColor=white) | ![NPM](https://img.shields.io/badge/NPM-CB3837?style=flat-square&logo=npm&logoColor=white) | ![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=white) |

</div>

### 📦 **Key Dependencies**
- **Three.js** `^0.141.0` - 3D graphics library
- **GSAP** `^3.10.4` - Animation library
- **@ashthornton/asscroll** `^2.0.7` - Smooth scrolling
- **lil-gui** `^0.16.1` - Debug GUI
- **Vite** `^7.1.3` - Build tool and dev server

---

## 🚀 Quick Start

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/khizar-portfolio.git

# Navigate to project directory
cd khizar-portfolio

# Install dependencies
npm install

# Start development server
npm run dev
```

### Available Scripts

```bash
# Development server with hot reload
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

---

## 📁 Project Structure

```
📦 Khizar Portfolio
├── 📂 Experience/           # 3D Experience core
│   ├── 📂 Utils/           # Utility classes
│   │   ├── Resources.js    # Asset loader
│   │   ├── Sizes.js        # Viewport management
│   │   └── Time.js         # Animation loop
│   ├── 📂 World/           # 3D World components
│   │   ├── Controls.js     # Camera controls
│   │   ├── Environment.js  # Lighting & environment
│   │   └── Floor.js        # Ground plane
│   ├── Camera.js           # Camera setup
│   ├── Experience.js       # Main experience class
│   └── Renderer.js         # WebGL renderer
├── 📂 public/              # Static assets
│   ├── 📂 models/          # 3D models (.glb)
│   ├── 📂 textures/        # Images & videos
│   └── 📂 draco/           # Draco compression
├── 📄 index.html           # Main HTML file
├── 📄 main.js              # Entry point
├── 📄 style.css            # Styles
└── 📄 package.json         # Dependencies
```

---

## 🎨 Sections Overview

### 🏠 **Hero Section**
- Animated 3D scene introduction
- Dynamic typography with GSAP animations
- Smooth scroll indicator

### 👨‍💻 **About Me**
- Personal introduction and background
- Educational journey with institution logos
- Skills and expertise highlights

### 💼 **Projects**
- Featured C++ and web development projects
- Interactive project cards with GitHub links
- Technology stack indicators

### 🏢 **Work Experience**
- Professional timeline
- Freelance and academic experience
- Achievement highlights

### 📞 **Contact**
- Social media integration
- Professional networking links
- Contact form (optional)

---

## 🎯 Performance Optimizations

### 🚀 **Loading Performance**
- **Draco Compression** - Reduced 3D model file sizes
- **Asset Preloading** - Smooth loading experience
- **Code Splitting** - Optimized bundle sizes

### 📱 **Mobile Optimizations**
- **Responsive 3D** - Adaptive quality based on device
- **Touch Controls** - Mobile-friendly interactions
- **Reduced Animations** - Battery-conscious design

### 🔧 **Technical Optimizations**
- **Frustum Culling** - Only render visible objects
- **LOD System** - Level of detail for 3D models
- **Texture Optimization** - Compressed textures

---

## 🎨 Customization Guide

### 🎨 **Theming**
```css
:root {
  /* Light Theme */
  --color-text-light: #323232;
  --color-background-light: #ffffff;
  --color-pink-light: #eb97c4;
  
  /* Dark Theme */
  --color-text-dark: #faf5e4;
  --color-background-dark: #5b6eb3;
  --color-pink-dark: #ff71bd;
}
```

### 🔧 **3D Scene Configuration**
```javascript
// Experience/Experience.js
this.camera = new Camera();
this.renderer = new Renderer();
this.world = new World();
```

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- **Design Inspiration**: [Bokoko33's Portfolio](https://bokoko33.me/)
- **3D Models**: Custom created GLB models
- **Fonts**: [Google Fonts - Poppins](https://fonts.google.com/specimen/Poppins)
- **Icons**: Custom SVG icons


<div align="center">

**⭐ Star this repository if you found it helpful!**

Made with ❤️ by Saim Shafique


</div>


