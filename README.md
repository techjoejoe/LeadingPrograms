# Leading - Leadership Training Website

A modern, interactive website for leadership training programs at Paylocity.

## Pages Included

- **Home** (`index.html`) - Main landing page with navigation to training paths
- **New Leader** (`new-leader.html`) - Journey for new leaders with onboarding options
- **Resources** (`resources.html`) - Leadership playbooks and resources dashboard
- **Programs** (`programs.html`) - Overview of leadership development programs
- **Continuing Education** (`continuing-education.html`) - Ongoing leadership learning paths

## Features

- Fully responsive design (mobile, tablet, desktop)
- Dark mode support
- Animated UI elements with floating bubbles
- Consistent navigation across all pages
- Paylocity branding with colorful gradient elements

## GitHub Pages Deployment

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right and select "New repository"
3. Name your repository (e.g., `leading-website`)
4. Choose "Public" (required for free GitHub Pages)
5. Click "Create repository"

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface**
1. On your new repository page, click "uploading an existing file"
2. Drag and drop all files from the `leading-website` folder
3. Commit the files with a message like "Initial website upload"

**Option B: Using Git Command Line**
```bash
cd leading-website
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/leading-website.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. In your repository, click "Settings"
2. Scroll down to "Pages" in the left sidebar
3. Under "Source", select "Deploy from a branch"
4. Under "Branch", select "main" and "/ (root)"
5. Click "Save"

### Step 4: Access Your Website

After 1-2 minutes, your website will be live at:
```
https://YOUR-USERNAME.github.io/leading-website/
```

## File Structure

```
leading-website/
├── index.html                    # Home page
├── new-leader.html              # New Leader Journey page
├── resources.html               # Resources/Playbooks page
├── programs.html                # Programs page
├── continuing-education.html    # Continuing Education page
├── logo.png                     # Leading logo
└── README.md                    # This file
```

## Customization Tips

### Updating Content
- All HTML files use inline CSS, so styling is self-contained
- To change colors, update the CSS variables at the top of each file
- Logo can be replaced by updating `logo.png`

### Adding New Pages
1. Copy an existing HTML file as a template
2. Update the navigation to include your new page
3. Add the new page link to all other pages' navigation

### Changing Navigation
The navigation is consistent across all pages. To add/remove items:
1. Find the `<div class="tabs">` section in each HTML file
2. Add or remove `<a class="tab">` elements
3. Update all pages to keep navigation consistent

## Browser Compatibility

- Modern Chrome, Firefox, Safari, Edge
- Mobile Safari (iOS)
- Mobile Chrome (Android)

## Support

For questions or issues with the website, contact the L&D team at Paylocity.

---

**Built with ❤️ for Paylocity Leadership Development**
