# IMP Douro - Professional Website

A complete, production-ready website for IMP Douro, Dubai's leading property maintenance and renovation company.

## Files Included

1. **index.html** (1,705 lines)
   - Complete single-page website with all sections
   - Fully responsive design (mobile, tablet, desktop)
   - No external dependencies required (uses CDN links)
   - Inline CSS and JavaScript

2. **firebase.json**
   - Firebase hosting configuration
   - Proper caching headers for optimal performance
   - SPA rewrites for client-side routing

## Features

### Design System
- **Primary Dark**: #1A1A1A
- **Gold Accent**: #C4A860
- **Dark Gold**: #A08040
- **Light Gold**: #E0C060
- **Fonts**: Poppins (headings) + Inter (body)

### Website Sections
1. **Header/Navigation**
   - Sticky navigation with smooth scroll
   - Transparent background → solid on scroll
   - Mobile hamburger menu
   - "Get Free Quote" CTA button

2. **Hero Section**
   - Full height (100vh) with gradient background
   - Headline: "Dubai's Trusted Property Maintenance & Renovation Experts"
   - CTA buttons and quick stat badges
   - Decorative gold line and subtle texture overlay

3. **Services Section**
   - 6 service cards in responsive grid
   - Services: Maintenance, Handyman, Painting, Landscaping, Renovations, Villa Maintenance
   - Hover effects with gold accent

4. **Why Choose Us**
   - Dark background section
   - 4 key statistics
   - 5 feature checkmarks

5. **About Section**
   - Split layout with text and visual element
   - Company mission and values
   - Key highlights with icons

6. **Areas We Serve**
   - 24 Dubai locations listed
   - Pill-shaped badges with gold borders
   - Responsive grid layout

7. **Villa Maintenance Packages**
   - 3 package tiers: Basic, Standard (featured), Premium
   - Detailed service lists
   - CTA buttons

8. **Contact Section**
   - Contact form with validation
   - Contact information (phone, email, WhatsApp, location)
   - Form submission to n8n webhook
   - Success/error message handling

9. **Footer**
   - 3 columns: Company info, Services, Contact
   - "Powered by Mobiweb" link
   - Copyright information

10. **WhatsApp Floating Button**
    - Fixed bottom-right corner
    - Green (#25D366) with hover effects
    - Links to WhatsApp chat

### Technical Features
- Smooth scroll behavior
- AOS (Animate On Scroll) animations
- Mobile-first responsive design
- Form validation and submission
- Hamburger menu for mobile
- Header scroll detection
- Schema.org LocalBusiness JSON-LD
- Complete SEO optimization
- CDN-based external resources

### External Resources (via CDN)
- Google Fonts (Poppins, Inter)
- Font Awesome 6.4.0
- AOS 2.3.1 (Animate On Scroll)
- Tailwind CSS

### Form Submission
- Endpoint: https://n8n.mobiweb.pt/webhook/impdouro-form
- Fields: name, phone, service, property_type, message
- JSON POST with error handling
- Client-side validation

### Mobile Responsive Breakpoints
- Desktop: Full layout
- Tablet (768px): Adjusted grid layouts
- Mobile (480px): Single column layouts

## How to Deploy

### Firebase Hosting
```bash
npm install -g firebase-tools
firebase login
firebase init hosting
firebase deploy
```

### Alternative Hosting
The website is a single HTML file with inline CSS/JS. Can be hosted on:
- Vercel
- Netlify
- GitHub Pages
- Any static hosting service
- Traditional web hosting

## Browser Compatibility
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Contact Information
- Phone: +971564641047
- Email: douroimp@gmail.com
- WhatsApp: https://wa.me/971564641047
- Location: Dubai, UAE

## Company Details
- Company: IMP Douro
- Tagline: Property Maintenance & Renovation in Dubai
- Years in Business: 10+
- Projects Completed: 500+
- Client Rating: 5★

---
Generated: 2025
Version: 1.0
Status: Production Ready
