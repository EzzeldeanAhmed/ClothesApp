# Copilot Instructions for "not chilly" Codebase

## Overview
This is a static website project for a brand or organization, consisting of several HTML pages, a CSS stylesheet, and an image asset directory. There is no build system, backend, or dynamic scripting detected.

## Major Components
- **HTML Files**: `index.html`, `about.html`, `contact.html`, `ourpolicy.html` are the main pages. Each page is standalone and linked via standard anchor tags.
- **CSS**: All styling is centralized in `style.css`. Update this file for global style changes.
- **Images**: All image assets are stored in the `img/` directory. Use relative paths (e.g., `img/face.png`) in HTML for referencing images.

## Project Conventions
- **File Naming**: Use lowercase and descriptive names for HTML and CSS files. Image files may use spaces and special characters, but prefer simple names for new assets.
- **Navigation**: Each HTML file should include navigation links to all other main pages for consistency.
- **Styling**: All pages should import `style.css` in the `<head>` section. Avoid inline styles; use CSS classes defined in `style.css`.
- **Images**: Reference images using relative paths. Optimize images for web (JPG, PNG, or GIF preferred).

## Developer Workflows
- **Previewing**: Open HTML files directly in a browser to preview changes. No build or serve step is required.
- **Debugging**: Use browser developer tools for inspecting layout, styles, and assets.
- **Adding Pages**: Duplicate an existing HTML file as a template for new pages. Update navigation links and content accordingly.
- **Updating Styles**: Edit `style.css` for global changes. Add new classes as needed and document their purpose in comments.
- **Asset Management**: Place new images in `img/` and reference them with relative paths. Avoid duplicating assets.

## Patterns and Examples
- **Consistent Navigation**: Ensure all pages have a navigation bar linking to `index.html`, `about.html`, `contact.html`, and `ourpolicy.html`.
- **CSS Usage**: Example of linking CSS:
  ```html
  <link rel="stylesheet" href="style.css">
  ```
- **Image Usage**: Example of referencing an image:
  ```html
  <img src="img/face.png" alt="Face">
  ```

## Integration Points
- No external dependencies or frameworks detected. All code is local and static.

## Key Files
- `index.html`, `about.html`, `contact.html`, `ourpolicy.html`: Main content pages
- `style.css`: Central stylesheet
- `img/`: Image assets

## Recommendations for AI Agents
- Maintain consistent navigation and styling across all pages.
- When adding new pages or assets, follow existing naming and linking conventions.
- Document any new CSS classes or major changes in `style.css`.
- Do not introduce build tools, JavaScript, or external dependencies unless explicitly requested.

---
_Last updated: September 22, 2025_
