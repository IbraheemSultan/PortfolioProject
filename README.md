# PortfolioProject

A modern, responsive portfolio website built with Tailwind CSS, Bootstrap Icons, Font Awesome, and AOS for smooth animations. This project showcases personal branding, skills, and work using custom themes and a visually appealing layout.

## Features

- Responsive design using Tailwind CSS
- Custom theme colors and utility classes
- SVG logo and navigation bar
- Integration of Bootstrap Icons, Font Awesome, and AOS
- Image assets for branding and backgrounds

## Project Structure

```
PortfolioProject/
├── index.html           # Main portfolio website
├── src/
│   └── input.css        # Custom Tailwind CSS and theme styles
├── dist/
│   └── output.css       # Compiled CSS output
├── image/               # Logos, backgrounds, icons
├── package.json         # Dependencies and build scripts
├── package-lock.json    # Dependency lock file
├── node_modules/        # Installed packages
└── .git/                # Git repository
```

## Getting Started

1. **Install dependencies:**
   ```powershell
   npm install
   ```
2. **Build CSS:**
   ```powershell
   npm run build-css
   ```
   This compiles `src/input.css` to `dist/output.css` using Tailwind CSS.
3. **Open `index.html` in your browser** to view the portfolio.

## Customization

- Edit `src/input.css` to change theme colors or add new styles.
- Add or replace images in the `image/` folder for your own branding.
- Modify `index.html` to update content, sections, or layout.

## Dependencies

- [Tailwind CSS](https://tailwindcss.com/)
- [Bootstrap Icons](https://icons.getbootstrap.com/)
- [Font Awesome](https://fontawesome.com/)
- [AOS (Animate On Scroll)](https://michalsnik.github.io/aos/)

## License

This project is open source and available under the MIT License.
