# CALCVLVS — Brutalist Luxury Calculator

> A high-end, minimalist calculator built with pure HTML, CSS & JavaScript.  
> Glassmorphism meets Brutalist aesthetics — no frameworks, no dependencies, no compromises.

---

## ✦ Preview

![CALCVLVS Screenshot](./preview.png)

---

## ✦ Features

| Feature | Detail |
|---|---|
| **Brutalist Luxury UI** | Gold accents, dark glass surfaces, grain overlay, Bebas Neue typography |
| **Glassmorphism** | `backdrop-filter` blur + layered transparency on all panels |
| **Basic Operations** | Addition, Subtraction, Multiplication, Division |
| **Advanced Functions** | Square Root `√`, Power `xʸ`, Percentage `%`, Sign Toggle `±`, Pi `π` |
| **Calculation History** | Live log panel — click any entry to recall its result |
| **Keyboard Support** | Full keyboard input (`0–9`, `+`, `-`, `*`, `/`, `Enter`, `Backspace`, `Escape`) |
| **Error Handling** | Division by zero, invalid square root input |
| **Responsive Display** | Auto-switches to scientific notation for large numbers |

---

## ✦ Keyboard Shortcuts

| Key | Action |
|---|---|
| `0–9` | Input digits |
| `+ - * /` | Operators |
| `Enter` or `=` | Calculate |
| `Backspace` | Delete last digit |
| `Escape` | Clear all (AC) |
| `%` | Percentage |
| `^` | Power mode |

---

## ✦ Project Structure

```
calcvlvs/
├── index.html      ← Single-file app (HTML + CSS + JS)
├── README.md       ← This file
└── preview.png     ← Screenshot (optional)
```

---

## ✦ Getting Started

No build step required. Open directly in your browser:

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/calcvlvs.git
cd calcvlvs

# Open in browser
xdg-open index.html   # Linux
open index.html        # macOS
```

Or serve it locally:

```bash
# Using Python (any machine with Python 3)
python3 -m http.server 8080
# Then visit http://localhost:8080
```

---

## ✦ Pushing Updates to GitHub

```bash
# 1. Stage all changes
git add .

# 2. Commit with a clear message
git commit -m "feat: upgrade to Brutalist Luxury UI v2 with advanced math and history log"

# 3. Push to your main branch
git push origin main
```

> **First time pushing?** Set up the remote first:
> ```bash
> git remote add origin https://github.com/YOUR_USERNAME/calcvlvs.git
> git branch -M main
> git push -u origin main
> ```

---

## ✦ Tech Stack

- **HTML5** — Semantic structure
- **CSS3** — Custom properties, Grid, `backdrop-filter`, keyframe animations
- **Vanilla JS** — Zero dependencies, event delegation, full keyboard support
- **Google Fonts** — Bebas Neue (display) + DM Mono (interface)

---

## ✦ License

MIT — free to use, fork, and modify.

---

<p align="center">
  Built with precision · No frameworks were harmed
</p>
