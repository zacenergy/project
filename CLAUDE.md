# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a portfolio website built with vanilla HTML, CSS, and JavaScript. It features a responsive design with sections for hero, about, projects, and contact information.

## Project Structure

```
/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # Main stylesheet with responsive design
├── js/
│   └── script.js       # Interactive features and animations
├── images/             # Project images and screenshots
│   └── README.md       # Instructions for adding project images
└── CLAUDE.md          # This file
```

## Development Commands

This is a static website that can be opened directly in a browser:

```bash
# Open the website in your default browser (macOS)
open index.html

# Or serve locally with Python (if available)
python3 -m http.server 8000
# Then visit http://localhost:8000

# Or serve with Node.js http-server (if installed)
npx http-server . -p 8000
```

## Key Features

- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Smooth Scrolling**: Navigation links scroll smoothly to sections
- **Mobile Menu**: Hamburger menu for mobile navigation
- **Animations**: Scroll-triggered animations for project cards and elements
- **Modern Styling**: Gradient backgrounds, hover effects, and clean typography

## Customization Notes

- Update personal information in `index.html` (name, skills, contact info)
- Replace project placeholders with actual project details
- Add project screenshots to `/images/` folder (400x250px recommended)
- Modify colors and styling in `css/style.css` as needed
- Skills tags can be easily modified in the HTML