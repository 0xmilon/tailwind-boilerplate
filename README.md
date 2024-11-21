# Modern Tailwind CSS Template

A production-ready Tailwind CSS template with component-based architecture using Gulp.js.

## Features

- 🎨 Tailwind CSS with PostCSS processing
- 📦 Component-based architecture
- 🔄 Live reload with BrowserSync
- 📱 Mobile-first responsive design
- 🎯 Semantic HTML structure
- 🚀 Production build optimization

## Prerequisites

- Node.js (v16 or higher)
- npm (v7 or higher)

## Installation

```bash
# Clone the repository
git clone [repository-url]
cd tailwind-gulp-workflow

# Install dependencies
npm install
```

## Development Workflow

```bash
# Start development server
npm run dev

# Build for production
npm run build

# Format code
npm run format
```

## Git Workflow

We follow a feature branch workflow:

1. Create a new branch for each feature/fix:
```bash
git checkout -b feature/feature-name
git checkout -b fix/bug-fix-name
```

2. Make your changes and commit with meaningful messages:
```bash
git add .
git commit -m "feat: add new feature"
# or
git commit -m "fix: resolve issue"
```

3. Push your branch and create a pull request:
```bash
git push origin feature/feature-name
```

4. After review and approval, merge into main branch

## Dependency Management

Keep dependencies up to date:

```bash
# Check for outdated packages
npm outdated

# Update packages
npm update

# Update major versions (careful with breaking changes)
npx npm-check-updates -u && npm install
```

## Project Structure

```
tailwind-gulp-workflow/
├── src/                  # Source files
│   ├── css/             # CSS files
│   ├── components/      # Reusable components
│   ├── js/             # JavaScript files
│   ├── layouts/        # Layout templates
│   └── pages/          # Page templates
├── dist/                # Compiled files
├── gulpfile.js         # Gulp configuration
├── tailwind.config.js  # Tailwind configuration
├── postcss.config.js   # PostCSS configuration
└── package.json        # Project dependencies
```

## Best Practices

1. **Component Development**
   - Keep components small and focused
   - Use semantic HTML
   - Follow BEM naming convention for custom classes

2. **CSS Management**
   - Use Tailwind's utility classes when possible
   - Create custom components for repeated patterns
   - Keep custom CSS minimal

3. **JavaScript**
   - Use ES6+ features
   - Keep functions pure when possible
   - Use meaningful variable names

4. **Version Control**
   - Write meaningful commit messages
   - Keep commits focused and atomic
   - Review code before merging

5. **Performance**
   - Optimize images before adding to the project
   - Minimize custom JavaScript
   - Use lazy loading for images

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

MIT License - feel free to use this template for your projects.
