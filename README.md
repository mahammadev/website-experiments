# website-experiments

Single-page React landing built with CDN scripts and Tailwind CSS for UNEC nəzdində Sosial–İqtisad Kolleci.

Mobile uses the top-right floating “Menyu” button; desktop/tablet uses the sticky-nav “Menyu paneli” button. Only one toggle shows per breakpoint so they never fight each other.

## Run locally
1. Start a simple static server (for example with Python):
   ```bash
   python -m http.server 5173
   ```
2. Open http://localhost:5173/ in your browser to view the page.

You can also open `index.html` directly in a browser, but using a local server ensures all assets load correctly.
