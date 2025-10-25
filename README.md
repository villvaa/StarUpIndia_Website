# StartupIndia - Textile Spinning Mill Spare Parts

A modern, elegant, mobile-responsive static website for StartupIndia - a leading supplier of spare parts for textile spinning mills across India.

## 🌟 Features

- **Modern Design**: Professional, clean design with gradient backgrounds and card-based layouts
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Comprehensive Product Catalog**: Detailed categories for Ring Frame, Autoconer, Blowroom, Carding, and Speed Frame parts
- **QR Code Integration**: Quick contact information sharing via QR code
- **Contact Form**: Easy-to-use contact form for customer inquiries
- **Semantic HTML**: Accessible and SEO-friendly markup
- **Fast Loading**: Lightweight static site using CDN resources

## 📁 Project Structure

```
starupindia/
├── index.html          # Homepage with hero section and company introduction
├── about.html          # About Us page with company history and mission
├── products.html       # Products page with comprehensive spare parts catalog
├── contact.html        # Contact page with form, QR code, and business hours
├── qr-contact.png      # QR code image for contact information
└── README.md           # Project documentation
```

## 🚀 Getting Started

### View the Website

Simply open any HTML file in a web browser:

1. **Using a local server** (recommended):
   ```bash
   # Python 3
   python -m http.server 8080
   
   # Python 2
   python -m SimpleHTTPServer 8080
   
   # Node.js (with http-server)
   npx http-server -p 8080
   ```
   Then visit: http://localhost:8080

2. **Direct file opening**:
   - Double-click `index.html` to open in your default browser
   - Or right-click and choose "Open with" your preferred browser

### Deployment

The website is a static site and can be deployed to any web hosting service:

- **GitHub Pages**: Push to GitHub and enable Pages in repository settings
- **Netlify**: Drag and drop the files or connect your repository
- **Vercel**: Import the repository or upload files
- **Traditional Hosting**: Upload all files via FTP to your web server

## 🎨 Customization

### Update Contact Information

Edit the contact details in all HTML files:
- Phone: Search for `+91 XXXXX XXXXX` and replace with actual number
- Email: Search for `info@startupindia.com` and replace if needed
- Location: Update the location text as needed

### Modify Colors

The site uses Tailwind CSS with the following primary colors:
- **Blue**: Primary brand color (blue-600, blue-800)
- **Green**: Autoconer category
- **Purple**: Blowroom category
- **Orange**: Carding category
- **Red**: Speed Frame category

To change colors, update the Tailwind class names in the HTML files.

### Add Products

To add more products:
1. Open `products.html`
2. Find the relevant product category section
3. Copy an existing product card
4. Modify the icon, title, and description

### Regenerate QR Code

To create a new QR code with updated contact information:

```python
import qrcode

contact_info = """StartupIndia
Textile Spinning Mill Spare Parts
Phone: YOUR_PHONE_NUMBER
Email: YOUR_EMAIL
Website: YOUR_WEBSITE"""

qr = qrcode.QRCode(
    version=1,
    error_correction=qrcode.constants.ERROR_CORRECT_H,
    box_size=10,
    border=4,
)
qr.add_data(contact_info)
qr.make(fit=True)

img = qr.make_image(fill_color="rgb(37, 99, 235)", back_color="white")
img.save("qr-contact.png")
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **Font Awesome**: Icon library (via CDN)
- **JavaScript**: Vanilla JS for mobile menu functionality
- **Python**: QR code generation (optional, for regeneration)

## 📱 Pages Overview

### Homepage (index.html)
- Hero section with call-to-action buttons
- Company introduction with key features
- Product categories preview
- Quick links to all sections

### About Us (about.html)
- Company history and story
- Mission and vision statements
- Core values
- Why choose StartupIndia
- Key statistics

### Products (products.html)
- **Ring Frame Parts**: Spindles, rings, travellers, rollers, etc.
- **Autoconer Parts**: Scissors, sensors, drums, cleaners, etc.
- **Blowroom Parts**: Beater blades, grid bars, feed rollers, etc.
- **Carding Parts**: Cylinder wire, flat tops, doffer wire, etc.
- **Speed Frame Parts**: Flyer assembly, bobbin holders, rollers, etc.

### Contact (contact.html)
- Contact form with validation
- Phone, email, and location information
- QR code for quick contact sharing
- Business hours
- Service areas across India

## 📄 License

All rights reserved © 2024 StartupIndia

## 🤝 Support

For technical support or inquiries about spare parts:
- **Phone**: +91 XXXXX XXXXX
- **Email**: info@startupindia.com
- **Hours**: Mon-Sat, 9:00 AM - 6:00 PM IST

---

Built with ❤️ for the textile industry
