# GitHub Pages Deployment Checklist

## Pre-Deployment Steps

### 1. Content Review

- [ ] Update email address in Contact section
- [ ] Update LinkedIn URL
- [ ] Update GitHub profile URL
- [ ] Review all company names and dates
- [ ] Verify technology stack is current
- [ ] Check all links work correctly

### 2. Optional Enhancements

- [ ] Add profile photo to `assets/` folder
- [ ] Add company logos if available
- [ ] Add favicon (16x16, 32x32, 180x180 PNG files)
- [ ] Set up Google Analytics (if desired)

### 3. Testing

- [ ] Open `index.html` in browser locally
- [ ] Test all navigation links
- [ ] Test mobile responsiveness (use browser dev tools)
- [ ] Check all sections load correctly
- [ ] Verify smooth scrolling works

## GitHub Deployment

### Step 1: Create Repository

```bash
cd portfolio-website
git init
git add .
git commit -m "Initial commit: Professional portfolio"
```

### Step 2: Create GitHub Repo

1. Go to: https://github.com/new
2. Repository name: `portfolio` (or `[username].github.io` for custom domain)
3. Public repository
4. Don't initialize with README
5. Click "Create repository"

### Step 3: Push Code

```bash
# Replace [username] with your GitHub username
git remote add origin https://github.com/[username]/portfolio.git
git branch -M main
git push -u origin main
```

### Step 4: Enable GitHub Pages

1. Go to repository → Settings
2. Click "Pages" in left sidebar
3. Under "Source":
   - Branch: `main`
   - Folder: `/ (root)`
4. Click "Save"
5. Wait 2-3 minutes for deployment

### Step 5: Verify

Your site will be available at:

- `https://[username].github.io/portfolio/` (if repo is named "portfolio")
- `https://[username].github.io/` (if repo is named "[username].github.io")

## Post-Deployment

### Update Content

After making changes:

```bash
git add .
git commit -m "Update [description of changes]"
git push
```

GitHub Pages will automatically rebuild (takes 1-2 minutes).

### Custom Domain (Optional)

1. Buy domain from registrar (Namecheap, Google Domains, etc.)
2. In repository Settings → Pages → Custom domain
3. Enter your domain: `www.asimriaz.com`
4. Add DNS records at your registrar:
   ```
   Type: CNAME
   Name: www
   Value: [username].github.io
   ```

## Troubleshooting

### Site Not Loading

- Check GitHub Pages is enabled in Settings
- Verify branch is set to `main`
- Wait 5 minutes after first deployment

### Styles Not Loading

- Check file paths in `index.html` are relative
- Clear browser cache
- Check browser console for errors

### Links Broken

- Use relative paths: `css/styles.css` not `/css/styles.css`
- Ensure file names match exactly (case-sensitive)

## Quick Reference Commands

```bash
# Check status
git status

# Add all changes
git add .

# Commit changes
git commit -m "Your message here"

# Push to GitHub
git push

# View remote URL
git remote -v
```

## Success Checklist

After deployment, verify:

- [ ] Site loads at GitHub Pages URL
- [ ] All sections display correctly
- [ ] Navigation works
- [ ] Responsive on mobile
- [ ] Contact links work
- [ ] No console errors

---

**Your portfolio is now live! 🎉**
