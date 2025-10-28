# Headshot Photo Toronto Website

Professional headshot photography website for downtown Toronto studio.

## 🌐 Live Website

Visit: [https://offlinestudios.github.io/Headshot-Photo-Toronto/](https://offlinestudios.github.io/Headshot-Photo-Toronto/)

## 📝 How to Edit the Website

This website is built with plain HTML, CSS, and JavaScript - no build process required! You can edit the content directly.

### Editing Text Content

1. Open `index.html` in any text editor
2. Find the section you want to edit
3. Change the text between the HTML tags
4. Save the file
5. Commit and push to GitHub

**Common sections to edit:**

- **Hero Title**: Search for `<h1 class="hero-title">` around line 48
- **Pricing**: Search for `<!-- Pricing Section -->` around line 204
- **Contact Info**: Search for `<!-- Contact Section -->` around line 398
- **FAQ Questions**: Search for `<!-- FAQ Section -->` around line 339

### Changing Images

1. Add your new image to the `images/` folder
2. Open `index.html`
3. Find the image you want to replace (search for `<img src="images/`)
4. Change the filename to match your new image
5. Save and push to GitHub

**Example:**
```html
<!-- Before -->
<img src="images/old-photo.jpg" alt="Description">

<!-- After -->
<img src="images/new-photo.jpg" alt="Description">
```

### Updating Colors

To change the color scheme:

1. Open `styles.css`
2. Find the `:root` section at the top (around line 10)
3. Modify the color variables:

```css
:root {
    --primary: #1e3a5f;        /* Navy blue - main color */
    --accent: #d4a574;         /* Warm gold - accent color */
    --background: #fafafa;     /* Page background */
}
```

### Changing Fonts

1. Open `index.html`
2. Find the Google Fonts link in the `<head>` section
3. Replace with your preferred font from [Google Fonts](https://fonts.google.com)
4. Update the font family in `styles.css`:

```css
:root {
    --font-family: 'Your Font Name', sans-serif;
}
```

## 🚀 Deploying to GitHub Pages

The website is automatically deployed to GitHub Pages from the `main` branch.

To update the live site:
1. Make your changes to the files
2. Commit your changes: `git add . && git commit -m "Your message"`
3. Push to GitHub: `git push origin main`
4. Wait 1-2 minutes for GitHub Pages to update

## 📁 File Structure

```
headshot-photo-toronto/
├── index.html          # Main website file (edit text here)
├── styles.css          # All styling (edit colors, fonts, spacing)
├── script.js           # Interactive features (menu, FAQ, forms)
├── images/             # All website images
│   ├── professional-1.jpg
│   ├── professional-2.jpg
│   └── ...
└── README.md          # This file
```

## 🎨 Customization Tips

### Adding a New Section

1. Copy an existing section from `index.html`
2. Paste it where you want the new section
3. Change the content
4. Update the navigation menu to link to it

### Changing Button Text

Search for `class="btn"` in `index.html` and edit the text between the tags.

### Updating Contact Information

Search for phone numbers, email addresses, or addresses in `index.html` and replace with your information.

## 📱 Mobile Responsive

The website is fully responsive and works on all devices. No additional configuration needed!

## 🔧 Technical Details

- **No Build Process**: Pure HTML/CSS/JS - edit and deploy instantly
- **No Dependencies**: No Node.js, npm, or package managers required
- **GitHub Pages Ready**: Deploys automatically from the main branch
- **SEO Optimized**: Includes meta tags and semantic HTML
- **Fast Loading**: Optimized images and minimal code

## 📞 Support

For questions about editing the website, refer to this README or search for HTML/CSS tutorials online.

## 📄 License

© 2025 Headshot Photo Toronto. All rights reserved.
