# The Flat Roof Specialist

Responsive static website for The Flat Roof Specialist, serving Broward and Miami-Dade counties.

## Hosting

GitHub Pages publishes the repository root from `main`. No build step or dependencies are needed.

## Editing

- `index.html`: website content
- `style.css`: responsive layout and styling
- `app.js`: navigation, photo gallery, privacy dialog, and estimate email preparation
- `assets/`: project photographs sourced from the business's existing website

The hero uses responsive 800px and 1448px versions of a finished-roof photo from the business’s Google Maps listing. CSS frames only the lower finished roof photograph as a full-width hero background with a dark overlay for legible text. Before-and-after photos remain in the gallery.

The estimate form opens the visitor's email app with a prepared email to the business. The visitor must send that email to submit the inquiry.

Preview locally with `python3 -m http.server 8765`.
