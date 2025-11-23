# Texora International - Premium Scrunchies Manufacturer Website

A modern, responsive B2B website for Texora International, a premium satin scrunchies and hair accessories manufacturer. Built with HTML5, CSS3, Bootstrap 5, and vanilla JavaScript.

## 📋 Project Overview

**Business:** Premium handcrafted satin scrunchies manufacturing and supply
**Target Audience:** Wholesalers, boutiques, fashion brands, and retailers globally
**Purpose:** Showcase products, services, and attract B2B partnerships

## 🏗️ Project Structure

```
texora-website/
├── index.html                 # Main landing page
├── css/
│   ├── bootstrap.min.css      # Bootstrap 5 framework
│   ├── style.css              # Main custom styling with rounded corners theme
│   └── custom.css             # Additional custom styles
├── js/
│   └── main.js                # Main JavaScript functionality
├── img/                       # Image assets
│   ├── banner-background.jpg  # Hero banner background image
│   ├── banner_right.png       # Hero banner right side product image
│   ├── product-1.jpg to product-6.jpg  # Product gallery images
│   ├── service-1.png to service-4.png  # Service icons/images
│   ├── testimonial-1.jpg to testimonial-3.jpg  # Customer testimonials
│   ├── arch-line.svg          # Decorative SVG elements
│   ├── TEXORA FAVICON.png     # Brand logo/favicon
│   └── favicon.ico            # Website favicon
├── video/
│   ├── about-1.mp4            # About section video 1
│   └── about-2.mp4            # About section video 2
├── lib/                       # Third-party libraries
│   ├── animate/               # Animate.css library
│   ├── owlcarousel/           # Owl Carousel slider
│   ├── wow/                   # WOW.js animations
│   ├── easing/                # jQuery easing
│   └── waypoints/             # Waypoints scroll tracking
└── scss/                      # Bootstrap SCSS source files
```

## 🎨 Design Features

- **Responsive Design:** Mobile-first approach with breakpoints at 768px and 991.98px
- **Rounded Corner Theme:** Consistent 6px (small), 10px (medium), and 15px (large) border-radius throughout
- **Color Scheme:** 
  - Primary: Teal (#0D6B68)
  - Secondary: Sandal (#f5f59d)
  - Backgrounds: White/Light Grey
- **Typography:** 
  - Space Grotesk (navbar, headings)
  - Outfit (special sections)
  - Poppins (custom elements)

## 📄 Page Sections

1. **Header/Navigation** - Sticky navbar with logo and menu links
2. **Hero Banner** - Eye-catching banner with CTA buttons and background image
3. **About Section** - Company introduction with embedded videos and expertise icons
4. **Why Choose Us** - 5 key features highlighting competitive advantages
5. **Key Benefits** - Statistics section with customer satisfaction metrics
6. **Product Range** - 6-item product gallery with hover effects
7. **Global Supply Network** - Services and company value proposition
8. **FAQ Section** - Accordion with common questions and answers
9. **Testimonials** - Owl Carousel slider with customer reviews
10. **Newsletter Subscription** - Email capture form
11. **Footer** - Contact information, quick links, and social media

## 🖼️ Image Management

### Image Locations
- **Banner Background:** `img/banner-background.jpg` (referenced in CSS)
- **Product Images:** `img/product-1.jpg` through `img/product-6.jpg`
- **Service Icons:** `img/service-1.png` through `img/service-4.png`
- **Testimonial Photos:** `img/testimonial-1.jpg` through `img/testimonial-3.jpg`

### How to Update Images
1. Replace images in the `img/` folder with same filenames
2. CSS automatically references `banner-background.jpg` for hero banner
3. All other images referenced directly in HTML with consistent naming

### Image Naming Convention
- Use descriptive, lowercase names with hyphens: `banner-background.jpg`, `product-1.jpg`
- Misspelled filenames like `banner_backround.jpg` should be corrected

## 💻 Technologies & Libraries

- **Framework:** Bootstrap 5.0
- **Animation:** WOW.js, Animate.css, jQuery Easing
- **Carousel:** Owl Carousel 2
- **Icons:** Font Awesome 5.10.0, Bootstrap Icons 1.4.1
- **Fonts:** Google Fonts (Space Grotesk, Outfit, Poppins)
- **jQuery:** 3.6.1

## 📧 Contact Information

- **Email:** info@texorainternational.com
- **Phone:** +91 82484 84100
- **WhatsApp:** https://wa.me/918248484100
- **Location:** Tirupur, Tamil Nadu, India
- **Instagram:** https://www.instagram.com/ilex_store

## 🎯 Key Features

✅ Fully Responsive Design
✅ Smooth Scroll Navigation
✅ Animated Elements on Scroll (WOW.js)
✅ Product Gallery with Hover Effects
✅ Customer Testimonials Carousel
✅ FAQ Accordion
✅ Newsletter Subscription
✅ Social Media Integration
✅ WhatsApp Floating Button
✅ Back-to-Top Button
✅ Lazy Loading Images
✅ Modern Rounded Corner Aesthetic

## 🔧 Development Notes

### CSS Custom Variables
```css
--border-radius-sm: 6px    /* Small elements: buttons */
--border-radius-md: 10px   /* Medium elements: forms, cards */
--border-radius-lg: 15px   /* Large elements: images, videos */
```

### Mobile Responsive
- Hero banner hides background image on mobile (< 768px)
- Buttons stack vertically on mobile
- Floating WhatsApp button resized for mobile
- All elements adapt to touch-friendly sizes

### Performance Optimizations
- Minified CSS and JavaScript libraries
- Lazy loading on all images
- CDN links for external resources
- Optimized video elements with playsinline

## 📝 Content Updates

### How to Update Content
1. **Product Information:** Edit product card descriptions in HTML
2. **Service Details:** Modify service section content
3. **FAQ:** Add/edit accordion items in FAQ section
4. **Testimonials:** Update testimonial text and customer names
5. **Contact Info:** Search for phone/email in HTML and update everywhere

### Files with Contact Information
- `index.html` - Multiple instances (footer, hero, WhatsApp link)
- Search for `+91 82484 84100` or `info@texorainternational.com`

## 🎨 Styling Guidelines

- All sharp corners converted to rounded edges for modern aesthetic
- Consistent spacing using Bootstrap grid system
- Color palette follows brand identity (Teal primary, Sandal accent)
- Hover states on all interactive elements
- Smooth transitions (0.3s - 0.5s) on animations

## 🚀 Deployment

1. Ensure all images are in `img/` folder
2. Verify all video files are in `video/` folder
3. Test responsive design on mobile devices
4. Check all external links (social media, email, WhatsApp)
5. Verify banner background image displays correctly
6. Test form submissions and email capture

## 📄 License

© 2024 Texora International. All rights reserved.

---

**Last Updated:** November 23, 2025
**Version:** 1.0 (Production Ready)
