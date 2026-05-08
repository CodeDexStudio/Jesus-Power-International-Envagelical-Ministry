# Jesus Power International Evangelical Ministry - Website

## Overview
A professional, responsive website for Jesus Power International Evangelical Ministry. This website is built with HTML, CSS, and JavaScript and features a modern, engaging design suitable for a church community.

## Features

### 📱 Responsive Design
- Mobile-friendly layout that works on all devices
- Hamburger menu for mobile navigation
- Optimized for tablets, phones, and desktops

### 🎨 Key Sections
1. **Navigation Bar** - Sticky navigation with smooth scrolling
2. **Hero Section** - Eye-catching welcome banner
3. **About Us** - Mission statement and core values
4. **Services** - Six key ministry services
5. **Events** - Upcoming church events with dates and times
6. **Contact** - Contact form and information
7. **Footer** - Social media links and quick navigation

### ⚡ Interactive Features
- Smooth scrolling navigation
- Mobile menu toggle animation
- Contact form with validation
- Scroll animations for elements
- Active link highlighting based on scroll position
- Hover effects and transitions throughout

### 🎯 Design Elements
- Professional color scheme (Red #c41e3a, Gold #ffc700, Dark #1a1a1a)
- Font Awesome icons for visual appeal
- Clean typography and spacing
- Consistent styling throughout

## File Structure
```
Jesus Power International Envangelical Ministry/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # All styling
├── js/
│   └── script.js       # JavaScript functionality
├── assets/             # For images and media files
└── README.md           # This file
```

## How to Use

### Local Testing
1. Open `index.html` in any web browser
2. The website will load with all styling and functionality

### Deployment
1. Upload all files to your web hosting service
2. Set `index.html` as your home page
3. Ensure all folders (css, js, assets) are maintained

## Customization Guide

### Update Church Information
Edit the following in `index.html`:

**Address and Contact Details:**
```html
<!-- Find and update these sections -->
<p>[Your Church Address]<br>[City, State ZIP]</p>
<p>+1 (XXX) XXX-XXXX</p>
<p>info@jpiem.com</p>
```

**Service Times:**
```html
<p>Sunday: 9:00 AM<br>Wednesday: 7:00 PM</p>
```

**Events:**
Update the event cards with your actual events:
```html
<div class="event-card">
    <div class="event-date">
        <span class="date-day">15</span>
        <span class="date-month">May</span>
    </div>
    <div class="event-details">
        <h3>Event Name</h3>
        <!-- Update details -->
    </div>
</div>
```

### Add Your Logo/Images
1. Place images in the `assets/` folder
2. Update image references in `index.html`:
```html
<img src="assets/your-image.jpg" alt="Description">
```

### Update Colors
Edit the CSS variables in `css/styles.css`:
```css
:root {
    --primary-color: #c41e3a;      /* Main red */
    --secondary-color: #ffc700;    /* Gold accent */
    --dark-bg: #1a1a1a;            /* Dark background */
    --light-bg: #f5f5f5;           /* Light background */
}
```

### Add Social Media Links
Update the footer social links:
```html
<a href="https://facebook.com/yourpage">
    <i class="fab fa-facebook"></i>
</a>
```

### Update Navigation Menu
Add or remove menu items in the navigation:
```html
<li class="nav-item">
    <a href="#section-id" class="nav-links">Menu Item</a>
</li>
```

## Hosting Options

### Free Hosting
- **GitHub Pages** - Perfect for static websites
- **Netlify** - Easy deployment with GitHub integration
- **Vercel** - Fast and reliable hosting
- **Firebase Hosting** - Google's hosting platform

### Paid Hosting
- Traditional web hosting providers
- Domain registration services usually offer hosting

## Browser Compatibility
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Tips
1. Optimize images before uploading (use tools like TinyPNG)
2. Use an image CDN for faster loading
3. Minify CSS and JavaScript for production
4. Enable GZIP compression on your server
5. Use lazy loading for images

## SEO Optimization
- Update the page title and description
- Add meta tags for better search visibility
- Include keywords in content naturally
- Submit sitemap to Google Search Console

## Future Enhancements
Consider adding:
- Blog/Sermon archive
- Online giving/donations
- Member directory
- Prayer request submissions
- Photo gallery
- Video streaming integration
- Multilingual support
- Integration with church management software (ChurchSpace, Planning Center, etc.)

## Support & Maintenance
- Regularly update event information
- Test links and forms periodically
- Monitor contact form submissions
- Keep content fresh and relevant
- Review analytics to understand visitor behavior

## License & Credits
- Font Awesome Icons - Free license
- Google Fonts - Free license
- Custom design created for JPIEM

## Contact for Support
For technical issues or additional customization:
- Review the inline comments in HTML, CSS, and JavaScript files
- Consult web development resources
- Contact a professional web developer if needed

---

**Last Updated:** May 2024
**Version:** 1.0
