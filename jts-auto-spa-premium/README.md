# JTS Auto Spa - Premium Website

A modern, premium website for JTS Auto Spa featuring a sleek dark theme, smooth animations, and professional design elements.

## Features

- **Modern Dark Theme**: Elegant black and gold color scheme that conveys luxury and professionalism
- **Responsive Design**: Fully responsive layout that works perfectly on all devices
- **Smooth Animations**: AOS (Animate On Scroll) effects and custom animations throughout
- **Interactive Elements**: 
  - Mobile-friendly navigation menu
  - Gallery with filter functionality
  - Smooth scrolling between sections
  - Parallax hero section
  - Hover effects on service cards
  - Auto-playing testimonials on mobile
- **Contact Form**: Professional quote request form with validation
- **SEO Optimized**: Meta tags and semantic HTML structure
- **Performance Optimized**: Lazy loading for images and efficient code structure

## Structure

```
jts-auto-spa-premium/
├── index.html          # Main HTML file with all content
├── styles.css          # Premium styling with animations
├── script.js           # Interactive functionality
└── README.md          # Documentation
```

## Sections

1. **Hero Section**: Video background with company introduction
2. **Services**: Four main services with detailed features
3. **Gallery**: Filterable portfolio of work
4. **About**: Company information and statistics
5. **Testimonials**: Client reviews
6. **Quote Form**: Contact form for service inquiries
7. **Contact**: Location map and business hours

## Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #FFD700;      /* Gold */
    --secondary-color: #FFA500;    /* Orange */
    --dark-bg: #0a0a0a;           /* Main background */
    --dark-bg-alt: #1a1a1a;       /* Alternate background */
}
```

### Content
- Replace placeholder images with actual photos
- Update contact information in multiple locations
- Modify service descriptions and pricing
- Add real testimonials
- Update the Google Maps embed with actual location

### Images to Replace
1. Logo images (placeholder URLs in nav and footer)
2. Hero video (currently using a stock video URL)
3. Gallery images (using Unsplash placeholders)
4. About section image
5. Testimonial author photos

## Setup Instructions

1. **Download the files** to your web server
2. **Replace placeholder content**:
   - Logo images
   - Gallery photos
   - Contact information
   - Google Maps API key and location
3. **Test the website** on different devices
4. **Configure the contact form** to send emails to your address

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Dependencies

- Google Fonts (Montserrat, Poppins)
- Font Awesome Icons
- AOS (Animate On Scroll) library

All dependencies are loaded via CDN for easy setup.

## Performance Tips

1. Optimize images before uploading (use WebP format when possible)
2. Enable GZIP compression on your server
3. Use a CDN for static assets
4. Minify CSS and JavaScript files for production

## Contact Form Setup

The contact form currently logs data to the console. To make it functional:

1. Set up a backend service (PHP, Node.js, etc.)
2. Or use a form service like Formspree or EmailJS
3. Update the form action and method accordingly

## License

This website template is created for JTS Auto Spa. All rights reserved.

---

For support or customization requests, contact your web developer.
