# Nice Shot Creatives

A modern, elegant photography studio website featuring video backgrounds, glass-morphism design elements, and a sophisticated portfolio showcase.

## 🌟 Features

- **Cinematic Video Background**: Full-screen video hero section with parallax scrolling
- **Modern Typography**: Clean serif fonts (Inter & Poppins) for professional aesthetics
- **Glass-morphism Design**: Contemporary translucent UI elements with backdrop blur
- **Responsive Portfolio**: Dynamic portfolio grid with real photography backgrounds
- **Professional Styling**: Sophisticated black/white/gray color scheme
- **Smooth Animations**: CSS transitions and hover effects throughout

## 📁 Project Structure

```
nice-shot-creatives/
├── index.html              # Main website file
├── assets/
│   ├── logo.png            # Studio logo
│   ├── cover.png           # Background image
│   ├── cover-video.mp4     # Hero background video
│   └── portfolio/          # Portfolio category images
│       ├── wedding.png
│       ├── portrait.png
│       ├── family.png
│       ├── corporate.png
│       ├── newborn.png
│       ├── graduation.png
│       ├── commercial.png
│       └── special-events.png
└── README.md              # This file
```

## 🚀 Getting Started

### Prerequisites

- Python 3.x installed on your system
- A modern web browser (Chrome, Firefox, Safari, Edge)

### Running the Website

1. **Navigate to the project directory**:
   ```bash
   cd nice-shot-creatives
   ```

2. **Start the local HTTP server**:
   ```bash
   python3 -m http.server 8000
   ```

3. **Open your browser** and visit:
   ```
   http://localhost:8000
   ```

4. **Stop the server** when done:
   - Press `Ctrl + C` in the terminal

### Alternative Server Options

If you prefer other server options:

**Using Node.js (if installed):**
```bash
npx http-server -p 8000
```

**Using PHP (if installed):**
```bash
php -S localhost:8000
```

## 🎨 Design Features

### Hero Section
- Full-screen video background (`cover-video.mp4`)
- Centered typography with clean layout
- Smooth parallax scrolling effect
- Professional call-to-action button

### About Section
- Cover image background with overlay
- Modern grid layout
- Elegant typography with Inter font family

### Services Section
- Numbered service cards (01-06)
- Hover animations and glass effects
- Clean card-based layout

### Portfolio Section
- Real photography backgrounds
- Hover effects with gradient overlays
- Responsive grid system
- Professional category organization

### Contact Section
- Dark theme with professional styling
- Glass-effect form elements
- Organized contact information

## 🛠️ Technical Details

### Video Background
- **Format**: MP4 with H.264 codec for browser compatibility
- **Features**: Autoplay, muted, looping, responsive
- **Fallback**: Background image if video fails to load

### Typography
- **Primary**: Inter (body text, navigation)
- **Secondary**: Poppins (headings, buttons)
- **Weights**: 300, 400, 500, 600

### Browser Support
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📱 Mobile Optimization

The website is fully responsive and optimized for:
- Mobile phones (320px+)
- Tablets (768px+)
- Desktop (1200px+)

## 🔧 Customization

### Updating Content
- Edit `index.html` to modify text content
- Replace images in `assets/` folder
- Update portfolio images in `assets/portfolio/`

### Styling Changes
- All styles are contained within `<style>` tags in `index.html`
- Colors, fonts, and layouts can be customized in CSS
- Glass-morphism effects use `backdrop-filter` and RGBA colors

## 📄 License

This project is created for Nice Shot Creatives photography studio.

## 🤝 Support

For technical support or questions about the website, please contact the development team.

---

**Built with modern web technologies for a professional photography studio experience.** 