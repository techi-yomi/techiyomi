===============================================
TACHIYOMI WEBSITE - README & SETUP GUIDE
===============================================

Welcome to the Tachiyomi Website project! This is a professional, modern, responsive multi-page website built with HTML, CSS, and JavaScript.

===============================================
FILE STRUCTURE
===============================================

The website consists of the following files:

    index.html      - Home page with hero section and features
    about.html      - About page with mission and vision
    contact.html    - Contact page with Google Form integration
    download.html   - Download page with installation guide
    style.css       - All styling and responsive design
    script.js       - Interactive features and animations
    README.txt      - This file (setup instructions)

===============================================
HOW TO RUN THE WEBSITE LOCALLY
===============================================

1. SIMPLE METHOD (Recommended):
   - Simply double-click on "index.html"
   - The website will open in your default web browser
   - Navigate through pages using the navigation menu

2. LOCAL SERVER METHOD (For testing):
   - If you have Python installed, open terminal/command prompt in the website folder
   - Run: python -m http.server 8000
   - Open browser and go to: http://localhost:8000
   
3. LIVE SERVER (VS Code):
   - If using VS Code, install "Live Server" extension
   - Right-click on index.html and select "Open with Live Server"

===============================================
CUSTOMIZATION GUIDE
===============================================

1. CHANGING COLORS:
   Open "style.css" and find the CSS Variables section at the top:
   
   :root {
       --primary-color: #21AFD5;      (Main brand color - blue)
       --secondary-color: #FFFFFF;     (White)
       --accent-color: #010042;        (Dark blue)
       --text-color: #010042;          (Text color)
   }
   
   Simply replace these color values with your preferred colors.

2. UPDATING GOOGLE FORM LINK:
   Open "contact.html" and find this line (around line 89):
   
   <a href="https://docs.google.com/forms/d/e/YOUR_FORM_ID/viewform?usp=header"
   
   Replace the URL with your own Google Form link.

3. CHANGING GITHUB LINK:
   Search for "https://github.com/techi-yomi" in all HTML files and replace with your GitHub URL.
   This appears in:
   - Navigation menu (all pages)
   - Footer (all pages)
   - Social cards (contact.html)

4. UPDATING DOWNLOAD LINK:
   Open "download.html" and find (around line 63):
   
   <a href="https://tachiyomi.site/download/"
   
   Replace with your actual download link.

5. CHANGING OFFICIAL SITE LINK:
   Search for "https://tachiyomi.site/" in all HTML files and replace with your official website URL.
   This appears in:
   - index.html (hero button and footer)
   - All other pages (footer)

6. MODIFYING KEYWORDS:
   Open "index.html" and find the keyword "Tachiyomi" linked to the official site.
   You can change this text and link as needed for SEO purposes.

7. UPDATING TEXT CONTENT:
   - Open any HTML file in a text editor
   - Find the section you want to change
   - Modify the text between HTML tags
   - Save the file and refresh your browser

8. CHANGING FONTS:
   Open "style.css" and find the @import or <link> for Google Fonts.
   Current font: Poppins
   To change: Replace "Poppins" with your preferred Google Font name in:
   - The <link> tag in HTML files
   - The font-family property in CSS

9. MODIFYING FOOTER:
   Open any HTML file and scroll to the <footer> section.
   Update:
   - Copyright year
   - "Designed & Developed by" text
   - Footer links and descriptions

===============================================
RESPONSIVE DESIGN
===============================================

The website is fully responsive and works on:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (320px - 767px)

Test responsiveness by:
1. Resizing your browser window
2. Using browser DevTools (F12) > Device Toolbar
3. Testing on actual devices

===============================================
FEATURES INCLUDED
===============================================

✓ Responsive navigation with mobile menu
✓ Smooth scroll animations
✓ Hover effects on cards and buttons
✓ Floating card animations on home page
✓ Contact form integration with Google Forms
✓ Download page with installation guide
✓ Back-to-top button
✓ SEO-friendly semantic HTML
✓ Fast loading and optimized performance
✓ Modern gradient effects
✓ Professional typography
✓ Cross-browser compatible

