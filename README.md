# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. Features a clean design, accessibility best practices, and SEO optimization.

## 🚀 Features

### Design & UX
- **Modern Design**: Clean, professional layout with smooth animations
- **Responsive Design**: Fully responsive across all devices (mobile, tablet, desktop)
- **Accessibility**: WCAG compliant with proper ARIA labels, keyboard navigation, and screen reader support
- **Performance**: Optimized for fast loading with efficient CSS and JavaScript

### SEO & Technical
- **SEO Optimized**: Proper meta tags, structured data, and semantic HTML
- **Open Graph**: Social media sharing support
- **Progressive Enhancement**: Works without JavaScript
- **Cross-browser Compatible**: Tested across modern browsers

### Interactive Features
- **Smooth Scrolling**: Navigation links with smooth scroll behavior
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Form Validation**: Real-time form validation with error messages
- **Animations**: Intersection Observer for scroll-triggered animations
- **Active Navigation**: Highlights current section in navigation

## 📁 File Structure

```
personal-portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This documentation
```

## 🛠️ Setup Instructions

1. **Clone or Download**: Get the files to your local machine
2. **Customize Content**: Update the HTML with your personal information
3. **Deploy**: Upload to any web hosting service

### Local Development
```bash
# Open index.html in your browser
# Or use a local server for development
python -m http.server 8000
# Then visit http://localhost:8000
```

## 🎨 Customization Guide

### Personal Information
Update the following sections in `index.html`:

1. **Meta Information** (lines 6-8):
   ```html
   <meta name="description" content="Your description here">
   <meta name="keywords" content="your, keywords, here">
   <meta name="author" content="Your Name">
   ```

2. **Title** (line 15):
   ```html
   <title>Your Name | Professional Portfolio</title>
   ```

3. **Hero Section** (around line 60):
   ```html
   <h1 id="hero-heading">Hi, I'm <span class="highlight">Your Name</span></h1>
   <p class="hero-subtitle">Your Title Here</p>
   ```

4. **About Section**: Update your bio and statistics

5. **Skills**: Modify the skills and technologies you know

6. **Experience**: Update your work history

7. **Projects**: Add your actual projects with links

8. **Contact Information**: Update email, LinkedIn, GitHub links

### Styling Customization

The CSS uses CSS custom properties (variables) for easy customization:

```css
:root {
    --primary-color: #2563eb;      /* Main brand color */
    --primary-dark: #1d4ed8;       /* Darker shade for hover */
    --accent-color: #f59e0b;       /* Accent color */
    --text-primary: #1e293b;       /* Main text color */
    --text-secondary: #64748b;     /* Secondary text color */
    /* ... more variables */
}
```

### Adding Images

1. Create an `images/` folder
2. Add your profile photo and project images
3. Update the HTML to reference your images:
   ```html
   <img src="images/your-photo.jpg" alt="Your Name">
   ```

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## ♿ Accessibility Features

- **Skip Links**: Keyboard users can skip to main content
- **ARIA Labels**: Proper labeling for screen readers
- **Focus Management**: Visible focus indicators
- **Semantic HTML**: Proper heading hierarchy and landmarks
- **Color Contrast**: WCAG AA compliant color ratios
- **Reduced Motion**: Respects user's motion preferences

## 🔧 Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 📈 Performance Features

- **Optimized CSS**: Efficient selectors and minimal repaints
- **Throttled Events**: Scroll events are throttled for performance
- **Lazy Loading**: Images load as needed
- **Minimal JavaScript**: Lightweight and efficient code

## 🚀 Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select your branch and save

### Netlify
1. Drag and drop your folder to Netlify
2. Your site will be live instantly

### Vercel
1. Connect your GitHub repository
2. Vercel will automatically deploy your site

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📞 Support

If you have any questions or need help customizing your portfolio, feel free to reach out!

---

**Built with ❤️ for developers who want to showcase their work professionally.**