# AI Educational Website — Todo

## Checklist

- [x] Scaffold HTML shell (doctype, meta, Google Fonts link)
- [x] Write embedded CSS — design tokens, reset, layout grid
- [x] Build Nav — logo left, links right, sticky on scroll
- [x] Build Hero — full-viewport dark section, bold headline, sub-copy, two CTAs
- [x] Build "Courses" section — 3-column card grid with placeholder images
- [x] Build "Why Learn Here" section — 3 stat/feature boxes
- [x] Build "Instructors" section — 3 circular avatar cards
- [x] Build CTA Banner — accent-color band with enroll button
- [x] Build Footer — 3-column links + copyright
- [x] Add minimal JS — scroll animations, sticky nav shadow
- [x] Add review section to this file

---

## Review

### What was built
A single self-contained `index.html` at `CLAUDE-CODE-EXAMPLE/index.html` — no external CSS framework, no build step.

### Sections (top → bottom)
| Section | Description |
|---|---|
| **Nav** | Sticky, frosted-glass bar; logo + 3 links + pill CTA button |
| **Hero** | Full-viewport dark section; gradient headline, announcement pill, 2 CTAs |
| **Courses** | White background; 3-column card grid; `picsum.photos` placeholder images; hover lift + image zoom |
| **Why** | Dark surface; 3-box stat strip (50+ Courses / 10k+ Students / 94% Completion) |
| **Instructors** | White background; 3 circular-avatar cards with name, role, bio |
| **Enroll CTA** | Violet gradient full-width band; white enroll button |
| **Footer** | Dark background; 4-column grid (brand + 3 link columns); copyright row |

### Design choices
- **Palette**: near-black bg `#0a0a0f`, violet accent `#7c3aed`, off-white text `#f0f0f8`
- **Font**: Inter (900 weight for headlines, 400/500/600/700 elsewhere)
- **Placeholder images**: `picsum.photos` (seeded for consistency across reloads)
- **JS**: `IntersectionObserver` fade-in on scroll + sticky nav shadow — no libraries

### Files changed
- `tasks/todo.md` — created (this file)
- `index.html` — created (the website)
