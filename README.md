# Company Template

A simple, fast landing page template for manufacturing and trading companies. Built with HTML/CSS/JS.

## Demo

Live preview: [your-site.github.io](https://your-site.github.io)

## Features

- Single-page design with smooth scroll
- Contact form with Formspree + Google reCAPTCHA v2
- Easy config - edit one object at the top of index.html
- Fully responsive, mobile-first
- No build tools, no npm. Just upload and it works.
- Lightweight: ~15KB total

## Quick Start

1. Download or fork this repo
2. Open index.html and edit the CONFIG section at the top
3. Replace placeholder images in /assets folder
4. Upload all files to GitHub Pages, Netlify, or any static host

## Configuration

All settings are in index.html inside the config object at the top of the file.

### Setup Formspree

1. Go to formspree.io and create a free account
2. Create new form, copy the endpoint URL
3. Paste it into formspreeEndpoint in index.html

### Setup reCAPTCHA

1. Go to google.com/recaptcha/admin
2. Register a new site with reCAPTCHA v2 "I'm not a robot" checkbox
3. Add your domain: yourusername.github.io or your custom domain
4. Copy the Site Key and paste into recaptchaSiteKey in index.html

## File Structure

/ 
├── index.html Main page - edit CONFIG here
├── thanks.html Thank you page that opens after sending a message via embed formspheere.io
├── style.css All styles for both pages
├── README.md This file
└── assets/ Your images
    ├── image.jpg Image
    ├── image.jpg Also image
    └── image.jpg Another image

## Customization 

### Products
Add or remove items in the products array. Each needs name, image, and description.

### Delivery Time Disclaimer
Update the text in advantages array. Always include realistic delivery times for imports.

## Deployment

### GitHub Pages
1. Push files to a repo named yourusername.github.io
2. Go to Settings → Pages → Deploy from branch main
3. Done. Site is live in 2 minutes.

### Netlify
1. Drag and drop the folder to app.netlify.com
2. Done.

## Browser Support

Works in all modern browsers. IE11 not supported.

## License

MIT License - free for personal and commercial use.

## Important Notes

1. Replace all placeholder images before going live
2. Test the contact form after deploying
3. Make sure thanks.html is in the same folder as index.html
4. Add your real reCAPTCHA domain or the form will fail

## Support

This is a static template. No backend or database. For issues with Formspree or reCAPTCHA, check their official docs.
