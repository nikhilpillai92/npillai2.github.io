# GitHub Pages Portfolio Website

A modern, responsive portfolio showcase website built with HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with smooth animations
- **Mobile Menu**: Hamburger menu for better mobile navigation
- **Project Showcase**: Display your projects with descriptions and links
- **Social Links**: Easy integration with social media profiles
- **Smooth Scrolling**: Enhanced navigation with smooth page scrolling
- **SEO Ready**: Semantic HTML structure
- **Fast Loading**: Lightweight and optimized assets

## Project Structure

```
test.github.io/
├── index.html              # Main HTML file
├── css/
│   └── style.css          # Main stylesheet
├── js/
│   └── script.js          # JavaScript for interactivity
└── README.md              # This file
```

## Getting Started

### 1. Fork & Rename the Repository

1. Create a new GitHub repository named `<username>.github.io`
2. Replace `test` with your actual GitHub username

### 2. Clone the Repository

```bash
git clone https://github.com/<username>/<username>.github.io.git
cd <username>.github.io
```

### 3. Customize Your Website

Edit the following files to personalize your portfolio:

- **index.html**: Update your name, description, projects, and social links
- **css/style.css**: Customize colors, fonts, and layout
- **js/script.js**: Add additional interactivity

### 4. Customize Content

#### Update Navigation Brand
In `index.html`, find the `nav-brand` section and update:
```html
<a href="#home"><span class="brand-icon">👨‍💻</span> Your Name</a>
```

#### Update Project Cards
Modify the project cards in the "Projects Section":
```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-code"></i>
    </div>
    <h3>Your Project Title</h3>
    <p>Your project description</p>
    <div class="project-tags">
        <span class="tag">Technology</span>
    </div>
    <a href="https://github.com/project-link" class="project-link">View Project <i class="fas fa-arrow-right"></i></a>
</div>
```

#### Update Social Links
Modify contact section with your actual social media links:
```html
<a href="https://github.com/yourusername" target="_blank" class="social-link">
    <i class="fab fa-github"></i>
</a>
```

#### Update Colors (Optional)
In `css/style.css`, modify the CSS variables:
```css
:root {
    --primary-color: #2563eb;        /* Main color */
    --secondary-color: #1e40af;      /* Darker shade */
    --accent-color: #0ea5e9;         /* Accent color */
    --text-color: #1f2937;           /* Text color */
    --light-text: #6b7280;           /* Light text */
}
```

### 5. Push to GitHub

```bash
git add .
git commit -m "Initial commit: Portfolio website"
git push origin main
```

### 6. Enable GitHub Pages

1. Go to your repository settings
2. Navigate to **Pages** section
3. Select **Deploy from a branch**
4. Choose the `main` branch
5. Click **Save**

Your website will be live at: `https://<username>.github.io`

## Customization Guide

### Colors
All colors are defined as CSS variables in `css/style.css`. Update them to match your brand.

### Typography
Modify font sizes and font families in the CSS file:
```css
body {
    font-family: 'Your Font', sans-serif;
}
```

### Icons
This website uses Font Awesome icons. Browse available icons at: https://fontawesome.com/icons

Update any icon by changing the class:
```html
<i class="fas fa-your-icon-name"></i>
```

### Add New Sections
Duplicate a section and update the content, then add a link in the navigation menu.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Tips

1. **Optimize Images**: Use compressed images in your project showcase
2. **Minimize CSS/JS**: Use minification tools for production
3. **Lazy Loading**: Consider implementing lazy loading for images
4. **CDN**: Font Awesome is loaded from CDN for faster delivery

## SEO Optimization

Update the meta tags in `index.html` for better SEO:
```html
<meta name="description" content="Your portfolio description">
<meta name="keywords" content="your, keywords, here">
<meta name="author" content="Your Name">
```

## Troubleshooting

### Website not showing up
- Ensure your repository name is exactly `<username>.github.io`
- Check that GitHub Pages is enabled in repository settings
- Wait 5-10 minutes for GitHub to build and deploy your site

### Images not loading
- Ensure image paths are correct relative to the index.html file
- Use absolute URLs for external images

### Styling looks off
- Clear browser cache (Ctrl+Shift+Del or Cmd+Shift+Del)
- Try in an incognito/private window

## License

This project is free to use and modify for personal and commercial purposes.

## Next Steps

1. Customize the content with your information
2. Add more projects to showcase
3. Update social media links
4. Deploy to GitHub Pages
5. Share your portfolio!

## Resources

- [GitHub Pages Documentation](https://pages.github.com/)
- [Font Awesome Icons](https://fontawesome.com/)
- [CSS Variables Guide](https://developer.mozilla.org/en-US/docs/Web/CSS/--*)
- [Markdown Guide](https://www.markdownguide.org/)

---

**Happy coding! 🚀**
