# Task: CSS - Laundry Services Hero Section

TuteDude MERN Stack course. Built with plain HTML and CSS only.

## Files
- `index.html` - navbar and hero section structure
- `style.css` - all styling
- `README.md` - this file

## How to run
1. Keep all files in the same folder.
2. Open `index.html` in a browser (or use VS Code Live Server).

## Implementation notes
- Navbar: logo on the left, Home / Services / About Us / Contact Us in the
  middle, username on the right. Uses `display: inline` / `inline-block`
  only, no Flexbox.
- Hero: two divs. Left has heading, description and "Book a service today!"
  button. Right shows a laundry illustration (inline SVG).
- Navbar (12vh) + hero (88vh) = 100vh, with `box-sizing: border-box`,
  so the page does not scroll.
- Sizes use `vw` and `vh` units.