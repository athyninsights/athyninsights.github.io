# Athyn Insights Website

A professional, standalone HTML website for Athyn Insights Incorporated, replicating the design and functionality of the original Squarespace site with enhanced content from the company's Capability Brief.

## Project Structure

```
athyn-insights-website/
├── index.html              # Home page
├── about.html              # About Us page
├── services.html           # Services page
├── our-team.html           # Our Team page
├── contact.html            # Contact Us page
├── assets/
│   ├── css/
│   │   └── styles.css      # Shared stylesheet
│   ├── js/
│   │   └── main.js         # Shared JavaScript
│   └── images/
│       └── hero-background.jpg  # Hero section background image
└── README.md               # This file
```

## Features

- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Modern Typography**: Uses Cormorant Garamond (serif) for headings and Inter (sans-serif) for body text
- **Smooth Animations**: Header scroll effect, hover states, and smooth scrolling
- **Professional Content**: Content from the Capability Brief PDF, including:
  - Company introduction and mission
  - Comprehensive service offerings
  - Team member profiles
  - Contact information
- **Accessible**: Semantic HTML structure and proper ARIA labels

## Pages

### Home (`index.html`)
- Hero section with "Data. Delivered." tagline
- Rubio quote about AI leadership
- Company introduction with Funhouse platform metrics

### About (`about.html`)
- Company overview and mission
- "People Matter Most" philosophy
- Proven results and company values
- Rubio quote

### Services (`services.html`)
- Platform Development and Maintenance
- Automation
- Analytics and Data Visualization
- Custom AI/ML Development
- Cost Tracking and Budget Management
- Training and Team Empowerment
- Technologies list
- Security and compliance information

### Our Team (`our-team.html`)
- Lana Tang (Owner & Founder) profile
- Blake Holmes (Data Science Consultant) profile with full bio
- Team member cards with contact information

### Contact (`contact.html`)
- Contact information (address, email, phone, website)
- Contact form for inquiries

## Usage

### Local Development

1. Open any HTML file in a web browser
2. Or use a local web server:
   ```bash
   cd athyn-insights-website
   python3 -m http.server 8000
   ```
   Then navigate to `http://localhost:8000`

### Deployment

The website is a static site and can be deployed to any web hosting service:
- GitHub Pages
- Netlify
- Vercel
- AWS S3
- Any traditional web hosting

Simply upload all files maintaining the folder structure.

## Customization

### Colors
Edit `assets/css/styles.css` to change the color scheme:
- Primary text: `#1a1a1a`
- Secondary text: `#4a4a4a`
- Background: `#f8f8f8`
- Links: `#0066cc`

### Typography
Fonts are loaded from Google Fonts. To change fonts, update the `<link>` tag in each HTML file and the corresponding CSS.

### Content
All content is in the HTML files. Edit the respective HTML files to update:
- Company information
- Service descriptions
- Team member profiles
- Contact information

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Notes

- The contact form currently shows an alert on submission. In production, you would need to connect it to a backend service or form handler (e.g., Formspree, Netlify Forms, etc.)
- Images should be optimized for web use
- Consider adding analytics tracking if needed
- The website uses modern CSS features (CSS Grid, Flexbox, clamp()) which are supported in all modern browsers

## License

© 2024 Athyn Insights Incorporated. All rights reserved.
