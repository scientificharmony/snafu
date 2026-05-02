# SNAFU Records Website

A modern, cyberpunk-inspired website for Snafu Records, Belfast's electronic music label.

## Features

- ✨ Dark, neon-accented electronic music aesthetic
- 🎵 Animated sound wave visualizations
- 📱 Fully responsive design
- 🎨 Bold typography with Orbitron and Rajdhani fonts
- ⚡ Smooth animations and hover effects
- 🔗 Direct links to all artist platforms and social media

## Deploying to GitHub Pages

### Option 1: Quick Deploy (Recommended)

1. Go to your GitHub repository: https://github.com/scientificharmony/snafu
2. Upload the `index.html` file to the root of your repository
3. Go to **Settings** → **Pages**
4. Under "Source", select **Deploy from a branch**
5. Select the **main** branch and **/ (root)** folder
6. Click **Save**
7. Your site will be live at: `https://scientificharmony.github.io/snafu/`

### Option 2: Using Git Command Line

```bash
# Clone your repository (if you haven't already)
git clone https://github.com/scientificharmony/snafu.git
cd snafu

# Copy the index.html file to the repository
cp /path/to/index.html .

# Add, commit, and push
git add index.html
git commit -m "Add SNAFU Records website"
git push origin main

# Enable GitHub Pages in repository settings
```

## Customization

### Updating Content

Edit the `index.html` file to update:

- **Artists**: Add/remove artist cards in the `.artist-grid` section
- **Services**: Modify service cards in the `.services-grid` section
- **Social Links**: Update URLs in the `.social-links` section
- **Colors**: Change CSS variables in the `:root` section

### Color Scheme

The site uses these neon colors (editable in the CSS `:root` section):

```css
--neon-cyan: #00ffff;
--neon-magenta: #ff00ff;
--neon-yellow: #ffff00;
--deep-purple: #0a0015;
```

## Browser Compatibility

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers

## Performance

- Single HTML file (no external dependencies except Google Fonts)
- Lightweight animations using CSS
- Optimized for fast loading
- No JavaScript frameworks required

## Contact

For questions or updates, visit [linktr.ee/snafubelfast](https://linktr.ee/snafubelfast)

---

**SNAFU RECORDS** • Belfast Electronic Music Label
