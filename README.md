# Modern Portfolio Website

A beautiful, responsive portfolio website inspired by modern design trends, similar to Super Declarative. Built with HTML, CSS, and JavaScript.

## Features

- 🎨 **Modern Design**: Clean, professional design with smooth animations
- 📱 **Fully Responsive**: Works perfectly on all devices
- ⚡ **Fast Performance**: Optimized for speed and user experience
- 🎯 **Interactive Elements**: Smooth scrolling, hover effects, and animations
- 📧 **Contact Form**: Functional contact form with validation
- 🌟 **Smooth Animations**: Intersection Observer for scroll-triggered animations
- 📊 **Progress Indicator**: Visual scroll progress bar

## Sections

1. **Hero Section**: Eye-catching introduction with floating cards
2. **Services**: Showcase your skills and services
3. **About**: Personal information and technology stack
4. **Contact**: Contact information and contact form

## Getting Started

### Prerequisites

- A modern web browser
- Basic knowledge of HTML/CSS/JavaScript (for customization)

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser
3. Start customizing the content!

## Customization Guide

### 1. Personal Information

Edit the following in `index.html`:

```html
<!-- Replace "Your Name" with your actual name -->
<title>Your Name - Portfolio</title>

<!-- Update hero section -->
<h1 class="hero-title">
    Hi, I'm <span class="highlight">Your Name</span>
</h1>

<!-- Update navigation logo -->
<div class="nav-logo">
    <a href="#home">YourName</a>
</div>
```

### 2. Contact Information

Update the contact section in `index.html`:

```html
<div class="contact-item">
    <div class="contact-icon">
        <i class="fas fa-envelope"></i>
    </div>
    <div>
        <h3>Email</h3>
        <p>your.email@example.com</p>
    </div>
</div>
```

### 3. Services/Skills

Modify the services section to match your expertise:

```html
<div class="service-card">
    <div class="service-icon">
        <i class="fas fa-code"></i>
    </div>
    <h3>Your Service</h3>
    <p>Description of your service</p>
    <ul class="service-features">
        <li>Skill 1</li>
        <li>Skill 2</li>
        <li>Skill 3</li>
    </ul>
</div>
```

### 4. About Section

Update the about section with your personal information:

```html
<div class="about-text">
    <h2>About Me</h2>
    <p>Your personal story and experience...</p>
    <div class="skills">
        <h3>Technologies I Work With</h3>
        <div class="skills-grid">
            <span class="skill-tag">Your Skill 1</span>
            <span class="skill-tag">Your Skill 2</span>
        </div>
    </div>
</div>
```

### 5. Profile Picture

Replace the placeholder with your actual photo:

```html
<div class="about-image">
    <img src="path/to/your/photo.jpg" alt="Your Name" style="width: 300px; height: 300px; border-radius: 50%; object-fit: cover;">
</div>
```

### 6. Colors and Styling

The website uses a purple gradient theme. To change colors, edit the CSS variables in `styles.css`:

```css
/* Main gradient colors */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* You can replace with your preferred colors */
background: linear-gradient(135deg, #your-color-1 0%, #your-color-2 100%);
```

## File Structure

```
portfolio_web/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## Performance Features

- **Lazy Loading**: Images load only when needed
- **Smooth Animations**: Optimized with CSS transforms
- **Intersection Observer**: Efficient scroll-triggered animations
- **Minimal Dependencies**: Only uses Font Awesome for icons

## Deployment

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select your branch and save
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify

1. Drag and drop your project folder to Netlify
2. Your site will be deployed instantly
3. Get a custom domain or use the provided Netlify URL

### Vercel

1. Connect your GitHub repository to Vercel
2. Deploy automatically on every push
3. Get a custom domain and SSL certificate

## Customization Tips

### Adding New Sections

1. Add the HTML structure in `index.html`
2. Add corresponding styles in `styles.css`
3. Add any JavaScript functionality in `script.js`

### Changing Fonts

Replace the Google Fonts link in `index.html`:

```html
<link href="https://fonts.googleapis.com/css2?family=Your+Font:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

Then update the font-family in `styles.css`:

```css
body {
    font-family: 'Your Font', sans-serif;
}
```

### Adding More Animations

The website uses Intersection Observer for scroll animations. To add more:

```javascript
// Add to script.js
const animatedElements = document.querySelectorAll('.your-new-class');
animatedElements.forEach(el => {
    el.style.opacity = '0';
    el.style.transform = 'translateY(30px)';
    el.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
    observer.observe(el);
});
```

## Troubleshooting

### Form Not Working

The contact form is currently set up for demonstration. To make it functional:

1. Use a form service like Formspree, Netlify Forms, or your own backend
2. Update the form action and method in `index.html`
3. Modify the form handling in `script.js`

### Images Not Loading

- Ensure image paths are correct
- Use relative paths for local images
- Optimize images for web (compress them)

### Mobile Issues

- Test on actual devices, not just browser dev tools
- Check viewport meta tag is present
- Ensure touch targets are large enough (44px minimum)

## Contributing

Feel free to fork this project and customize it for your needs. If you make improvements, consider sharing them!

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing your portfolio, feel free to:

1. Check the code comments for guidance
2. Look at the browser console for any errors
3. Test on different browsers and devices

---

**Happy coding! 🚀** 