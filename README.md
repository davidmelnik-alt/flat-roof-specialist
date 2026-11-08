# The Flat Roof Specialist

Responsive static website for The Flat Roof Specialist, serving Broward and Miami-Dade counties.

## Hosting

GitHub Pages publishes the repository root from `main`. No build step or dependencies are needed.

## Editing

- `index.html`: website content
- `style.css`: responsive layout and styling
- `app.js`: navigation, photo gallery, privacy dialog, and estimate email preparation
- `assets/`: project photographs sourced from the business's existing website

The hero uses responsive 720px and 1200px images and preserves the entire before-and-after photograph.

The estimate form opens the visitor's email app with a prepared email to the business. The visitor must send that email to submit the inquiry.

Preview locally with `python3 -m http.server 8765`.
