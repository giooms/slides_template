# slides_template

A lightweight, ready-to-fork slide template using [remark](https://github.com/gnab/remark) + [KaTeX](https://github.com/Khan/KaTeX) and a few custom CSS helpers. Intended for quick creation of talk decks (tested on Windows / Python HTTP server).

## Quick start

- Clone the repo:
  ```
  git clone https://github.com/giooms/slides_template.git
  cd talk-template
  ```
- Serve locally (Windows PowerShell / CMD):
  ```
  python -m http.server 8001
  ```
  Open http://localhost:8001 in your browser.

- Edit slides in `talk.md`.
- Custom styles and layout helpers live in `assets/style.css` and `assets/grid.css`.

## Export to PDF

- Use Decktape to export:
  ```
  decktape remark http://localhost:8001 your-slides.pdf
  ```