===============================================
SEO OPTIMIZATION TIPS
===============================================

1. Meta Tags: Each page has meta descriptions. Update them with your content.
2. Keywords: Naturally integrate your target keywords in content.
3. Alt Text: Add alt attributes to images when you add them.
4. Internal Links: The site includes natural internal linking.
5. Page Titles: Update the <title> tags in each HTML file's <head> section.

===============================================
ADDING IMAGES
===============================================

To add images to your website:

1. Create an "images" folder in the same directory as your HTML files
2. Add your image files to this folder
3. In your HTML, reference them like this:
   <img src="images/your-image.jpg" alt="Description">

Example locations to add images:
- Hero section (index.html)
- About page (about.html)
- Feature cards (index.html)
- Download page illustrations

===============================================
BROWSER COMPATIBILITY
===============================================

Tested and working on:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

===============================================
TROUBLESHOOTING
===============================================

Issue: Styles not loading
Solution: Ensure style.css is in the same folder as HTML files

Issue: JavaScript not working
Solution: Ensure script.js is in the same folder as HTML files

Issue: Links not working
Solution: Check that all href attributes have correct file names

Issue: Mobile menu not appearing
Solution: Check that script.js is properly linked in HTML

Issue: Fonts not loading
Solution: Ensure you have internet connection for Google Fonts

===============================================
ADVANCED CUSTOMIZATION
===============================================

1. ADDING NEW PAGES:
   - Copy an existing HTML file
   - Rename it
   - Update the content
   - Add a link to it in the navigation menu of all pages

2. ADDING NEW SECTIONS:
   - Copy an existing section's HTML structure
   - Modify the content
   - Style it using existing CSS classes or add new ones

3. CHANGING ANIMATIONS:
   - Open script.js
   - Find the "Intersection Observer" section
   - Modify animation properties (opacity, transform, duration)

4. CUSTOM JAVASCRIPT:
   - Add your custom code at the bottom of script.js
   - Or create a new .js file and link it in HTML

===============================================
DEPLOYMENT OPTIONS
===============================================

1. GITHUB PAGES (Free):
   - Create a GitHub repository
   - Upload all files
   - Enable GitHub Pages in repository settings
   - Your site will be live at: https://username.github.io/repository-name

2. NETLIFY (Free):
   - Sign up at netlify.com
   - Drag and drop your website folder
   - Get a free URL or connect custom domain

3. VERCEL (Free):
   - Sign up at vercel.com
   - Import your project from GitHub
   - Deploy with one click

4. WEB HOSTING:
   - Purchase hosting from any provider
   - Upload files via FTP
   - Configure domain settings

===============================================
MAINTENANCE & UPDATES
===============================================

- Regularly update content to keep it fresh
- Check links periodically to ensure they work
- Update copyright year annually in footer
- Test on new browsers and devices
- Monitor website performance
- Keep backups of all files

===============================================
SUPPORT & RESOURCES
===============================================

HTML Reference: https://developer.mozilla.org/en-US/docs/Web/HTML
CSS Reference: https://developer.mozilla.org/en-US/docs/Web/CSS
JavaScript Reference: https://developer.mozilla.org/en-US/docs/Web/JavaScript
Google Fonts: https://fonts.google.com/
Color Picker: https://www.google.com/search?q=color+picker

===============================================
LICENSE & CREDITS
===============================================

This website template is free to use and modify.

Design inspired by: Tachiyomi official website
Built with: HTML5, CSS3, Vanilla JavaScript
Fonts: Poppins (Google Fonts)
Icons: Inline SVG

Designed & Developed by: Techi Yomi
Version: 1.0
Last Updated: 2024

===============================================
CONTACT
===============================================

For questions or support regarding this website:
- Visit: https://github.com/techi-yomi
- Official Site: https://tachiyomi.site/
- Use the contact form on the website

===============================================

Thank you for using this website template!
We hope it serves your needs perfectly.

Happy customizing! 🚀

===============================================
