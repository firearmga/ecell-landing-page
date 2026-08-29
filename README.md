# E-Cell, UIET KUK — Landing Page

A responsive landing page for the Entrepreneurship Cell of University
Institute of Engineering and Technology (UIET), Kurukshetra University.
Re-themed around the official E-Cell mark: near-black navy ground, the
mark's signature red as the single accent, and warm off-white text.

## What changed from the previous version

- **Palette rebuilt from the logo.** Colors were sampled directly from the
  uploaded mark: background `#0C131B` (matches the logo's own background
  exactly, so the lockup blends in seamlessly with no visible edge), accent
  red `#EA2418`, and off-white ink `#F4F1EA`.
- **Logo integrated into the nav** (`assets/logo.png`) — cropped and cleaned
  from the source artwork, replacing the previous placeholder mark.
- **Favicon** (`assets/favicon.png`) — a transparent-background crop of just
  the flame-figure icon from the mark.
- **The "Join Us" section is now the one inverted, high-contrast moment on
  the page** — a solid red panel (rather than the old dark panel), echoing a
  physical ink stamp being pressed onto the page.
- **The nav's double rule now closes with a thin red line**, echoing the
  underline beneath "E-CELL" in the mark itself.
- Kept all of your content edits as-is (event/team placeholders, lorem ipsum
  copy, UIET KUK contact details) — only the logo integration and the one
  mismatched mailto address (hero "Apply" button was still pointing at an
  old placeholder domain; it now matches the contact section's
  `ecell-uiet@kuk.ac.in`) were touched.

## Structure

```
ecell-uiet/
├── index.html
├── style.css
├── script.js
├── assets/
│   ├── logo.png       — nav lockup (figure + wordmark)
│   └── favicon.png     — cropped, transparent-background icon
└── README.md
```

## Running it

No build step. Open `index.html` directly, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Still to fill in

The page still has your placeholder copy in a few spots — worth a pass
before publishing:
- Hero "On the books" stats (`XYZ`, `XY`, `X,XX,XYZ`, `0X`)
- About section heading/body/list (currently lorem ipsum)
- About pull-quote attribution ("Headecell")
- Team names ("Name here" ×6) and initials tags (HEAD/VC/SI/HOE/HDC/HFO)
- Join Us headline/subhead (currently lorem ipsum)
- Pitch Fest prize amount (`&#8377;XYZXYZ`)
- Startup Trail event description (currently lorem ipsum)
