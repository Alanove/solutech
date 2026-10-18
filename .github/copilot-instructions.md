# GitHub Copilot Instructions

## Styling Rules

### SCSS vs CSS
- **ALWAYS modify SCSS files** (`.scss`) for styling changes
- **NEVER directly edit `styles.css`** - this is a compiled file
- SCSS files are located in `public/css/` directory (e.g., `menu.scss`, `variables.scss`)
- The `styles.css` file is generated from SCSS compilation

### File Structure
- Main SCSS files: `public/css/menu.scss`, `public/css/variables.scss`
- Compiled output: `public/css/styles.css` (DO NOT EDIT)
- Always suggest SCSS modifications instead of CSS edits

### Workflow
1. Make changes to `.scss` files
2. Compile SCSS to CSS using build tools
3. Test the compiled CSS output

## General Rules
- Follow existing code patterns and naming conventions
- Use semantic class names
- Maintain responsive design principles
- Keep styles organized and commented
