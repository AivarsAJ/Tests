# Website Template - Inspired by SPINX Digital

A modern, responsive website template with similar design elements and flow to SPINX Digital's website.

## Features

- **Modern Design**: Clean, professional layout with smooth animations
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Elements**: 
  - Smooth scrolling navigation
  - Mobile hamburger menu
  - Testimonial slider
  - Dropdown menus
  - Fade-in animations on scroll
- **SEO Friendly**: Semantic HTML structure
- **Performance Optimized**: Efficient CSS and JavaScript

## File Structure

```
.
├── index.html      # Main HTML structure
├── styles.css      # All styling and responsive design
├── script.js       # Interactive functionality
└── README.md       # This file
```

## Customization Guide

### 1. Company Information

**Update Company Name:**
- Search and replace `YourCompany` throughout `index.html`
- Update the logo text in the navigation: `<a href="#home">YourCompany</a>`

**Update Contact Information:**
- In the footer section, update:
  - Phone: `+1 (555) 123-4567`
  - Email: `hello@yourcompany.com`
  - Address: `123 Business Street, Your City, State 12345`

### 2. Colors

Edit the CSS variables in `styles.css` at the top:

```css
:root {
    --primary-color: #1a1a1a;      /* Main text color */
    --secondary-color: #333;        /* Secondary text */
    --accent-color: #0066cc;       /* Primary brand color (buttons, links) */
    --text-color: #333;             /* Body text */
    --text-light: #666;             /* Light text */
    --bg-light: #f8f9fa;           /* Light backgrounds */
    --white: #ffffff;               /* White */
    --border-color: #e0e0e0;        /* Borders */
}
```

### 3. Content Sections

**Hero Section:**
- Update the main headline in the hero section
- Modify the subtitle text
- Change the CTA button text

**Featured Projects:**
- Replace project cards with your actual projects
- Add project images (replace the placeholder divs)
- Update project titles and descriptions

**Testimonials:**
- Replace with your actual client testimonials
- Update names and titles

**Statistics:**
- Update the numbers in the stats section (20+, 500+, 35+)
- Modify the labels

### 4. Adding Images

To add project images:

1. Create an `images` folder in your project
2. Add your image files
3. Replace the placeholder divs:

```html
<div class="project-image">
    <img src="images/your-project.jpg" alt="Project Name">
</div>
```

### 5. Technologies/Services

Update the technology grid with your actual services/technologies. Modify the tech items in the technologies section.

### 6. Navigation Menu

Customize the navigation items in the `<nav>` section:
- Update menu item names
- Modify dropdown menu items
- Add or remove sections as needed

### 7. Footer

Update footer links and sections:
- Services list
- Industries list
- Social media links (update hrefs)
- Contact information

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Tips

1. **Optimize Images**: Compress images before adding them
2. **Minify CSS/JS**: Use minified versions for production
3. **CDN**: Consider using a CDN for fonts and assets
4. **Lazy Loading**: Images already have lazy loading support built-in

## Next Steps

1. Replace placeholder content with your actual content
2. Add your company logo (replace text logo with image)
3. Update all contact information
4. Add real project images and case studies
5. Customize colors to match your brand
6. Test on multiple devices and browsers
7. Add Google Analytics or other tracking (if needed)
8. Set up hosting and domain

## License

This template is free to use and modify for your projects.

## Support

For customization help, refer to the comments in the code files or modify the sections as needed for your specific requirements.

