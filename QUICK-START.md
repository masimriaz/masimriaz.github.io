# Quick Start: Adding Your Professional Photo

## Current Status

✅ Portfolio deployed to: **https://masimriaz.github.io**
⚠️ Using placeholder image - add your photo to personalize

## Add Your Photo (3 Easy Steps)

### Step 1: Prepare Your Image

1. Use a professional headshot photo
2. Crop to square format (1:1 ratio)
3. Recommended size: **400x400px** minimum
4. Keep file size under 500KB for fast loading

**Free tools to prepare your photo:**

- **Remove background:** https://www.remove.bg/
- **Resize & crop:** https://squoosh.app/ or https://www.iloveimg.com/crop-image
- **AI headshot (if needed):** https://www.photopea.com/

### Step 2: Add to Assets Folder

Save your photo as:

```
portfolio-website/assets/profile.jpg
```

or

```
portfolio-website/assets/profile.png
```

### Step 3: Update and Deploy

```bash
cd portfolio-website

# If using .jpg (recommended)
# No changes needed - already configured

# If using .png, update index.html line 50:
# Change: src="assets/profile.svg"
# To: src="assets/profile.png"

# Commit and push
git add .
git commit -m "Add professional profile photo"
git push
```

Wait 1-2 minutes and refresh https://masimriaz.github.io

## What Changed?

### ✨ New Professional Features:

1. **Modern Dark Hero Section**

   - Gradient background (dark blue/navy)
   - White text for high contrast
   - Professional profile image display

2. **Enhanced Color Scheme**

   - Primary: Professional Blue (#0d6efd)
   - Dark backgrounds with gradient overlays
   - Better contrast throughout

3. **Improved Interactions**

   - Service cards with gradient top border on hover
   - Navigation links with animated underline
   - Smooth transitions and shadows

4. **Better Visual Hierarchy**
   - Larger, bolder section titles
   - Enhanced card designs
   - Modern spacing and padding

## Next Customizations (Optional)

### Update Contact Info

Edit `index.html` around line 520-540:

- Replace `asim.riaz@example.com` with your real email
- Update LinkedIn URL
- Update GitHub URL

### Change Colors

Edit `css/styles.css` lines 8-25 to customize:

```css
:root {
  --primary-color: #0d6efd; /* Change this for different brand color */
  --primary-dark: #0a58ca;
  /* ... other colors ... */
}
```

### Add More Images (Future)

The `assets/` folder now has:

- `README.md` - Instructions
- `profile.svg` - Placeholder (replace with your photo)
- Ready for additional images (logos, screenshots, etc.)

## Troubleshooting

**Image not showing?**

- Check file name matches exactly: `profile.jpg` or `profile.png`
- Ensure file is in `assets/` folder
- Clear browser cache
- Check browser console for errors

**Want to go back to light hero?**
Let me know and I can provide the CSS changes.

## Your Live Site

🚀 **https://masimriaz.github.io**

The site is now more professional, modern, and ready for your photo!
