# SH Donuts Website

A professional, responsive website for SH Donuts - Austin's favorite neighborhood donut shop located at 5313 Manor Rd, Austin, TX.

## Features

- **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- **Clean Modern UI** - Professional design with custom orange (#FF8B3D) brand colors
- **Three Main Pages**:
  - Home page with hero section, featured items, hours, and location
  - Full menu with pricing for donuts, kolaches, tacos, sandwiches, and drinks
  - Contact page with hours, address, phone, and embedded Google Map
- **SEO Optimized** - Proper meta tags and semantic HTML
- **Fast Loading** - Minimal dependencies, optimized assets
- **Accessible** - Follows web accessibility best practices

## File Structure

```
sh-donuts/
├── index.html          # Home page
├── menu.html           # Menu page
├── contact.html        # Contact page
├── styles.css          # Main stylesheet
├── images/             # Images folder
│   └── logo.png        # Logo file
└── README.md           # This file
```

## Quick Start

### Option 1: GitHub Pages (Recommended for Free Hosting)

1. **Create a new GitHub repository**:
   - Go to https://github.com/new
   - Name it `sh-donuts` (or any name you prefer)
   - Keep it public
   - Don't initialize with README

2. **Upload files**:
   ```bash
   # In your project folder
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/sh-donuts.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository Settings
   - Click "Pages" in the left sidebar
   - Under "Source", select "main" branch
   - Click Save
   - Your site will be live at: `https://YOUR-USERNAME.github.io/sh-donuts/`

### Option 2: Netlify (Also Free, Easier Deployment)

1. Go to https://netlify.com and sign up
2. Drag and drop your project folder onto Netlify
3. Your site will be live instantly with a custom URL
4. Optional: Add a custom domain in Site Settings

### Option 3: Vercel (Free, Fast, Easy)

1. Go to https://vercel.com and sign up with GitHub
2. Click "New Project"
3. Import your GitHub repository
4. Click Deploy
5. Your site will be live at: `https://sh-donuts.vercel.app/`

### Option 4: Traditional Web Hosting

1. Get hosting from providers like:
   - Bluehost
   - HostGator
   - SiteGround
   - GoDaddy
   
2. Upload all files via FTP to your `public_html` folder

3. Your site will be live at your domain

## Local Development

To test the website locally before deploying:

1. **Simple method** - Just open `index.html` in your web browser

2. **With a local server** (recommended for testing):
   ```bash
   # Using Python 3
   python3 -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js (install http-server first: npm install -g http-server)
   http-server
   ```
   Then open http://localhost:8000 in your browser

## Customization Guide

### Colors
Edit the CSS variables in `styles.css` (lines 13-21):
```css
:root {
    --primary-orange: #FF8B3D;  /* Main brand color */
    --dark-navy: #1A2332;       /* Footer background */
    --cream: #FFF5E8;           /* Light background */
    /* ... etc */
}
```

### Logo
Replace `images/logo.png` with your actual logo file. Recommended size: 80x80px or larger.

### Phone Number
Search for `5129266094` and `(512) 926-6094` in all HTML files and replace with your number.

### Address
Search for `5313 Manor Rd` and `Austin, TX 78723` and update with your address.

### Hours
Edit the hours in:
- `index.html` (lines in the hours section)
- `contact.html` (hours section)

### Menu Items & Prices
Edit the menu tables in `menu.html` to update items and pricing.

### Google Maps
In `index.html` and `contact.html`, find the `<iframe>` tag and replace the `src` URL with your location's embed URL from Google Maps:
1. Go to Google Maps
2. Search for your address
3. Click "Share" → "Embed a map"
4. Copy the iframe code
5. Replace the existing iframe src URL

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- No external JavaScript libraries
- Minimal CSS (single file)
- Optimized images
- Fast load times (<1 second)

## SEO Checklist

✅ Semantic HTML5  
✅ Meta descriptions  
✅ Proper heading hierarchy  
✅ Alt text for images  
✅ Mobile responsive  
✅ Fast loading  
✅ Valid HTML/CSS  

## Additional Improvements (Optional)

Consider adding:
- Favicon (website icon)
- Online ordering integration
- Photo gallery
- Customer reviews
- Social media links
- Email newsletter signup
- Analytics (Google Analytics)

## Support

For issues or questions about the website code, please create an issue in your GitHub repository.

## License

This website template is provided as-is for SH Donuts. Modify as needed.

---

**Built with ❤️ for SH Donuts**  
Fresh donuts, kolaches, and breakfast favorites in East Austin!
