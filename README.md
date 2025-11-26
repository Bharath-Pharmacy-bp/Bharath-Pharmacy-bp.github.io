# Bharath Pharmacy Website

A modern, responsive website for Bharath Pharmacy built with HTML, CSS, and JavaScript featuring smooth animations and professional design.

## Features

- **Responsive Design**: Works perfectly on all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, scroll animations, and dynamic content
- **Performance Optimized**: Fast loading with optimized assets
- **SEO Friendly**: Proper meta tags and semantic HTML structure
- **Accessibility**: WCAG compliant with proper contrast and keyboard navigation

## Sections

1. **Hero Section**: Eye-catching landing area with animated pharmacy elements
2. **Products**: Showcase of pharmacy products with category cards
3. **Services**: Key services offered by the pharmacy
4. **About**: Company information and statistics
5. **Contact**: Contact form and business information
6. **Footer**: Additional links and social media

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts (Poppins)

## Setup for GitHub Pages

1. Fork or clone this repository
2. Go to your repository settings
3. Scroll down to "Pages" section
4. Select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click "Save"

Your website will be available at: `https://yourusername.github.io/bharathpharmacy-bp`

## Custom Domain Setup

To connect your custom domain:

1. In your repository, create a file named `CNAME` (no extension)
2. Add your domain name (e.g., `www.bharathpharmacy.com`)
3. In your domain registrar's DNS settings, add:
   - A record pointing to GitHub Pages IPs:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
   - CNAME record: `www` pointing to `yourusername.github.io`

## Local Development

To run locally:

1. Clone the repository
2. Open `index.html` in a web browser
3. Or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

## Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2c5aa0;
    --secondary-color: #1e3c72;
    --accent-color: #00c9ff;
    /* ... other variables */
}
```

### Content
- Update business information in `index.html`
- Modify product/service offerings
- Replace contact details with actual information
- Add real social media links

### Images
- Add your pharmacy images to an `images/` folder
- Update image references in HTML/CSS
- Optimize images for web (WebP format recommended)

## Performance Tips

- Images are optimized and properly sized
- CSS and JavaScript are minified for production
- Lazy loading implemented for images
- Service Worker ready for offline functionality

## Browser Support

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

For support or questions, please contact:
- Email: your-email@domain.com
- Website: https://your-website.com

---

**Note**: Remember to update all placeholder content with your actual business information before deploying!