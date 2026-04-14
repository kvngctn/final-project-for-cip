# Central Food Hub Website - README

## Project Description
A professional, responsive website for Central Food Hub - a premier food distribution business. Built with Bootstrap 5 for modern, mobile-first design.

## Website Structure

### Pages Created

1. **Splash Page (index.html)**
   - Welcome/intro landing page with animated logo
   - Navigation to main homepage
   - Brand introduction

2. **Home Page (home.html)**
   - Main entry point with company overview
   - Mission & Vision statements
   - Featured products section
   - Why Choose Us highlights
   - Call-to-action sections

3. **About Page (about.html)**
   - Company history and background
   - Core values (Quality, Integrity, Customer Focus, Sustainability)
   - Mission and Vision details
   - Key achievements and milestones
   - Nature of operations
   - Core competencies

4. **Products & Services (products-services.html)**
   - Comprehensive product catalog
   - Tabbed interface for filtering:
     - All Products
     - Fresh Produce (vegetables, fruits, herbs, seasonal)
     - Seafood (fish, shellfish, specialty)
     - Meat & Poultry
     - Services (Delivery, Bulk Orders, Subscriptions, Support)
   - Detailed descriptions and pricing information

5. **Personnel (personnel.html)**
   - Leadership Team showcase
   - Board of Directors
   - Management Team
   - Company culture and values
   - Join Our Team section

6. **News & Events (news-events.html)**
   - Latest company news and announcements
   - Upcoming events calendar
   - Press releases
   - Event details with dates

7. **Contact Us (contact.html)**
   - Complete contact information
   - Multiple location addresses
   - Phone numbers and email addresses
   - Business hours
   - Contact form with validation
   - Location maps
   - FAQ section

## Features Included

✅ **Responsive Design**
- Mobile-first Bootstrap 5 framework
- Works on all devices (desktop, tablet, mobile)

✅ **Modern UI/UX**
- Smooth animations and transitions
- Interactive cards and hover effects
- Professional color scheme
- Consistent branding throughout

✅ **Interactive Elements**
- Navigation menu with active states
- Tabbed filtering system
- Accordions for FAQs and press releases
- Contact form with validation
- Scroll-to-top button

✅ **Accessibility**
- Semantic HTML structure
- ARIA labels where needed
- FormControl accessibility
- Keyboard navigation support

✅ **Performance**
- Optimized CSS and JavaScript
- CDN-hosted libraries (Bootstrap, FontAwesome)
- Smooth scrolling behavior
- Efficient animations

✅ **SEO Friendly**
- Proper heading hierarchy
- Meta tags and descriptions
- Semantic markup
- Fast load times

## File Structure

```
Central Food Hub/
├── index.html                   # Splash page
├── home.html                    # Homepage
├── about.html                   # About company
├── products-services.html       # Product catalog & services
├── personnel.html               # Team information
├── news-events.html             # News and events
├── contact.html                 # Contact page
├── css/
│   └── style.css               # Custom styles
├── js/
│   └── script.js               # Interactive functionality
├── images/
│   └── logo.png                # Company logo (add here)
└── README.md                    # This file
```

## How to Set Up

1. **Extract/Download Files**
   - Keep all files in the same directory structure

2. **Add Company Logo**
   - Save your logo as `logo.png` in the `images/` folder
   - Logo size: 200x200px recommended (will be resized responsively)
   - Update logo path if filename differs

3. **Open Website**
   - Open `index.html` in your web browser
   - Or index it on your web server

4. **Customize Content**
   - Update phone numbers and email addresses in contact pages
   - Replace placeholder images with actual product images
   - Update company information and personnel details
   - Modify business hours and locations
   - Add real event information

## Customization Guide

### Change Colors
Edit `css/style.css` - modify CSS variables:
```css
:root {
    --primary-color: #007bff;      /* Change button/link colors */
    --secondary-color: #6c757d;    /* Gray backgrounds */
    --success-color: #28a745;      /* Success indicators */
}
```

### Update Company Info
- **Phone**: Search for phone numbers in HTML files and replace
- **Email**: Search for email addresses and update
- **Address**: Update in contact.html
- **Team Members**: Edit personnel.html with actual names and roles

### Add Logo
1. Save your logo image in `images/logo.png`
2. Use any image format (png, jpg, svg)
3. Recommended size: 200x200px or higher

### Add Product Images
- Create subfolders in `images/` for categories
- Update product image references in `products-services.html`

### Customize Theme
- Modify button styles in style.css
- Change fonts in body selector
- Adjust spacing and padding values
- Customize hover effects

## Responsive Design

Your website is fully responsive and automatically adjusts to any screen size:

✅ **Desktop** (1200px+) - Full width layout with optimized spacing
✅ **Laptop** (992px - 1199px) - Adjusted container widths  
✅ **Tablet** (768px - 991px) - Medium layout with optimized text sizes
✅ **Mobile** (576px - 767px) - Stacked layout, mobile-optimized
✅ **Small Mobile** (below 576px) - Ultra-compact layout with minimal spacing

### How It Works

The website automatically:
- Adjusts font sizes for smaller screens
- Stacks columns responsively 
- Hides/shows elements based on screen size
- Optimizes button/touch target sizes for mobile
- Adjusts spacing and padding for readability
- Scales images fluidly
- Reorganizes navigation for mobile

### Mobile Optimizations

- **Touch-friendly buttons** - Minimum 44px height for easy tapping
- **Smart menu** - Hamburger menu collapses on smaller screens
- **Auto-closing menu** - Mobile menu closes when you navigate or click outside
- **Optimized forms** - Easy to fill on mobile with proper input sizing
- **Landscape support** - Looks great in landscape orientation too

### Browser Compatibility for Responsive Design
✅ Firefox (latest versions)
✅ Safari (latest versions)
✅ Edge (latest versions)
✅ Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Metrics

- Lightweight CSS (~15KB)
- Minimal JavaScript (~8KB)
- Bootstrap from CDN (optimized)
- FontAwesome icons from CDN
- Mobile-optimized images

## SEO Optimization

The website includes:
- Proper meta tags
- Semantic HTML5 structure
- Mobile viewport configuration
- Open Graph tags ready (customize in head)
- Sitemap-friendly structure

## Additional Features Available

To add more functionality, consider:
- Integration with Google Maps API for location maps
- Form submission backend
- Product image gallery with lightbox
- Blog/news management system
- E-commerce integration
- Customer testimonials section
- Live chat support widget

## Support

For customization or questions:
- Review Bootstrap documentation: https://getbootstrap.com/
- FontAwesome icons: https://fontawesome.com/
- CSS Grid/Flexbox guides for layout modifications

## License & Usage

This website template is ready for business use. Customize with your company information and branding.

---

**Created:** April 2026
**Version:** 1.0
**Framework:** Bootstrap 5.3
