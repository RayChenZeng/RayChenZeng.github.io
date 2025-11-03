# GitHub Copilot Instructions for RayChenZeng.github.io

## Repository Overview

This is a personal portfolio website built with Jekyll and hosted on GitHub Pages. The site showcases projects, provides contact information, and includes a resume for engineering applications.

## Technology Stack

- **Jekyll**: Static site generator (v4.2)
- **GitHub Pages**: Hosting platform
- **HTML/CSS**: Frontend markup and styling
- **Liquid**: Templating language used by Jekyll
- **YAML**: Data files for structured content

## Project Structure

```
.
├── _data/              # Data files (YAML)
│   └── projects.yml    # Project information and metadata
├── _includes/          # Reusable HTML components
│   ├── header.html     # Site header component
│   └── footer.html     # Site footer component
├── _layouts/           # Page layouts
│   └── home.html       # Home page layout template
├── assets/             # Static assets (images, PDFs, videos, etc.)
│   ├── Resume.pdf      # Resume file
│   ├── PG_news.pdf     # Publication/news PDF
│   ├── images/         # Image files
│   ├── video/          # Video files
│   └── _config.yml     # Asset configuration
├── index.html          # Main homepage with inline styles
├── style.css           # Main stylesheet (root level)
├── Gemfile.txt         # Ruby gem dependencies
└── README.md           # Project documentation
```

## Building and Testing

### Local Development

Since this is a Jekyll site, you can build and serve it locally:

1. Install dependencies:
   ```bash
   bundle install
   ```

2. Build the site:
   ```bash
   jekyll build
   ```

3. Serve locally (with live reload):
   ```bash
   jekyll serve
   ```

4. View at `http://localhost:4000`

### GitHub Pages Deployment

- The site automatically deploys when changes are pushed to the main branch
- GitHub Pages builds the site using Jekyll automatically
- No manual build or deployment steps are required

### Validation

- **HTML validation**: Ensure valid HTML5 syntax
- **CSS validation**: Check for CSS errors and browser compatibility
- **Responsive design**: Test on multiple screen sizes (mobile, tablet, desktop)
- **Link checking**: Verify all internal and external links work
- **Asset availability**: Confirm all images and files load correctly

## Coding Standards and Best Practices

### HTML/Liquid Templates

- Use semantic HTML5 elements (`<header>`, `<main>`, `<footer>`, `<nav>`, `<section>`)
- Maintain proper indentation (2 spaces)
- Keep inline styles minimal; prefer external stylesheets
- Use descriptive IDs and classes with kebab-case naming
- Ensure accessibility (ARIA labels, alt text for images, proper heading hierarchy)

### CSS

- Follow BEM or similar naming conventions for classes
- Use CSS custom properties (variables) defined in `:root` for theming
- Maintain mobile-first responsive design approach
- Keep specificity low; avoid deep nesting
- Group related styles together with comments

### YAML Data Files

- Maintain consistent structure across entries
- Use proper indentation (2 spaces)
- Include all required fields for each data entry
- Validate YAML syntax before committing

### Content Updates

- **Projects**: Edit `_data/projects.yml` to add/modify projects
- **About text**: Modify content in `index.html` or `_layouts/home.html`
- **Resume**: Replace `assets/resume.pdf` with updated file
- **Portrait**: Add portrait image to assets and configure in site config

## Common Tasks

### Adding a New Project

1. Edit `_data/projects.yml`
2. Add a new entry with required fields (title, description, link, etc.)
3. Follow the existing format and indentation

### Updating Styles

1. The main stylesheet is `style.css` in the root directory
2. Note: `index.html` currently has extensive inline styles in a `<style>` block
3. For global styles, modify `style.css`
4. For page-specific styles, consider the inline styles in `index.html`
5. Use existing CSS custom properties for colors and spacing

### Changing Layout

1. Edit layout files in `_layouts/`
2. Modify component includes in `_includes/`
3. Keep consistent structure with existing templates

### Testing Changes

1. Always test locally with `jekyll serve` before committing
2. Check responsive behavior at different breakpoints
3. Validate HTML and CSS
4. Test in multiple browsers (Chrome, Firefox, Safari, Edge)

## File Conventions

- **Images**: Place in `assets/images/` directory
- **Videos**: Place in `assets/video/` directory
- **Documents**: Store PDFs and other documents in `assets/` (e.g., Resume.pdf)
- **Data**: Keep structured data in `_data/` as YAML files
- **Styles**: Main stylesheet is `style.css` in root; page-specific styles can be inline in HTML
- **Templates**: Layouts in `_layouts/`, reusable components in `_includes/`

## Important Notes

- This is a GitHub Pages site, so Jekyll version and plugins are limited to what GitHub Pages supports
- Avoid adding Ruby gem dependencies that aren't compatible with GitHub Pages
- The site is published at `https://RayChenZeng.github.io/`
- Changes to the main branch automatically trigger a rebuild and deployment
- Keep the site lightweight for fast loading

## Acceptance Criteria for Changes

When making changes to this repository:

1. **Maintain visual consistency**: Match existing design patterns and styles
2. **Preserve responsive design**: Ensure mobile, tablet, and desktop views work properly
3. **Keep accessibility**: Maintain WCAG standards with proper semantic HTML and ARIA attributes
4. **Validate syntax**: Ensure HTML, CSS, and YAML are syntactically correct
5. **Test locally**: Always test with `jekyll serve` before committing
6. **Minimal changes**: Make surgical, focused changes without breaking existing functionality
7. **Document updates**: Update README.md if changing structure or adding features
8. **No unnecessary dependencies**: Only add dependencies if absolutely necessary and compatible with GitHub Pages

## Getting Help

- Jekyll documentation: https://jekyllrb.com/docs/
- GitHub Pages documentation: https://docs.github.com/en/pages
- Liquid templating: https://shopify.github.io/liquid/
