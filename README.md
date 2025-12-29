# Asim Riaz - Professional Portfolio Website

A modern, professional static portfolio website for a Principal Software Architect & Technology Consultant specializing in Cloud-Native Modernization and AI-Enabled Systems.

## 🚀 Live Demo

**GitHub Pages URL:** `https://[your-username].github.io/[repository-name]/`

## 📋 Overview

This is a fully static, single-page portfolio website built with:

- **Bootstrap 5** - Modern, responsive framework
- **HTML5** - Semantic markup
- **CSS3** - Custom styling with CSS variables
- **Vanilla JavaScript** - Minimal, performant interactions

### Design Philosophy

- Executive and business-credible presentation
- Clean, professional aesthetic with plenty of white space
- Optimized for clarity, trust, and conversion
- Mobile-responsive across all devices
- Fast-loading with minimal dependencies

## 📁 Project Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # Custom CSS styles
├── js/
│   └── main.js         # JavaScript interactions
├── assets/             # Images and other assets (add as needed)
└── README.md           # This file
```

## 🌐 Deploying to GitHub Pages

### Option 1: Quick Deploy (Recommended)

1. **Create a new GitHub repository**

   ```bash
   # Initialize git in the portfolio-website folder
   cd portfolio-website
   git init
   git add .
   git commit -m "Initial commit: Professional portfolio website"
   ```

2. **Create repository on GitHub**

   - Go to https://github.com/new
   - Name it: `portfolio` (or any name you prefer)
   - Don't initialize with README (we already have one)
   - Create repository

3. **Push to GitHub**

   ```bash
   git remote add origin https://github.com/[your-username]/portfolio.git
   git branch -M main
   git push -u origin main
   ```

4. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Under "Source", select: `main` branch
   - Click Save
   - Your site will be live at: `https://[your-username].github.io/portfolio/`

### Option 2: User/Organization Site

For a cleaner URL like `https://[your-username].github.io`:

1. Create a repository named exactly: `[your-username].github.io`
2. Push the portfolio files to this repository
3. GitHub Pages will automatically deploy from the `main` branch

## ✏️ Customization Guide

### 1. Update Contact Information

**File:** `index.html`

Find and update these sections:

```html
<!-- Email -->
<a href="mailto:asim.riaz@example.com">asim.riaz@example.com</a>

<!-- LinkedIn -->
<a href="https://linkedin.com/in/asim-riaz">Connect on LinkedIn</a>

<!-- GitHub -->
<a href="https://github.com/asim-riaz">View Portfolio</a>
```

Replace with your actual email, LinkedIn URL, and GitHub profile.

### 2. Modify Colors and Branding

**File:** `css/styles.css`

Update the CSS variables at the top:

```css
:root {
  --primary-color: #2563eb; /* Main brand color */
  --primary-dark: #1e40af; /* Hover states */
  --primary-light: #3b82f6; /* Accents */
  /* ... other variables ... */
}
```

### 3. Edit Content

All content is in `index.html`. Key sections to customize:

- **Hero Section** - Name, title, positioning statement
- **About** - Professional summary
- **Services** - Your core offerings
- **Experience** - Company highlights
- **AI Philosophy** - Your approach (optional to modify)
- **Technology Stack** - Add/remove technologies
- **Case Study** - Replace with your featured project
- **Contact** - Update contact details

### 4. Add Your Photo/Logo

1. Add image to `assets/` folder (e.g., `assets/profile.jpg`)
2. Update hero section in `index.html`:

```html
<div class="col-lg-4 text-center mb-4">
  <img
    src="assets/profile.jpg"
    alt="Asim Riaz"
    class="img-fluid rounded-circle"
    style="max-width: 250px;"
  />
</div>
```

### 5. Change Fonts

**File:** `index.html` (in `<head>`)

Current font: Inter from Google Fonts

To change:

```html
<!-- Replace this line -->
<link
  href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap"
  rel="stylesheet"
/>

<!-- With your preferred font -->
<link
  href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap"
  rel="stylesheet"
/>
```

Then update in `css/styles.css`:

```css
body {
  font-family: "Poppins", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    sans-serif;
}
```

### 6. Add Google Analytics (Optional)

Add before closing `</head>` tag in `index.html`:

```html
<!-- Google Analytics -->
<script
  async
  src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"
></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag() {
    dataLayer.push(arguments);
  }
  gtag("js", new Date());
  gtag("config", "GA_MEASUREMENT_ID");
</script>
```

Replace `GA_MEASUREMENT_ID` with your actual Google Analytics ID.

## 🔧 Local Development

To preview the site locally:

### Option 1: Using Python

```bash
cd portfolio-website
python -m http.server 8000
```

Visit: `http://localhost:8000`

### Option 2: Using Node.js (http-server)

```bash
cd portfolio-website
npx http-server
```

### Option 3: Using VS Code Live Server

1. Install "Live Server" extension
2. Right-click `index.html`
3. Select "Open with Live Server"

## 📱 Browser Compatibility

Tested and works on:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎨 Design Credits

- **Framework:** Bootstrap 5
- **Icons:** Bootstrap Icons
- **Fonts:** Inter (Google Fonts)
- **Color Scheme:** Custom professional palette

## 📄 License

This is a personal portfolio template. Feel free to use and modify for your own portfolio.

## 🤝 Support

For questions or issues:

- Create an issue in the GitHub repository
- Contact via email (update with your email)

## 🔄 Maintenance

### Regular Updates

- Review and update experience highlights quarterly
- Add new projects to case studies
- Update technology stack as you learn new tools
- Refresh testimonials if you add them later

### Performance Optimization

- Compress images before adding to `assets/`
- Keep external dependencies (Bootstrap, fonts) up to date
- Test page speed with Google PageSpeed Insights

---

**Built with precision for technical credibility and business impact.**

Last updated: December 2025
