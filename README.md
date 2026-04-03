# Sri Harshitha — Portfolio

A personal portfolio website for **Sri Harshitha Bommireddypally**, a B.Tech Computer Science & Data Science student at GITAM University, Hyderabad (Class of 2027).

---

## ✨ Features

- **Custom cursor** with a smooth-following ring and hover scaling effects
- **Scroll-triggered reveal animations** via IntersectionObserver
- **Noise texture overlay** for depth and atmosphere
- **Animated grid background** in the hero section
- **Stat cards** with hover lift and accent line transitions
- **Project cards** with left-border slide-in and horizontal nudge on hover
- **Achievement cards** with radial glow effect
- Fully **responsive** — mobile layout at ≤900px breakpoint

---

## 🗂️ Sections

| Section | Description |
|---|---|
| **Hero** | Name, tagline, CTA buttons, and key stats |
| **Skills** | Tech stack grid (languages, frameworks, libraries, tools) |
| **Projects** | 3 featured projects with tags and dates |
| **Achievements** | Awards, workshops, and academic highlights |
| **Contact** | Email, phone, GitHub, LinkedIn + education card |

---

## 🛠️ Tech Stack

**Built with:** Vanilla HTML · CSS · JavaScript (no frameworks)

**Fonts (Google Fonts):**
- `Playfair Display` — headings & display numbers
- `Syne` — UI labels, buttons, nav
- `DM Mono` — body text

**Key techniques:**
- CSS custom properties (`--accent`, `--bg`, etc.) for theming
- `IntersectionObserver` for scroll-reveal (`.reveal` → `.visible`)
- `requestAnimationFrame` loop for smooth cursor ring lag
- CSS `@keyframes` for hero entrance animations and scan-line effect

---

## 🚀 Getting Started

No build step needed — it's a single HTML file.

```bash
# Clone or download the file
git clone https://github.com/Bommireddypally/<repo-name>.git

# Open directly in a browser
open index.html
```

Or drag `index.html` into any browser.

---

## 📁 File Structure

```
portfolio/
└── index.html      # Everything — HTML, CSS, and JS in one file
```

---

## 🎨 Customization

All theme colors are defined as CSS variables at the top of the `<style>` block:

```css
:root {
  --bg: #080b10;        /* page background */
  --accent: #00e5c0;    /* primary teal accent */
  --accent2: #ff6b47;   /* secondary orange (badges) */
  --text: #e8edf2;      /* body text */
  --muted: #6b7f92;     /* secondary text */
}
```

To update content, edit the relevant HTML section directly — projects, skills, and achievements are all plain HTML with no data layer.

---

## 📬 Contact

| Channel | Details |
|---|---|
| Email | srihb9@gmail.com |
| GitHub | [github.com/Bommireddypally](https://github.com/Bommireddypally) |
| LinkedIn | [sri-harshitha-bommireddypally](https://www.linkedin.com/in/sri-harshitha-bommireddypally-b31736294/) |

---

© 2025 Sri Harshitha Bommireddypally · GITAM University, Hyderabad
