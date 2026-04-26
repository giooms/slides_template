# slides_template

A lightweight, ready-to-fork template for creating **slides and scientific posters** using [remark](https://github.com/gnab/remark) + [KaTeX](https://github.com/Khan/KaTeX) and custom CSS helpers. Supports both talk decks and conference posters with full LaTeX math rendering.

## Quick start

### Installation
```bash
git clone https://github.com/giooms/slides_template.git
cd slides_template
```

### Serve locally
```bash
python -m http.server 8001
```
Open http://localhost:8001 in your browser.

## Modes

### 📊 Slides Mode (Presentation Decks)

Create presentation slides using [remark](https://github.com/gnab/remark).

1. Edit your slides in [talk.md](talk.md)
2. Open [index.html](index.html) in your browser
3. Custom styles: [assets/style.css](assets/style.css) and [assets/grid.css](assets/grid.css)

**Navigation:** 
- Arrow keys to advance slides
- Press `H` for help

### 📌 Poster Mode (Scientific Posters)

Create single-page scientific posters similar to [posterdown](https://github.com/brentthorne/posterdown).

1. Edit your poster in [poster.md](poster.md)
2. Open [poster.html](poster.html) in your browser
3. Poster styles: [assets/poster.css](assets/poster.css)

**Features:**
- Multi-column layouts (customizable via CSS Grid)
- Professional header with title, authors, and affiliations
- Full KaTeX math support for equations
- Print-friendly design for PDF export
- Responsive design (adapts to different screen sizes)

#### Poster Structure
The poster template includes:
- **Header section**: Title, authors, affiliations, and institution logo
- **Content columns**: Default 3-column layout for main content
- **Results section**: Multi-column results display
- **Conclusions**: Highlighted conclusion section
- **References**: Formatted reference list

Modify the column count by editing `.poster-columns` grid in [assets/poster.css](assets/poster.css):
```css
.poster-columns {
    grid-template-columns: repeat(3, 1fr);  /* Change 3 to 2, 4, etc. */
}
```

## Export to PDF

### Slides → PDF
Use [Decktape](https://github.com/astefanutti/decktape):
```bash
decktape remark http://localhost:8001 your-slides.pdf
```

### Poster → PDF
Use [Decktape](https://github.com/astefanutti/decktape):
```bash
decktape http://localhost:8001/poster.html your-poster.pdf
```

Or print directly from your browser (Ctrl+P or Cmd+P) and select "Save as PDF".

