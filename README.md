# Leading - Single Page Leadership Training Website

A modern, smooth-scrolling single-page website for leadership training programs at Paylocity.

## ✨ Features

### Single Page Benefits
- **Smooth Scrolling** - Seamless navigation between sections
- **Active Navigation** - Highlights current section automatically
- **Fast Performance** - Everything loads once, instant transitions
- **Mobile Optimized** - Perfect experience on all devices
- **Back to Top Button** - Quick navigation from anywhere

### Sections Included
1. **Home** - Hero section with main learning paths
2. **New Leader** - Journey for new leaders with onboarding options
3. **Playbooks** - 6 practical leadership playbooks
4. **Resources** - Tools, templates, and materials library
5. **Programs** - 3 comprehensive development programs
6. **Continuing Education** - Advanced learning timeline

## 🔗 Direct Section Links

You can link directly to any section:
- `https://yoursite.com/#home`
- `https://yoursite.com/#new-leader`
- `https://yoursite.com/#playbooks`
- `https://yoursite.com/#resources`
- `https://yoursite.com/#programs`
- `https://yoursite.com/#continuing-education`

Perfect for emails, presentations, or sharing specific content!

## 🚀 GitHub Pages Deployment

### Quick Deploy (3 minutes)

1. **Create GitHub Repository**
   - Go to https://github.com/new
   - Name: `leading-website`
   - Select: **Public**
   - Click: **Create repository**

2. **Upload Files**
   - Click: **uploading an existing file**
   - Drag both files:
     - `index.html`
     - `logo.png`
   - Click: **Commit changes**

3. **Enable GitHub Pages**
   - Click: **Settings** → **Pages**
   - Source: **main** branch
   - Click: **Save**
   - Wait 1-2 minutes

4. **Your Live Site**
   ```
   https://[YOUR-USERNAME].github.io/leading-website/
   ```

## 📱 Mobile Experience

Fully responsive design:
- Navigation collapses on mobile
- Sections stack vertically
- Touch-friendly buttons
- Optimized animations

## 🎨 Design Features

- **Colorful Navigation** - Each section has unique gradient colors
- **Floating Bubbles** - Animated background elements
- **Smooth Transitions** - Elegant hover and scroll effects
- **Dark Mode Support** - Automatically adapts to system preference
- **Professional Typography** - Clean, readable fonts
- **Gradient Accents** - Brand colors throughout

## 🛠️ Customization

### Add More Programs
Find the "Programs Section" in `index.html` and add more program cards:

```html
<div class="program-card">
  <h3>🎯 Your Program Name</h3>
  <div class="program-meta">
    <span>📅 Duration</span>
    <span>👥 Format</span>
    <span>🎓 Certification</span>
  </div>
  <p>Program description here...</p>
  <button class="cta-button orange">Learn More</button>
</div>
```

### Add New Sections
1. Copy an existing `<section>` block
2. Change the `id` attribute
3. Add navigation link in the header
4. Update colors/content as needed

### Change Colors
All colors are defined at the top in CSS variables:
```css
:root {
  --brand-orange: #ff8f1c;
  --brand-blue: #4a90e2;
  /* etc... */
}
```

## 🔧 Technical Details

- **File Size**: ~25KB (extremely lightweight)
- **Load Time**: < 1 second
- **Dependencies**: None (pure HTML/CSS/JS)
- **Browser Support**: All modern browsers
- **Offline Ready**: Works after first load

## 📊 Navigation Features

- **Auto-highlighting** - Active section highlighted in menu
- **Smooth scrolling** - Elegant transitions between sections
- **Sticky header** - Navigation always accessible
- **Back to top** - Appears after scrolling down
- **URL hash** - Bookmarkable section links

## 🎯 Use Cases

Perfect for:
- Internal training portals
- Leadership development sites
- Corporate learning platforms
- Professional development programs
- Team onboarding sites

## 💡 Tips

1. **Sharing Sections**: Copy the full URL with `#section-name` to link directly
2. **Presentations**: Use section links to navigate during workshops
3. **Emails**: Link to specific sections for targeted messaging
4. **Mobile**: Site works perfectly on phones/tablets

## 🆘 Support

For questions or customization help, contact the L&D team at Paylocity.

---

**Built with ❤️ for Paylocity Leadership Development**
