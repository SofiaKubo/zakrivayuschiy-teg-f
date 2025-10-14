# Zakrivayuschiy Teg

This project, "Zakrivayuschiy Teg" (which translates as "Closing Tag"), is a web-based application developed primarily using HTML and CSS.

## Features

- **Interactive HTML layout**
- **Responsive ("rubber") layout** using modern CSS (including `clamp()` for adaptive typography and flexible containers)
- **CSS animations**: Custom keyframes and animated SVG elements (like a "Like" heart with animated sparks)
- **CSS filters**: Dynamic filters applied to images (blur, hue, sepia, brightness, etc.) for visual effects
- **Accessibility**: Semantic HTML, `alt` attributes, ARIA labels, and keyboard navigation support
- **Lazy loading** for images
- **Modern image formats**: AVIF, WebP, and fallbacks for better performance across devices
- **Custom fonts** via the `fonts/` directory and CSS variables
- **SVG icons** with dedicated folder and documentation
- **Theming and variables**: All main colors, fonts, and sizes are managed via CSS variables in `styles/variables.css`
- **Component-based structure**: Reusable card and button components

## Technologies Used

- **HTML5**: Semantic markup, accessibility best practices
- **CSS3**: Flexbox, grid, variables, custom properties, keyframe animations, filters, transitions, media queries
- **JavaScript** (if present): For advanced interactivity (check the repository for scripts)
- **SVG**: Scalable icons and animated elements
- **Modern image formats**: AVIF, WebP
- **Yandex Praktikum Template**: The basis for initial structure and some styles

## Project Structure

The typical structure of the project looks like this:

```
/zakrivayuschiy-teg-f
├── index.html                 # Main HTML file
├── styles/
│   ├── style.css              # Main stylesheet
│   ├── animations.css         # Keyframes and animation styles
│   ├── variables.css          # CSS variables and theming
│   └── globals.css            # Global resets and base styles
├── fonts/                     # Custom web fonts
├── images/                    # Images in AVIF, WebP, PNG formats
├── svg/
│   └── README.md              # Info about SVG usage
├── favicon.ico
├── README.md                  # Project documentation
└── (script.js)                # JS for interactivity, if present
```

## Getting Started

To run the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/SofiaKubo/zakrivayuschiy-teg-f.git
   ```
2. Navigate to the project directory:
   ```bash
   cd zakrivayuschiy-teg-f
   ```
3. Open `index.html` in your preferred web browser.

Or try the [GitHub Pages demo](https://sofiakubo.github.io/zakrivayuschiy-teg-f/).

## License

This project currently does not specify a license.

## Acknowledgements

- Template: [yandex-praktikum/zakrivayuschiy-teg-f](https://github.com/yandex-praktikum/zakrivayuschiy-teg-f)
