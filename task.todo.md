# AI Educational Website — Task Plan

## Design Vision
Single-page HTML site with a premium agency aesthetic:
- Dark/light split palette with bold typography
- Smooth gradient accents (electric blue + violet)
- CSS-only image mockups (abstract SVG shapes, placeholders)
- Clean sections with generous whitespace

## Sections
1. Hero — bold headline, subtext, CTA button, abstract AI illustration mockup
2. Features / What You'll Learn — 3-column card grid with icon mockups
3. Courses — horizontal scrollable course cards with image mockups
4. Testimonials — quote cards with avatar mockups
5. Newsletter CTA — email signup strip
6. Footer — links, logo, tagline

## Todos
- [x] Set up HTML boilerplate + embedded CSS + Google Fonts (Inter)
- [x] Build Hero section with SVG/CSS neural network illustration mockup
- [x] Build Features section (6 cards)
- [x] Build Courses section (4 course cards with image mockups)
- [x] Build Testimonials section (3 quote cards)
- [x] Build Newsletter CTA + Footer
- [x] Polish: hover effects, responsive layout, micro-animations

## Push to GitHub Plan

- [x] `git init` — initialize local git repository
- [x] `git add` — stage all project files (index.html, claude.md, task.todo.md)
- [x] `git commit` — create initial commit
- [x] `gh repo create` — create new GitHub repo named `claude-code-example` (public)
- [x] `git push` — push main branch to GitHub remote

## Review (Push to GitHub)

Initialized a new git repo, committed all 3 project files (`index.html`, `claude.md`, `task.todo.md`), and pushed to a new public GitHub repo at https://github.com/OS136/claude-code-example.

## Review

Single `index.html` file (~450 lines), no external dependencies except Google Fonts.

**Sections built:**
- **Nav** — fixed, blur backdrop, gradient logo
- **Hero** — animated SVG neural network illustration, 2 floating stat badges with CSS animation, 3 key stats
- **Features** — 6 cards with gradient top-border hover effect and color-coded SVG icons
- **Courses** — 4 cards, each with a unique hand-crafted SVG image mockup (deep learning, ML, LLMs, CV)
- **Testimonials** — 3 quote cards with gradient avatar initials
- **CTA** — email signup strip with dot-pattern background
- **Footer** — 4-column grid layout

**Design details:**
- Dark palette (`#09090f` base) with electric blue + violet gradient accents
- Inter 800/900 display type with tight letter-spacing
- Responsive down to mobile (single column at 600px, nav collapses)
- CSS-only image mockups: SVGs with gradients, no external images needed
