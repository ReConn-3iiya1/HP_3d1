# Copilot Instructions for myHomePage

## Project Overview
This is a static HTML website using HTML5 Boilerplate as the foundation. It's a simple personal homepage with no server-side logic or dynamic content generation.

## Architecture
- **Single Page**: The site consists of a single `index.html` file as the entry point.
- **Asset Organization**: 
  - Stylesheets in `css/` directory (e.g., `css/style.css`)
  - JavaScript files in `js/` directory (e.g., `js/app.js`)
  - Static assets (images, icons) in the root or dedicated subdirectories
- **No Backend**: Pure client-side static files, no databases or API integrations.

## Developer Workflows
- **Editing**: Modify HTML, CSS, and JS files directly in your editor.
- **Testing**: Open `index.html` in a web browser to preview changes. No build step required.
- **Deployment**: Copy files to a web server or use static hosting services like GitHub Pages.
- **Debugging**: Use browser developer tools for inspecting elements, console logs, and network requests.

## Project-Specific Conventions
- **HTML Structure**: Follows HTML5 Boilerplate template with semantic elements and proper meta tags.
- **CSS**: Custom styles in `css/style.css`, potentially overriding boilerplate defaults.
- **JavaScript**: Application logic in `js/app.js`, loaded at the end of `<body>`.
- **Meta Tags**: Update title, description, and Open Graph tags in `<head>` for SEO and social sharing.
- **Icons and Manifest**: Includes favicon, apple-touch-icon, and `site.webmanifest` for PWA features.

## Key Files
- `index.html`: Main HTML document with boilerplate structure
- `css/style.css`: Primary stylesheet
- `js/app.js`: Main JavaScript file
- `site.webmanifest`: Web app manifest for PWA installation

## Integration Points
- No external APIs or third-party services integrated.
- Static hosting compatible with any web server.

This project emphasizes simplicity and direct file editing for rapid prototyping of personal websites.