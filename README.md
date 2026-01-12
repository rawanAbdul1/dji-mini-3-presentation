# DJI Mini 3 - Scroll-Based Web Presentation

A modern, immersive scroll-based presentation website inspired by premium web experiences like Pixelik Studio, showcasing the DJI Mini 3 drone with focus on aerial photography and timelapse capabilities.

## 🎨 Features

### Scroll-Based Navigation
- **Full-screen sections** with smooth scroll snapping
- **Scroll progress indicator** at the top showing your position
- **Smooth transitions** between sections
- **Keyboard navigation** (Arrow keys, Page Up/Down)

### Sections

1. **Hero Section**
   - Full-screen drone image background
   - Animated title and subtitle
   - Scroll indicator with bounce animation
   - Parallax effect on background

2. **About Section**
   - Split-screen layout with image and content
   - Key statistics (weight, flight time, video quality)
   - Fade-in animations on scroll

3. **Feature Sections**
   - Professional camera system details
   - Intelligent flight modes
   - Alternating left/right layouts
   - High-quality drone images

4. **Gallery Section**
   - 3-image grid layout
   - Hover effects with captions
   - Staggered fade-in animations
   - Showcases different perspectives

5. **Timelapse Section**
   - Dedicated section for hyperlapse features
   - 4 timelapse modes with icons
   - Card-based layout with hover effects
   - Gradient background

6. **Specifications Section**
   - Technical details in organized cards
   - Flight performance, camera, and transmission specs
   - Dark theme for contrast

7. **Call-to-Action Section**
   - Gradient background
   - Large button interaction
   - Encourages user engagement

### Animations & Effects

- ✅ **Fade-in animations** triggered by scroll position
- ✅ **Parallax scrolling** on hero section
- ✅ **Staggered animations** for multiple elements
- ✅ **Hover effects** on images and cards
- ✅ **Smooth transitions** between all states
- ✅ **Auto-hiding navigation** on scroll down

### Interactive Elements

- **Navigation bar** with smooth scroll to sections
- **Scroll progress bar** showing page position
- **Keyboard shortcuts** for navigation
- **Hover interactions** on all clickable elements
- **Responsive design** for all screen sizes

## 🚀 Technologies Used

- **HTML5** - Semantic structure
- **CSS3** - Modern styling with animations
- **Vanilla JavaScript** - Intersection Observer API for scroll animations
- **Responsive Design** - Mobile, tablet, and desktop support

## 📱 Responsive Breakpoints

- **Desktop**: 1024px and above
- **Tablet**: 768px - 1024px
- **Mobile**: Below 768px

## 🎯 Key Highlights

### Timelapse Focus
The presentation includes a dedicated section highlighting the DJI Mini 3's hyperlapse capabilities:
- Free Mode
- Circle Mode
- Waypoint Mode
- Course Lock Mode

### Drone Photography
Multiple sections showcase:
- Aerial perspectives
- Golden hour shots
- Detail photography
- Action shots in flight

## 🎨 Design Philosophy

Inspired by premium web presentations like Pixelik Studio:
- **Minimalist** - Clean, uncluttered design
- **Immersive** - Full-screen sections
- **Smooth** - Fluid animations and transitions
- **Modern** - Contemporary typography and spacing
- **Visual-first** - High-quality imagery

## 🔧 Customization

### Changing Images
Replace image URLs in `index.html`:
```html
<img src="YOUR_IMAGE_URL" alt="Description">
```

### Adjusting Animation Speed
Modify transition durations in `styles.css`:
```css
transition: all 0.8s ease; /* Change 0.8s to your preference */
```

### Scroll Snap Behavior
Adjust in `styles.css`:
```css
html {
    scroll-snap-type: y mandatory; /* or 'y proximity' for looser snapping */
}
```

## 📊 Performance

- Lazy loading for images
- Debounced scroll events
- Intersection Observer for efficient animations
- Optimized CSS transitions
- Minimal JavaScript overhead

## 🌐 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Usage

Simply open `index.html` in a modern web browser. No build process or dependencies required!

## 🎓 Learning Resources

This project demonstrates:
- Intersection Observer API
- CSS Grid and Flexbox
- Scroll-triggered animations
- Responsive design patterns
- Modern JavaScript practices

---

**Note**: All images are sourced from Unsplash for demonstration purposes. Replace with actual DJI Mini 3 product images for production use.
