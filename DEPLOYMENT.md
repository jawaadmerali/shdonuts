# Quick Deployment Guide for SH Donuts Website

## Fastest Way to Get Your Site Online (Under 5 Minutes!)

### Method 1: GitHub Pages (100% Free Forever)

1. Create a GitHub account at https://github.com if you don't have one

2. Create a new repository:
   - Click the '+' icon in top right → "New repository"
   - Name: `sh-donuts-website` 
   - Make it PUBLIC
   - Click "Create repository"

3. Upload your files:
   - On the repository page, click "uploading an existing file"
   - Drag ALL your website files (index.html, menu.html, contact.html, styles.css, and the images folder)
   - Scroll down and click "Commit changes"

4. Enable GitHub Pages:
   - Click "Settings" tab
   - Scroll down and click "Pages" in the left menu
   - Under "Source", select "main" branch
   - Click "Save"
   - Wait 1-2 minutes

5. Your website is LIVE! 🎉
   - URL will be: `https://YOUR-USERNAME.github.io/sh-donuts-website/`
   - You can share this link immediately!

### Method 2: Netlify (Super Easy, Also Free)

1. Go to https://www.netlify.com
2. Click "Sign up" (you can use GitHub, GitLab, or email)
3. After signing in, go to https://app.netlify.com/drop
4. Drag your entire project folder onto the drop zone
5. DONE! Your site is live with a URL like `https://random-name-12345.netlify.app`
6. To get a better URL:
   - Click "Site settings"
   - Click "Change site name"
   - Enter "sh-donuts" or similar
   - New URL: `https://sh-donuts.netlify.app`

### Method 3: Get a Custom Domain (Optional)

If you want `www.shdonuts.com` instead of a free subdomain:

1. Buy a domain from:
   - Namecheap (usually $8-12/year)
   - GoDaddy
   - Google Domains
   - Cloudflare

2. Connect it to your hosting:
   - **For GitHub Pages**: Follow instructions at https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site
   - **For Netlify**: Go to Site Settings → Domain Management → Add custom domain

## Testing Locally Before Deploying

Want to see the site on your computer first?

### Super Simple Way
Just double-click `index.html` - it will open in your browser!

### Better Way (with a local server)
1. Install Python (it's free, google "install python")
2. Open Terminal (Mac) or Command Prompt (Windows)
3. Navigate to your project folder:
   ```
   cd path/to/your/website
   ```
4. Run:
   ```
   python3 -m http.server 8000
   ```
5. Open browser and go to: `http://localhost:8000`

## Common Issues & Solutions

**Problem**: Links don't work after uploading  
**Solution**: Make sure ALL files are in the same folder structure. Don't put HTML files in subfolders.

**Problem**: Images don't show  
**Solution**: Make sure the `images` folder is uploaded and contains `logo.png`

**Problem**: Styles look wrong  
**Solution**: Make sure `styles.css` is in the same folder as your HTML files

**Problem**: Map doesn't load  
**Solution**: The Google Maps embed should work automatically. If not, get a fresh embed code from Google Maps.

## Updating Your Live Website

### For GitHub Pages:
1. Edit files on your computer
2. Go to your GitHub repository
3. Click "Add file" → "Upload files"
4. Upload the changed files
5. Commit changes
6. Wait 1-2 minutes for changes to appear

### For Netlify:
1. Edit files on your computer
2. Go to https://app.netlify.com
3. Find your site
4. Drag the updated files onto the deploy section
5. Changes appear immediately!

## Need Help?

- GitHub Pages help: https://pages.github.com/
- Netlify help: https://docs.netlify.com/
- HTML/CSS basics: https://www.w3schools.com/

## Checklist Before Going Live

- [ ] Update phone number from (512) 926-6094 to your real number
- [ ] Update address from "5313 Manor Rd" to your real address  
- [ ] Update Google Maps embed with your real location
- [ ] Update hours of operation if different
- [ ] Update menu items and prices
- [ ] Replace logo.png with your actual logo
- [ ] Test all links work
- [ ] Test on mobile phone
- [ ] Test calling the phone number from the site

---

Good luck with your website! 🍩
