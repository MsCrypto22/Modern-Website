# Modern Portfolio Website

A sleek, modern portfolio website built with vanilla HTML, CSS, and JavaScript. Features a dark theme, smooth animations, and interactive elements inspired by contemporary web design.

## ✨ Features

- **Responsive Design** - Works perfectly on all devices
- **Custom Cursor** - Interactive cursor with smooth following animation
- **Smooth Animations** - Fade-in effects and scroll-triggered animations
- **Parallax Effects** - Floating shapes with parallax scrolling
- **Interactive Elements** - Hover effects and smooth transitions
- **Contact Form** - Animated form submission with feedback
- **Modern UI** - Clean, minimalist design with glassmorphism effects
- **Performance Optimized** - Lightweight vanilla JavaScript

## 🚀 Live Demo

[View Live Demo](https://your-portfolio-site.vercel.app)

## 🛠️ Technologies Used

- HTML5
- CSS3 (Grid, Flexbox, Animations)
- Vanilla JavaScript
- No external dependencies

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/modern-portfolio.git
cd modern-portfolio
```

2. Open `index.html` in your browser or serve with a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using VS Code Live Server extension
# Right-click on index.html and select "Open with Live Server"
```

## 🚀 Deployment

### Vercel (Recommended)
1. Push your code to GitHub
2. Connect your repository to [Vercel](https://vercel.com)
3. Deploy automatically

### Netlify
1. Drag and drop your project folder to [Netlify](https://netlify.com)
2. Or connect via GitHub for automatic deployments

### GitHub Pages
1. Go to your repository settings
2. Navigate to Pages section
3. Select source branch (usually `main`)
4. Your site will be available at `https://yourusername.github.io/repository-name`

## 🎨 Customization

### Colors
Update the CSS variables in `styles.css`:
```css
:root {
  --primary-bg: #0a0a0a;
  --primary-text: #ffffff;
  --accent-color: #ffffff;
}
```

### Content
Edit the content in `index.html`:
- Update the hero section with your name and tagline
- Modify the about section with your skills
- Replace gallery items with your projects
- Update contact information

### Animations
Adjust animation timings in `styles.css`:
```css
.hero h1 {
  animation: fadeInUp 1s ease 0.5s forwards;
}
```

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🔧 Performance Tips

- All animations use `transform` and `opacity` for optimal performance
- Images are optimized for web
- CSS is minified for production
- JavaScript uses `requestAnimationFrame` for smooth animations

## 📞 Support

If you have any questions or need help customizing the template, feel free to open an issue or reach out!

---

⭐ Star this repository if you found it helpful!
