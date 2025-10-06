# IELTS Preparation Landing Page

A modern, animated landing page for IELTS preparation services built with React, GSAP, and Tailwind CSS.

## 🚀 Quick Start

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd animated_assignment
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173`

## 🛠️ Build for Production

```bash
npm run build
```

## 📁 Project Structure

```
src/
├── components/
│   ├── AnimatedBox.jsx          # Countdown animation component
│   ├── FloatingPanel.jsx        # Floating panel with content
│   ├── Footer.jsx               # Site footer
│   ├── GridStage.jsx            # Main grid layout with panels
│   ├── HorizontalPanels.jsx     # Horizontal scrolling panels
│   ├── Icon.jsx                 # SVG icon components
│   ├── Navbar.jsx               # Navigation bar
│   └── ShowcaseSections.jsx     # Features & testimonials carousel
├── App.jsx                      # Main application component
├── index.css                    # Global styles & animations
└── main.jsx                     # Application entry point
```

## 🎨 Design Choices

### **Typography**
- **Mollen Font Family**: Custom font with multiple weights and styles for a premium, professional look
- **Hierarchy**: Clear typography scale with `text-5xl` for headings, `text-xl` for subheadings, and `text-sm` for body text

### **Color Scheme**
- **Dark Theme**: `bg-zinc-950` base with `bg-zinc-900` cards for modern appeal
- **Accent Colors**: Red (`red-500`) for highlights and call-to-action elements
- **Glassmorphism**: Semi-transparent cards with `backdrop-blur-md` for depth

### **Layout & Animations**
- **GSAP Timeline**: Scroll-triggered animations for smooth, professional transitions
- **Grid System**: 2x2 responsive grid for main content panels
- **Infinite Carousels**: Smooth horizontal scrolling for features and testimonials
- **Z-Index Layering**: Strategic layering for complex animations (images, backgrounds, text)

### **User Experience**
- **Smooth Scrolling**: ReactLenis integration for buttery-smooth scroll experience
- **Responsive Design**: Mobile-first approach with Tailwind's responsive utilities
- **Interactive Elements**: Hover effects and clickable testimonial cards
- **Performance**: Optimized animations with proper cleanup and context management

### **Technical Architecture**
- **Component-Based**: Modular React components for maintainability
- **Ref Management**: Strategic use of refs for GSAP animations
- **State Management**: Minimal state usage, focusing on animation-driven interactions
- **CSS-in-JS**: Tailwind CSS for consistent styling and rapid development

## 🎯 Key Features

- **Animated Landing**: Scroll-triggered timeline with multiple animation sequences
- **Interactive Panels**: Horizontal scrolling with mask animations
- **Feature Showcase**: Infinite carousel displaying IELTS preparation features
- **Testimonial Section**: Clickable testimonial cards with external links
- **Responsive Design**: Optimized for all device sizes
- **Modern UI**: Glassmorphism effects and smooth transitions

## 🛠️ Technologies Used

- **React 18** - UI framework
- **Vite** - Build tool and dev server
- **GSAP** - Animation library
- **Tailwind CSS** - Utility-first CSS framework
- **ReactLenis** - Smooth scrolling
- **Custom Fonts** - Mollen font family

## 📝 Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🎨 Customization

### Adding New Panels
1. Add new refs in `App.jsx`
2. Update the GSAP timeline with new animations
3. Add corresponding JSX in `GridStage.jsx`

### Modifying Animations
- Edit the GSAP timeline in `App.jsx`
- Adjust timing, easing, and properties as needed
- Use GSAP's documentation for advanced techniques

### Styling Changes
- Modify `src/index.css` for global styles
- Update component classes for specific styling
- Add new Tailwind utilities as needed

## 📄 License

This project is for educational/demonstration purposes.

---

**Built with ❤️ using React, GSAP, and Tailwind CSS**