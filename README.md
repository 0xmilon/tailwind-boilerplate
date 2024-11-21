# Modern Tailwind CSS Boilerplate

A production-grade, enterprise-ready boilerplate for modern web development using Tailwind CSS, Gulp, and best practices.

## ✨ Features

- 🎨 **Modern Design System**
  - Tailwind CSS v3.4.15
  - Dark mode support with system preference detection
  - Custom color schemes (neutral, slate)
  - Typography plugin integration
  - Responsive design patterns

- 🛠️ **Advanced Build System**
  - Gulp 5.0.0 workflow
  - PostCSS processing
  - JavaScript minification
  - CSS optimization
  - Live reload with BrowserSync
  - Component-based architecture

- 🔧 **Development Tools**
  - Biome JS for formatting and linting
  - Source maps for debugging
  - Hot module replacement
  - NPM scripts for common tasks
  - Automated dependency updates

- 📦 **Production Ready**
  - Minified assets
  - Optimized builds
  - Cache busting
  - SEO friendly
  - Performance optimized

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone [your-repo-url]
   cd boilerplate
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Build for production**
   ```bash
   npm run build
   ```

## 📁 Project Structure

```
boilerplate/
├── src/                  # Source files
│   ├── css/             # CSS files
│   │   └── app.css      # Main CSS file
│   ├── js/              # JavaScript files
│   │   └── app.js       # Main JS file
│   ├── components/      # Reusable components
│   │   ├── header.html
│   │   ├── footer.html
│   │   └── home/        # Page-specific components
│   └── pages/           # HTML pages
│       └── index.html
├── dist/                # Compiled files
├── gulpfile.js         # Gulp configuration
├── tailwind.config.js  # Tailwind configuration
├── postcss.config.js   # PostCSS configuration
└── package.json        # Project dependencies
```

## 🎨 Customization

### Tailwind Configuration

The template includes a customized `tailwind.config.js` with:
- Custom color schemes
- Dark mode support
- Typography plugin
- Extended theme settings

### Components

Components are modular and can be included using:
```html
@@include('../components/header.html')
```

### Dark Mode

Dark mode is implemented using Tailwind's `dark:` variant and supports:
- System preference detection
- Manual toggle
- Persistent preference storage

## 📜 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run clean` - Clean dist folder
- `npm run format` - Format code with Biome
- `npm run lint` - Lint code with Biome
- `npm run check` - Run Biome checks
- `npm run update-deps` - Update dependencies

## 🔧 Development

### Adding New Pages

1. Create a new HTML file in `src/pages/`
2. Include necessary components
3. Add content between header and footer
4. Run development server to see changes

### Creating Components

1. Add new component in `src/components/`
2. Use Tailwind classes for styling
3. Include in pages using `@@include()`

### Styling

- Use Tailwind utility classes
- Add custom styles in `src/css/app.css`
- Configure theme in `tailwind.config.js`

## 📦 Production Build

The production build:
1. Minifies CSS and JavaScript
2. Optimizes assets
3. Generates sourcemaps
4. Creates production-ready files in `dist/`

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Tailwind CSS](https://tailwindcss.com)
- [Gulp](https://gulpjs.com)
- [PostCSS](https://postcss.org)
- [Biome](https://biomejs.dev)

---

Made with ❤️ for the modern web development community.
