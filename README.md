# Reformly Folding - Smart Folding Furniture Website

A modern, responsive website for Reformly smart folding furniture featuring an interactive hero slider, product gallery, and product details pages.

## 📁 File Structure

```
├── index.html        # Main HTML file
├── style.css         # All styling (2,183 lines)
├── script.js         # JavaScript functionality (1,454 lines)
└── README.md         # This file
```

## 🚀 Getting Started

### Option 1: Local Development
1. Clone this repository
   ```bash
   git clone https://github.com/yourusername/reformly-folding.git
   cd reformly-folding
   ```

2. Open `index.html` in your browser
   - Simply double-click the file, or
   - Use a local server (recommended):
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (with http-server installed)
     npx http-server
     ```

3. Navigate to `http://localhost:8000` (or your server's address)

### Option 2: GitHub Pages
1. Push this repository to GitHub
2. Go to **Settings** → **Pages**
3. Under "Source", select **main** branch and **/ (root)**
4. Click **Save**
5. Your site will be live at `https://yourusername.github.io/reformly-folding`

## ✨ Features

- **Hero Slider**: Auto-rotating hero section with manual navigation
- **Responsive Design**: Mobile-first approach with smooth transitions
- **Product Grid**: Interactive product cards with hover effects
- **Category Filtering**: Filter products by category
- **FAQ Section**: Expandable FAQ items
- **Smooth Scrolling**: Navigation with smooth scroll behavior
- **Modern Typography**: Playfair Display & Inter fonts
- **Accessibility**: Semantic HTML and keyboard navigation

## 🎨 Design System

### Color Palette
- **Cream**: `#f5f2ee`
- **Charcoal**: `#1a1a18`
- **Accent**: `#c8a97a` (Gold)
- **Brown**: `#7a6a55`
- **Text**: `#3a3833`

### Typography
- **Headings**: Playfair Display (serif)
- **Body**: Inter (sans-serif)

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Customization

### Change Colors
Edit the CSS variables in `style.css` (lines 14-20):
```css
:root {
  --cream: #f5f2ee;
  --charcoal: #1a1a18;
  --accent: #c8a97a;
  /* ... more colors ... */
}
```

### Update Content
- Edit text in `index.html`
- Replace image URLs in the hero section and product cards
- Update company information in the footer

### Modify Features
- Slider timing: Look for `sliderTimer` in `script.js`
- Animation speeds: Search for `transition` values in `style.css`
- Product data: Update the `products` array in `script.js`

## 📦 External Dependencies

- **Google Fonts**: Playfair Display & Inter (loaded via CDN)
- **Model Viewer**: 3D product preview (from AJAX CDN)
- **Unsplash**: Demo images (can be replaced)

All dependencies are loaded from CDN, no npm packages required.

## 🐛 Troubleshooting

### Images not loading?
- Check image URLs in `index.html`
- Ensure CORS is enabled for external image sources
- Use a local server instead of opening the file directly

### Slider not working?
- Check browser console for JavaScript errors
- Ensure `script.js` is properly linked in `index.html`
- Verify no JavaScript conflicts

### Styles not applying?
- Clear browser cache (Ctrl+Shift+Delete or Cmd+Shift+Delete)
- Verify `style.css` is in the same directory as `index.html`
- Check for CSS file size/load issues

## 📄 License

This project is provided as-is. Feel free to use, modify, and distribute.

## 🤝 Contributing

Contributions are welcome! Please:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📞 Support

For issues or questions, please open an issue on GitHub.

---

**Last Updated**: March 2026  
**Version**: 1.0.0
