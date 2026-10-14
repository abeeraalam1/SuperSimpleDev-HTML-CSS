[README.md](https://github.com/user-attachments/files/33450825/README.md)
# HTML & CSS — SuperSimpleDev Course Work

My code from working through [SuperSimpleDev's HTML & CSS full course](https://www.youtube.com/@SuperSimpleDev). It starts with a first "Hello World" page and builds up to a responsive YouTube homepage clone, with all the lesson exercises along the way.

## Final project: YouTube clone

[`youtube.html`](youtube.html) recreates the YouTube homepage with plain HTML and CSS — no frameworks or JavaScript.

- Fixed header with logo, search bar, voice search, and icon buttons with hover tooltips
- Fixed sidebar with navigation links
- Video grid with thumbnails, channel avatars, titles, and view counts
- **Responsive layout** — the grid switches between 1, 2, and 3 columns using media queries
- Styles split into separate files: `general.css`, `header.css`, `sidebar.css`, `video.css`

## What I practiced

| Topic | Where to look |
| --- | --- |
| HTML basics, links, text styling | `intro-to-html/website.html`, `text.html`, `text-exercises.html` |
| Buttons, hover / active states, transitions | `intro-to-html/buttons.html` |
| Inline / block elements, cards | `exercise8.html`, `exercise10.html`, `intro-to-html/5g.html` |
| CSS Grid | `grid.html`, `exercise11.html`, `exercise11d.html` |
| Flexbox | `flexbox.html`, `exercise12.html`, `exercise12e.html`, `12g.html`, `13e.html`, `13f.html`, `styles/lesson13.html` |
| Positioning (fixed, absolute, relative), z-index | `position.html`, `exercise14.html`, `14e.html`, `exercise15e.html`, `intro-to-html/exercise15.html` |
| Rebuilding real UIs | Gmail-style inbox (`13e.html`), tweet (`13f.html`), Discord sidebar (`discord-sider.html`), Amazon product card (`intro-to-html/exercise2.html`), YouTube (`youtube.html`) |

## Running it

No build step or install needed:

```bash
git clone https://github.com/abeeraalam1/SuperSimpleDev-HTML-CSS.git
cd SuperSimpleDev-HTML-CSS
```

Then open any `.html` file in your browser — start with `youtube.html`. For live reload while editing, the VS Code **Live Server** extension works well.

## Folder layout

```
├── youtube.html          # Final project
├── styles/               # CSS for the YouTube clone
├── header/, sidebar/     # Icons for the YouTube clone
├── thumbnails/, channel/ # Video thumbnails and channel pictures
├── intro-to-html/        # Early lessons: text, buttons, first website
├── pictures-exercise/    # Images used in the image exercises
└── *.html                # Lesson exercises (grid, flexbox, position, …)
```

## Credits

Course and exercises by [SuperSimpleDev](https://supersimple.dev/). The YouTube clone is a learning exercise and isn't affiliated with YouTube; logos, icons, and thumbnails belong to their respective owners.
