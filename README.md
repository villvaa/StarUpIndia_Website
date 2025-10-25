# starupindia - Textile Spinning Mill Spare Parts Supplier

A modern, responsive static website for starupindia, a leading supplier of premium spare parts for textile spinning mills.

## Features

- **Homepage**: Hero section with company overview and key features
- **About Page**: Detailed company information, values, expertise, and client testimonials
- **Products Page**: Comprehensive catalog of spare parts categories
- **Contact Page**: Contact form, information, and QR code for quick access
- **Responsive Design**: Fully responsive layout using Tailwind CSS
- **Professional B2B Design**: Clean, industrial-focused aesthetic
- **SEO Optimized**: Meta descriptions, keywords, and sitemap for better search visibility
- **Custom Styling**: Additional CSS for enhanced animations and effects
- **Shared Scripts**: Common JavaScript functionality for better maintainability

## Technology Stack

- HTML5
- Tailwind CSS (via CDN)
- Font Awesome Icons
- QRCode.js for contact QR code generation
- Custom CSS and JavaScript for enhanced functionality
- Vanilla JavaScript for interactivity

## Pages

1. **index.html** - Homepage with hero section, features, and industries served
2. **about.html** - Company information, values, expertise, and testimonials
3. **products.html** - Product categories including spinning components, mechanical parts, and accessories
4. **contact.html** - Contact form, business information, and QR code for vCard

## Files Structure

```
├── index.html          # Homepage
├── about.html          # About page with testimonials
├── products.html       # Products catalog
├── contact.html        # Contact page with form
├── styles.css          # Custom CSS styles
├── scripts.js          # Shared JavaScript functionality
├── favicon.svg         # Website favicon
├── sitemap.xml         # XML sitemap for SEO
├── robots.txt          # Robots file for search engines
└── README.md           # This file
```

## Running Locally

Simply open any HTML file in a web browser, or serve using a local web server:

```bash
# Using Python
python3 -m http.server 8080

# Using Node.js
npx http-server -p 8080
```

Then visit `http://localhost:8080` in your browser.

## Deployment

This static website can be deployed to any web hosting service or GitHub Pages.

### GitHub Pages Deployment

1. Push the repository to GitHub
2. Go to repository Settings > Pages
3. Select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Save and wait for deployment

The site will be available at `https://[username].github.io/[repository-name]/`

## SEO Features

- Optimized meta titles and descriptions for each page
- Relevant keywords for textile industry search terms
- XML sitemap for search engine indexing
- Robots.txt for crawler guidance
- Semantic HTML structure

## Contact Information

The QR code on the contact page contains vCard information for easy contact saving on mobile devices.

## License

© 2024 starupindia. All rights reserved.
