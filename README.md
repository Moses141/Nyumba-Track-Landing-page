# Nyumba Track Landing Page

A professional, modern, mobile-responsive landing page for Nyumba Track - a digital property management system designed for individual landlords and small-scale property owners in Uganda.

## Project Overview

Nyumba Track helps landlords replace manual record-keeping methods (notebooks, spreadsheets) with a centralized digital system for:
- Property and tenant management
- Room-level tracking
- Rent payment monitoring
- Outstanding balance tracking

## Files Structure

```
Group_1_landing_page/
├── index.html      # Main HTML structure
├── styles.css      # Complete styling with responsive design
├── script.js       # Interactive functionality
└── README.md       # Project documentation
```

## Features

### Landing Page Sections
1. **Navigation** - Fixed header with smooth scroll navigation
2. **Hero Section** - Strong value proposition with dashboard mockup
3. **Problem Section** - Addresses landlord pain points
4. **Solution Section** - Shows how Nyumba Track solves problems
5. **Features Section** - 6 key feature cards
6. **Comparison Section** - Why Nyumba Track vs competitors
7. **Testimonials** - 3 realistic testimonials from Ugandan landlords
8. **How It Works** - 3-step process explanation
9. **CTA Section** - Strong call-to-action
10. **Contact Section** - Form with contact details
11. **Footer** - Links, mission statement, copyright

### Technical Features
- Mobile-first responsive design
- Smooth scroll navigation
- Scroll-triggered animations
- Interactive contact form
- Animated statistics counter
- CSS custom properties for easy theming
- Clean, semantic HTML5
- Accessible markup

## Design System

### Colors
- **Primary**: Deep Blue (#1e3a5f)
- **Accent**: Green (#22c55e)
- **Background**: White/Light Gray
- **Text**: Gray scale

### Typography
- Font Family: Inter (Google Fonts)
- Responsive font sizing using clamp()

### Breakpoints
- Desktop: 1024px+
- Tablet: 768px - 1023px
- Mobile: < 768px

## How to Use

1. Open `index.html` in a web browser
2. No build process required - pure HTML/CSS/JS
3. For development, use a local server for best results

### Local Development
```bash
# Using Python
python -m http.server 8000

# Using Node.js (if http-server is installed)
npx http-server

# Using VS Code Live Server extension
# Right-click index.html → Open with Live Server
```

## Customization

### Updating Colors
Edit CSS variables in `styles.css`:
```css
:root {
    --primary: #1e3a5f;
    --accent: #22c55e;
    /* ... other variables */
}
```

### Adding Images
Replace mockup placeholders with actual images:
1. Dashboard screenshots in hero section
2. Feature icons (currently using inline SVGs)
3. Testimonial photos

### Form Integration
The contact form currently shows a success animation. To integrate with a backend:
1. Update the form action in `index.html`
2. Modify the submit handler in `script.js`

## SEO Keywords Included
- Property management system
- Landlord rent tracking
- Rental management software
- Property management for small landlords
- Digital rent record system

## Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome for Android)

## License
© 2026 Nyumba Track. All rights reserved.
