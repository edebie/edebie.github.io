# Dr. Essam Debie - Academic Portfolio

A clean, professional academic website designed for GitHub Pages hosting.

## 📁 File Structure

```
edebie.github.io/
├── index.html              # Main HTML file
├── data.json              # All dynamic content (publications, grants, teaching, career)
├── index_files/
│   ├── essam.jpg          # Profile photo
│   ├── style.css          # All styles
│   └── js                 # JavaScript for loading and rendering data
```

## ✨ Features

- **JSON-driven content**: All publications, grants, teaching, and career data loaded from `data.json`
- **No build process**: Works directly on GitHub Pages
- **Responsive design**: Mobile-friendly with hamburger menu
- **Smooth animations**: Fade-in effects on scroll
- **Professional styling**: Academic-appropriate design with proper typography
- **Academic metrics**: Impact Factor, Quartile rankings, Best Paper Awards, Citations

## 🔧 Updating Content

### To add/update publications:

Edit `data.json` and add entries to the `publications` array:

```json
{
  "year": 2025,
  "venue": "Conference/Journal Name",
  "title": "Paper Title",
  "authors": "Author list",
  "doi": "10.xxxx/xxxxx",
  "metrics": {
    "impactFactor": 7.3,
    "quartile": "Q1",
    "bestPaper": true,
    "citations": 50
  }
}
```

### To add/update grants:

Edit the `grants` array in `data.json`:

```json
{
  "year": 2023,
  "amount": "$50,000",
  "project": "Project title",
  "source": "Funding source"
}
```

### To add/update teaching:

Edit the `teaching` array in `data.json`:

```json
{
  "title": "Course Name",
  "meta": "Level · Institution · Years",
  "highlight": "Key achievement or description"
}
```

### To add/update career:

Edit the `career` array in `data.json`:

```json
{
  "year": "2023–Present",
  "role": "Position Title",
  "org": "Institution",
  "desc": "Description",
  "current": true
}
```

## 🚀 Deployment

1. Create a repository named `yourusername.github.io`
2. Upload all files maintaining the folder structure
3. Add your profile photo as `index_files/essam.jpg`
4. Enable GitHub Pages in Settings → Pages
5. Your site will be live at `https://yourusername.github.io`

## 🎨 Customization

### Colors

Edit CSS variables in `index_files/style.css`:

```css
:root {
    --accent: #2563eb;        /* Primary color */
    --teal: #0d9488;          /* Secondary color */
    --amber: #d97706;         /* Tertiary color */
    /* ... more colors ... */
}
```

### Fonts

The site uses:
- **Serif**: DM Serif Display (headings)
- **Sans**: Source Sans 3 (body text)
- **Mono**: JetBrains Mono (code/metadata)

Change fonts by editing the Google Fonts link in `index.html`.

## 📝 License

© 2026 Dr. Essam Debie. All rights reserved.
