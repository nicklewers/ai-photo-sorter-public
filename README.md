# AI Photo Sorter - Website

This repository hosts the GitHub Pages website for AI Photo Sorter, including:
- Landing page
- Privacy Policy
- Support & FAQ

## 🌐 Live Site

Once GitHub Pages is enabled, your site will be available at:
`https://[your-username].github.io/[repository-name]/`

## 📋 Setup Instructions

1. **Push this repository to GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: AI Photo Sorter website"
   git branch -M main
   git remote add origin [your-repo-url]
   git push -u origin main
   ```

2. **Enable GitHub Pages**
   - Go to your repository settings
   - Navigate to "Pages" in the left sidebar
   - Under "Source", select "Deploy from a branch"
   - Select the `main` branch and `/ (root)` folder
   - Click "Save"

3. **Wait a few minutes** for GitHub to build and deploy your site

4. **Use the URL in App Store Connect**
   - Copy your GitHub Pages URL
   - Use it as your Support URL in App Store Connect
   - Link to `/privacy.html` for Privacy Policy URL

## 📁 File Structure

```
├── index.html      # Landing page
├── support.html    # Support & FAQ page
├── privacy.html    # Privacy Policy
├── styles.css      # Styles for all pages
└── README.md       # This file
```

## ✏️ Customization

### Update Contact Email
Replace `support@aiphotosorter.com` in all HTML files with your actual support email.

### Add App Store Link
Once your app is live, update the "Download on the App Store" button link in `index.html`:
```html
<a href="https://apps.apple.com/app/[your-app-id]" class="btn btn-primary">Download on the App Store</a>
```

### Update Pricing Information
Edit the FAQ section in `support.html` to reflect your actual pricing model.

## 🔗 App Store Connect URLs

Use these URLs in your App Store Connect submission:

- **Marketing URL**: `https://[your-username].github.io/[repository-name]/`
- **Support URL**: `https://[your-username].github.io/[repository-name]/support.html`
- **Privacy Policy URL**: `https://[your-username].github.io/[repository-name]/privacy.html`

## 📱 Mobile Responsive

The site is fully responsive and optimized for both desktop and mobile viewing.

## 🎨 Design

The site features:
- Clean, modern design inspired by Apple's design language
- Mobile-first responsive layout
- Smooth animations and transitions
- Accessible color contrast
- Privacy-first messaging

---

Built for AI Photo Sorter iOS App

