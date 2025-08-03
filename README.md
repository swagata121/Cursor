# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. Features a clean design, smooth animations, and mobile-first approach.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic navigation
- **Contact Form**: Functional contact form with validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Smooth Animations**: CSS animations and JavaScript-powered interactions
- **SEO Friendly**: Semantic HTML structure
- **Fast Loading**: Optimized for performance

## Sections

1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About Section**: Personal information and statistics
3. **Skills Section**: Technical skills organized by category
4. **Projects Section**: Showcase of featured projects
5. **Contact Section**: Contact information and contact form

## Customization Guide

### Personal Information

1. **Update your name and title** in `index.html`:
   ```html
   <h1 class="hero-title">
       Hi, I'm <span class="highlight">Your Name</span>
   </h1>
   <h2 class="hero-subtitle">Full Stack Developer</h2>
   ```

2. **Update the about section** with your personal information:
   ```html
   <p>
       I'm a passionate developer with a love for creating innovative solutions 
       that make a difference...
   </p>
   ```

3. **Update statistics** in the about section:
   ```html
   <div class="stat">
       <h3>3+</h3>
       <p>Years Experience</p>
   </div>
   ```

### Skills and Technologies

Update the skills section in `index.html` to reflect your expertise:

```html
<div class="skill-category">
    <h3>Frontend</h3>
    <div class="skill-items">
        <div class="skill-item">
            <i class="fab fa-html5"></i>
            <span>HTML5</span>
        </div>
        <!-- Add more skills -->
    </div>
</div>
```

### Projects

Replace the sample projects with your own:

```html
<div class="project-card">
    <div class="project-image">
        <div class="project-placeholder">
            <i class="fas fa-laptop-code"></i>
        </div>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span>React</span>
            <span>Node.js</span>
        </div>
        <div class="project-links">
            <a href="your-github-link" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
            <a href="your-live-link" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live
            </a>
        </div>
    </div>
</div>
```

### Contact Information

Update your contact details:

```html
<div class="contact-methods">
    <div class="contact-method">
        <i class="fas fa-envelope"></i>
        <span>your.email@example.com</span>
    </div>
    <div class="contact-method">
        <i class="fas fa-phone"></i>
        <span>+1 (555) 123-4567</span>
    </div>
    <div class="contact-method">
        <i class="fas fa-map-marker-alt"></i>
        <span>Your City, Country</span>
    </div>
</div>
```

### Social Media Links

Update the social media links:

```html
<div class="social-links">
    <a href="your-github" class="social-link">
        <i class="fab fa-github"></i>
    </a>
    <a href="your-linkedin" class="social-link">
        <i class="fab fa-linkedin"></i>
    </a>
    <!-- Add more social links -->
</div>
```

## Styling Customization

### Colors

The main color scheme can be customized in `styles.css`:

```css
/* Primary colors */
--primary-color: #2563eb;
--secondary-color: #7c3aed;
--accent-color: #fbbf24;
```

### Fonts

The website uses Inter font from Google Fonts. You can change it by:

1. Update the Google Fonts link in `index.html`
2. Change the font-family in `styles.css`:

```css
body {
    font-family: 'Your Font', sans-serif;
}
```

### Adding Your Photo

Replace the placeholder icons with your actual photos:

1. Add your photo to the project directory
2. Replace the placeholder divs with `<img>` tags:

```html
<!-- In hero section -->
<div class="hero-image">
    <img src="your-photo.jpg" alt="Your Name" class="profile-image">
</div>

<!-- In about section -->
<div class="about-image">
    <img src="your-about-photo.jpg" alt="About You" class="about-image">
</div>
```

Add corresponding CSS for the images:

```css
.profile-image {
    width: 300px;
    height: 300px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid rgba(255, 255, 255, 0.2);
}

.about-image img {
    width: 250px;
    height: 250px;
    border-radius: 20px;
    object-fit: cover;
}
```

## Deployment

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify

1. Drag and drop your project folder to [Netlify](https://netlify.com)
2. Your site will be deployed automatically
3. You can set up a custom domain

### Vercel

1. Connect your GitHub repository to [Vercel](https://vercel.com)
2. Vercel will automatically deploy your site
3. You can set up a custom domain

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance Tips

1. **Optimize images**: Use WebP format and compress images
2. **Minimize CSS/JS**: Use minified versions for production
3. **Enable compression**: Use gzip or brotli compression
4. **Use CDN**: Serve fonts and libraries from CDN

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── README.md           # This file
└── images/             # Your images (optional)
    ├── profile.jpg
    ├── about.jpg
    └── projects/
```

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you have any questions or need help customizing your portfolio, feel free to reach out!

---

**Happy coding! 🚀**
