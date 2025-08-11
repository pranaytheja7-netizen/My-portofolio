# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. This portfolio features a clean design inspired by the Tian Personal Portfolio template with smooth animations and interactive elements.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean and professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic content
- **Contact Form**: Functional contact form with validation
- **Portfolio Gallery**: Showcase your work with hover effects
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Smooth Animations**: CSS animations and JavaScript interactions
- **SEO Friendly**: Proper HTML structure and meta tags

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Customization Guide

### 1. Personal Information

Edit the `index.html` file to update your personal information:

#### Hero Section
```html
<h1 class="hero-title">
    <span class="outline-text">Your</span> Name
</h1>
<p class="hero-description">
    I am a Full Stack Web Developer at heart and produce features that are best suited for the job at hand.
</p>
```

#### About Section
```html
<h2 class="about-title">Creative Designer With Modern Technology</h2>
<p class="about-text">
    Your personal description here...
</p>
```

#### Contact Information
```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <div>
        <h3>Email</h3>
        <p>your.email@example.com</p>
    </div>
</div>
```

### 2. Images

Replace the placeholder images with your own:

#### Hero Image
```html
<img src="path/to/your/hero-image.jpg" alt="Your Name">
```

#### About Image
```html
<img src="path/to/your/about-image.jpg" alt="About Me">
```

#### Portfolio Images
```html
<img src="path/to/your/project-image.jpg" alt="Project Name">
```

### 3. Portfolio Projects

Add your projects to the portfolio section:

```html
<div class="portfolio-item">
    <img src="project-image.jpg" alt="Project Name">
    <div class="portfolio-overlay">
        <h3>Project Title</h3>
        <p>Project Category</p>
    </div>
</div>
```

### 4. Skills

Update the skills radio buttons in the hero section:

```html
<div class="skills-radio">
    <label class="radio-item">
        <input type="radio" name="skills" checked>
        <span class="radio-custom"></span>
        <span class="radio-label">Your Skill 1</span>
    </label>
    <label class="radio-item">
        <input type="radio" name="skills">
        <span class="radio-custom"></span>
        <span class="radio-label">Your Skill 2</span>
    </label>
</div>
```

### 5. Social Media Links

Update the social media icons with your actual profiles:

```html
<div class="social-icons">
    <a href="https://twitter.com/yourusername" class="social-icon">
        <i class="fab fa-twitter"></i>
    </a>
    <a href="https://linkedin.com/in/yourusername" class="social-icon">
        <i class="fab fa-linkedin"></i>
    </a>
    <a href="https://github.com/yourusername" class="social-icon">
        <i class="fab fa-github"></i>
    </a>
</div>
```

### 6. Colors and Styling

Customize the color scheme by editing the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #007bff;
    --secondary-color: #333;
    --background-color: #f8f9fa;
    --text-color: #333;
    --accent-color: #28a745;
}
```

### 7. Experience Badge

Update the experience badge in the hero section:

```html
<div class="floating-element experience-badge">
    <span>5 Years Experience</span>
</div>
```

## How to Use

1. **Download/Clone** the files to your local machine
2. **Customize** the content as described above
3. **Replace** placeholder images with your own
4. **Update** contact information and social media links
5. **Test** the website locally by opening `index.html` in a browser
6. **Deploy** to your preferred hosting service

## Deployment Options

### GitHub Pages
1. Create a new repository on GitHub
2. Upload your portfolio files
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your portfolio will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop your portfolio folder to [Netlify](https://netlify.com)
2. Your site will be deployed instantly
3. You can customize the URL in the site settings

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Navigate to your portfolio folder
3. Run `vercel` and follow the prompts

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Features Included

- ✅ Responsive design
- ✅ Mobile navigation
- ✅ Smooth scrolling
- ✅ Contact form validation
- ✅ Portfolio gallery
- ✅ Social media integration
- ✅ Download CV functionality
- ✅ Animated elements
- ✅ Professional styling
- ✅ SEO optimized

## Customization Tips

1. **Keep it Simple**: Don't overcrowd your portfolio with too much information
2. **High-Quality Images**: Use professional photos and project screenshots
3. **Clear Call-to-Action**: Make it easy for visitors to contact you
4. **Regular Updates**: Keep your portfolio current with new projects
5. **Test on Mobile**: Ensure everything works well on mobile devices

## Support

If you need help customizing your portfolio or have questions, feel free to:

- Check the code comments for guidance
- Review the HTML structure for reference
- Test different browsers for compatibility
- Validate your HTML and CSS

## License

This portfolio template is free to use for personal and commercial projects.

---

**Happy coding! 🚀**
