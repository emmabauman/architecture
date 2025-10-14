# Architecture Company Website

A modern, responsive website for an architecture company featuring clean design and mobile-first approach.

## Features

- 📱 **Responsive Design** - Works seamlessly on mobile, tablet, and desktop
- 🎨 **Modern UI** - Clean, professional design with Inter font family
- 🖼️ **Responsive Images** - Optimized images for different screen sizes using `<picture>` elements
- 🎥 **Video Content** - HTML5 video with captions in English and Spanish
- 📐 **Sass Architecture** - Organized stylesheet structure with breakpoint-based files
- ♿ **Accessible** - Semantic HTML and proper alt attributes

## Technology Stack

- **HTML5** - Semantic markup with responsive images
- **CSS3** - Modern styling with Flexbox
- **Sass** - Organized stylesheet architecture
- **WebP Images** - Optimized image formats for better performance
- **Web Fonts** - Google Fonts (Inter)

## File Structure

```
├── index.html              # Main HTML file
├── css/
│   ├── styles.css          # Compiled CSS
│   └── styles.min.css      # Minified CSS
├── scss/                   # Sass source files
│   ├── _small.scss         # Mobile styles
│   ├── _medium.scss        # Tablet styles  
│   ├── _large.scss         # Desktop styles
│   └── styles.scss         # Main Sass file
├── images/                 # Image assets
│   ├── hero-small.webp     # Mobile hero image
│   ├── hero-med.webp       # Tablet hero image
│   ├── hero-large.webp     # Desktop hero image
│   └── ...                 # Logos and favicons
└── media/                  # Video and caption files
    ├── trimmed_hb.mp4      # Main video file
    ├── trimmed_hb.webm     # WebM video format
    └── *.vtt               # Video caption files
```

## Responsive Breakpoints

- **Small (Mobile)**: Default styles, no media query
- **Medium (Tablet)**: `@media (min-width: 35rem)` - 560px+
- **Large (Desktop)**: `@media (min-width: 60rem)` - 960px+

## Getting Started

1. Clone the repository
2. Open `index.html` in your browser
3. For development with Sass:
   ```bash
   npm install
   npm run sass:watch
   ```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

MIT License - feel free to use for your projects!