# Single-page Design Portfolio

This project is a single-page portfolio website designed to showcase design services and projects. It is built using semantic HTML and CSS with a mobile-first approach.

## Features

- **Responsive Design**: Optimized for mobile, tablet, and desktop devices.
- **Sections**:
  - **Hero**: Introduction to the portfolio.
  - **Services**: Overview of design services offered.
  - **About**: Personal introduction.
  - **My Work**: Image slider showcasing projects.
  - **Contact**: Call-to-action for booking a consultation.
- **Custom Styling**: CSS variables for consistent theming.

## Project Structure

```
/assets
  favicon-32x32.png
  logo.svg
  pattern-*.svg
  image-*.webp
  image-slide-*.jpg
index.html
style.css
README.md
```

## Development Workflow

### 1. Clone the Repository
```bash
git clone <repository-url>
cd single-page-portfolio
```

### 2. Create a New Branch for Features
```bash
git checkout -b feature/<feature-name>
```

### 3. Add Changes
After making changes to files:
```bash
git add .
```

### 4. Commit Changes
```bash
git commit -m "Add <description-of-change>"
```

### 5. Push Changes
```bash
git push origin feature/<feature-name>
```

### 6. Merge Changes
- Open a pull request on GitHub.
- Review and merge the branch into `main`.

### 7. Update Local Repository
```bash
git pull origin main
```

## Deployment

To deploy the project:
1. Ensure all changes are merged into the `main` branch.
2. Use a static hosting service like GitHub Pages:
   ```bash
   git checkout main
   git push origin main
   ```
   Enable GitHub Pages in the repository settings.

## Future Improvements

- Add JavaScript for slider functionality.
- Optimize images for faster loading.


## Author

- Clement Adjei
