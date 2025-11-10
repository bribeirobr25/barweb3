# BarWeb3 Website

Professional Local SEO services website for Berlin businesses.

## Features

- ✅ Modern, responsive design
- ✅ Mobile-first approach
- ✅ SEO optimized with meta tags
- ✅ Professional Lucide icons (no emojis)
- ✅ Rounded corners for buttons and images
- ✅ Fast loading times
- ✅ Accessible and user-friendly

## Deployment to GitHub Pages

### Option 1: Manual Upload

1. Create a new repository on GitHub (or use existing one)
2. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

3. Copy the `index.html` file to your repository root

4. Commit and push:
   ```bash
   git add .
   git commit -m "Update website design"
   git push origin main
   ```

5. Enable GitHub Pages:
   - Go to your repository on GitHub
   - Click "Settings" → "Pages"
   - Under "Source", select "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder
   - Click "Save"

6. Your site will be live at: `https://yourusername.github.io/your-repo-name/`

### Option 2: Using GitHub Desktop

1. Open GitHub Desktop
2. Clone your repository
3. Copy `index.html` to the repository folder
4. Commit with message "Update website design"
5. Push to origin
6. Follow step 5-6 from Option 1

## Custom Domain Setup

If you're using a custom domain like `barweb3.xyz`:

1. In your repository root, create a file named `CNAME` with your domain:
   ```
   barweb3.xyz
   ```

2. Configure your DNS settings with your domain provider:
   - Add an A record pointing to GitHub Pages IPs:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
   - Or add a CNAME record pointing to: `yourusername.github.io`

3. In GitHub Settings → Pages, add your custom domain
4. Enable "Enforce HTTPS"

## Making Updates

To update your website:

1. Edit the `index.html` file locally
2. Test your changes by opening the file in a browser
3. Commit and push to GitHub
4. Changes will be live within a few minutes

## File Structure

```
your-repo/
├── index.html          # Main website file
├── CNAME              # Custom domain configuration (optional)
└── README.md          # This file
```

## SEO Features

The website includes:
- Semantic HTML5 structure
- Open Graph meta tags for social sharing
- Descriptive meta descriptions
- Proper heading hierarchy
- Alt text support for images (add when needed)
- Fast loading times
- Mobile-responsive design

## Customization

### Colors
Edit the CSS variables in `index.html` (lines ~36-44):
```css
:root {
    --primary-color: #2563eb;
    --primary-dark: #1e40af;
    --secondary-color: #10b981;
    /* ... */
}
```

### Content
All content is in German. Search for specific sections in `index.html`:
- Hero section: Line ~240
- Services: Line ~280
- Process: Line ~350
- Contact: Line ~390

### Icons
Using Lucide icons. Browse available icons at: https://lucide.dev/icons/

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- No external dependencies except Lucide icons CDN
- Optimized CSS with minimal file size
- Fast First Contentful Paint
- Excellent Lighthouse scores

## License

© 2025 BarWeb3. All rights reserved.
