# CALCULATOR — Futuristic Calculator

A sleek, single-file HTML calculator with a cyberpunk / retro-futuristic aesthetic. Zero dependencies, zero build tools — just open and use.

---

## ✦ Features

| Feature | Detail |
|---|---|
| **Single file** | One `.html` file — no npm, no bundler, no server needed |
| **Full arithmetic** | Addition, subtraction, multiplication, division |
| **Smart display** | Auto-scales font size for long numbers |
| **Chained operations** | Seamless operator chaining (e.g. 5 + 3 × 2) |
| **Edge case handling** | Division-by-zero shows `ERR:DIV0` |
| **Keyboard support** | Full numpad + keyboard input (see below) |
| **Ripple effects** | Click/tap feedback on every button |
| **Flash on equals** | Cyan glow flash when result is computed |
| **Animated background** | Scrolling perspective grid |
| **Live ticker** | Status bar at bottom |

---

## ✦ Getting Started

1. Download `calculator.html`
2. Open it in any modern browser (Chrome, Firefox, Edge, Safari)
3. That's it — no internet connection required after the Google Fonts load

---

## ✦ Keyboard Shortcuts

| Key | Action |
|---|---|
| `0–9` | Digit input |
| `.` | Decimal point |
| `+` | Addition |
| `-` | Subtraction |
| `*` | Multiplication |
| `/` | Division |
| `Enter` or `=` | Calculate result |
| `Escape` | Clear / AC |
| `Backspace` | Delete last digit |
| `%` | Percent |

---

## ✦ Design System

| Token | Value | Purpose |
|---|---|---|
| `--glow` | `#00f0ff` | Primary cyan accent |
| `--glow2` | `#ff2d78` | Equals button / orb |
| `--bg` | `#050a0f` | Page background |
| `--panel` | `#0a1520` | Calculator body |
| `--mono` | Share Tech Mono | Display & buttons |
| `--head` | Orbitron | Logo & result number |

---

## ✦ Browser Support

Works in all modern browsers. Requires:
- CSS custom properties (variables)
- CSS Grid & Flexbox
- ES6 JavaScript

---

## ✦ Customization Tips

- **Change accent color**: Edit `--glow` in `:root` to any hex color
- **Change size**: Edit `width: 360px` on `.shell`
- **Dark/Light toggle**: Swap `--bg` and `--panel` to lighter values
- **Remove grid animation**: Delete the `body::before` rule and its `@keyframes gridMove`

---

## ✦ File Structure

```
calculator.html
├── <style>   — all CSS (variables, animations, layout, button styles)
├── <body>    — HTML structure (shell, display, keypad, ticker)
└── <script>  — calculator logic (state machine, keyboard listeners)
```

---

## ✦ License

Free to use, modify, and distribute. No attribution required.

