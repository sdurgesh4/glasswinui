# GlassWin UI

Modern Glassmorphic CSS Framework inspired by futuristic Windows-style UI.

Lightweight.
Responsive.
Beautiful blur effects.
Easy Bootstrap-like class system.

---
Use jsDelivr: `<link rel="stylesheet"  href="https://cdn.jsdelivr.net/gh/sdurgesh4/glasswinui/glasswin-ui.css" />`

# Features

- Glassmorphic UI
- Modern blur effects
- Responsive grid system
- Buttons
- Forms
- Cards
- Dialogs
- Dropdowns
- Alerts
- Tables
- Carousel
- Marquee
- Hover animations
- Utility classes
- Easy CDN usage

---

# Installation

## Direct CSS

```html
<link rel="stylesheet" href="glasswin-ui.css">
```

---

# CDN Usage

Upload CSS to GitHub + jsDelivr:

```html
<link rel="stylesheet"
href="https://cdn.jsdelivr.net/gh/yourusername/glasswin-ui/glasswin-ui.css">
```

---

# Basic Usage

## Button

```html
<button class="gw-btn gw-btn-primary">
Primary Button
</button>
```

## Card

```html
<div class="gw-card">
  <h2 class="gw-card-title">
    Glass Card
  </h2>

  <p class="gw-card-body">
    Modern glassmorphic component.
  </p>
</div>
```

## Input

```html
<input
type="text"
class="gw-input"
placeholder="Enter your name">
```

## Form Group

```html
<div class="gw-form-group">

  <label class="gw-label">
    Email
  </label>

  <input
  type="email"
  class="gw-input">

</div>
```

## Alert

```html
<div class="gw-alert gw-alert-success">
Saved successfully
</div>
```

## Grid

```html
<div class="gw-grid gw-grid-3">

  <div class="gw-card">1</div>
  <div class="gw-card">2</div>
  <div class="gw-card">3</div>

</div>
```

---

# Components

| Component | Class |
|---|---|
| Button | gw-btn |
| Input | gw-input |
| Textarea | gw-textarea |
| Select | gw-select |
| Card | gw-card |
| Alert | gw-alert |
| Navbar | gw-navbar |
| Table | gw-table |
| Dialog | gw-dialog |
| Badge | gw-badge |
| Dropdown | gw-dropdown |
| Tooltip | gw-tooltip |
| Loader | gw-loader |
| Carousel | gw-carousel |
| Marquee | gw-marquee |

---

# Utility Classes

| Utility | Class |
|---|---|
| Flex | gw-flex |
| Center | gw-flex-center |
| Margin Top | gw-mt-* |
| Padding | gw-p-* |
| Hover Float | gw-hover-float |
| Hover Glow | gw-hover-glow |

---

# Example Layout

```html
<div class="gw-container">

  <div class="gw-navbar gw-glass">

    <h2>GlassWin UI</h2>

    <div class="gw-nav-links">
      <a href="#">Home</a>
      <a href="#">Docs</a>
      <a href="#">About</a>
    </div>

  </div>

  <div class="gw-grid gw-grid-3">

    <div class="gw-card">
      <h3 class="gw-card-title">
        Modern UI
      </h3>
    </div>

    <div class="gw-card">
      <h3 class="gw-card-title">
        Blur Effects
      </h3>
    </div>

    <div class="gw-card">
      <h3 class="gw-card-title">
        Responsive
      </h3>
    </div>

  </div>

</div>
```

---

# Folder Structure

```bash
glasswin-ui/
│
├── glasswin-ui.css
├── README.md
├── LICENSE
└── examples/
```

---

# Publish to npm

```bash
npm init -y
```

```bash
npm publish
```

---

# GitHub CDN

Use:

```html
https://cdn.jsdelivr.net/gh/USERNAME/REPO/file.css
```

---

# License

MIT License
