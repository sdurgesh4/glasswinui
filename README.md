# GlassWin UI

Modern Glassmorphic CSS Framework inspired by futuristic Windows-style UI.

<a href="https://sdurgesh4.github.io/glasswin-ui/">
  <img src="https://img.shields.io/badge/🚀%20Launch%20Demo-GlassWinUI-8A2BE2?style=for-the-badge">
</a>

---

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
<link rel="stylesheet"  href="https://cdn.jsdelivr.net/gh/sdurgesh4/glasswinui/glasswin-ui.css" />
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


# GlassWin UI v2.0 — Class Reference & Tutorial
# Modern Glassmorphic CSS Framework
# Windows 11 Acrylic / Mica inspired


#CDN LINK
--------
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/sdurgesh4/glasswinui/glasswin-ui.css" />

```

# THEMING

Dark theme is the default. Add data-theme="light" to
<html> or <body> to switch to light.

  Dark:  <html>
  Light: <html data-theme="light">

Toggle via JS: 
```html
  document.documentElement.dataset.theme = 'light'; // or 'dark'
```
Use the built-in toggle button:
```html
  <button class="gw-theme-toggle" onclick="
    const h = document.documentElement;
    h.dataset.theme = h.dataset.theme === 'light' ? 'dark' : 'light';
  ">Toggle Theme</button>
```


# GLASS LAYERS

# Three built-in glass surfaces, ordered by opacity:
```html
  .gw-glass       Balanced. Good for cards, navbars.
  .gw-glass-sm    Subtle. Thin blur. Good for tooltips, inputs.
  .gw-glass-deep  Heavy acrylic. Dialogs, hero panels.

Example:
  <div class="gw-glass gw-p-3">
    Deep frosted glass panel
  </div>
```


# CONTAINER
```html
  .gw-container     max-width: 1200px, centered
  .gw-container-sm  max-width: 720px
  .gw-container-lg  max-width: 1400px
```

# TYPOGRAPHY
```html
  .gw-title          Large heading (2.2rem, bold)
  .gw-subtitle       Section heading (1.3rem)
  .gw-heading        Label-style uppercase small heading
  .gw-text           Body text, readable line-height
  .gw-lead           Intro text, slightly larger
  .gw-muted          Muted/secondary text
  .gw-code           Inline code block (monospace)
  .gw-gradient-text  Brand gradient on text

  Text size utilities:
  .gw-text-sm   0.85rem
  .gw-text-lg   1.1rem
  .gw-text-xl   1.3rem

  Font weight:
  .gw-fw-400 / .gw-fw-600 / .gw-fw-700 / .gw-fw-800

  Alignment:
  .gw-text-center / .gw-text-right / .gw-text-left

  Colors:
  .gw-color-primary / .gw-color-success / .gw-color-danger
  .gw-color-warning / .gw-color-muted
```


# BUTTONS

Base class: .gw-btn
Always combine with a variant.
```html
  .gw-btn .gw-btn-primary     Blue gradient, glowing
  .gw-btn .gw-btn-success     Green gradient
  .gw-btn .gw-btn-danger      Red gradient
  .gw-btn .gw-btn-warning     Amber gradient
  .gw-btn .gw-btn-info        Sky blue gradient
  .gw-btn .gw-btn-ghost       Transparent, border only

Sizes:
  .gw-btn-sm    Small (7px 14px)
  (default)     Medium (11px 22px)
  .gw-btn-lg    Large (15px 32px)
  .gw-btn-xl    Extra large (18px 40px)
  .gw-btn-block Full width, centered
  .gw-btn-icon  Square/circle for icon-only buttons

Example:
  <button class="gw-btn gw-btn-primary">Save Changes</button>
  <button class="gw-btn gw-btn-ghost gw-btn-sm">Cancel</button>
  <button class="gw-btn gw-btn-danger gw-btn-lg gw-btn-block">Delete</button>
```

# INPUTS
```html
  .gw-input      Text field
  .gw-select     Dropdown select
  .gw-textarea   Multiline textarea
  .gw-range      Range slider
  .gw-label      Form label (use inside .gw-form-group)
  .gw-form-group Wrapper with 20px bottom margin
  .gw-form-hint  Helper text below input
  .gw-form-error Error message below input

Input states:
  .gw-input-success   Green border + glow
  .gw-input-error     Red border + glow

Input with icon:
  <div class="gw-input-group">
    <span class="gw-input-icon">&#x1F50D;</span>
    <input class="gw-input" placeholder="Search...">
  </div>

Input + button:
  <div class="gw-input-group">
    <input class="gw-input" placeholder="Email">
    <button class="gw-btn gw-btn-primary">Subscribe</button>
  </div>

Full form example:
  <div class="gw-form-group">
    <label class="gw-label">Username</label>
    <input class="gw-input" type="text" placeholder="Enter username">
    <span class="gw-form-hint">Letters and numbers only.</span>
  </div>
```


# TOGGLE SWITCH
```html
  <label class="gw-toggle">
    <input type="checkbox">
    <div class="gw-toggle-track">
      <div class="gw-toggle-thumb"></div>
    </div>
    Enable notifications
  </label>
```
Checked state switches the thumb and glows blue.


# CHECKBOX & RADIO
```html
  <label class="gw-checkbox">
    <input type="checkbox"> Accept terms
  </label>

  <label class="gw-radio">
    <input type="radio" name="plan"> Pro Plan
  </label>
```

#  CARD
```html
  .gw-card          Standard glass card
  .gw-card-acrylic  Heavy blur, stronger glass

Card parts:
  .gw-card-header   Top section with divider
  .gw-card-title    Bold card heading
  .gw-card-subtitle Muted subtitle below title
  .gw-card-body     Content area
  .gw-card-footer   Bottom section with divider

Full example:
  <div class="gw-card">
    <div class="gw-card-header">
      <div>
        <div class="gw-card-title">Analytics</div>
        <div class="gw-card-subtitle">Last 30 days</div>
      </div>
      <span class="gw-badge gw-badge-success">Live</span>
    </div>
    <div class="gw-card-body">Your content here.</div>
    <div class="gw-card-footer">
      <button class="gw-btn gw-btn-primary gw-btn-sm">Details</button>
    </div>
  </div>
```


# NAVBAR
```html
  .gw-navbar         Sticky blurred top bar
  .gw-navbar-brand   Logo / brand name
  .gw-nav-links      Horizontal link group
  .gw-nav-actions    Right-side buttons area

  .gw-nav-links a.active  Highlighted active link

Example:
  <nav class="gw-navbar">
    <a class="gw-navbar-brand" href="#">GlassWin</a>
    <div class="gw-nav-links">
      <a href="#" class="active">Home</a>
      <a href="#">Docs</a>
      <a href="#">About</a>
    </div>
    <div class="gw-nav-actions">
      <button class="gw-btn gw-btn-primary gw-btn-sm">Get Started</button>
    </div>
  </nav>
```


# SIDEBAR
```html
  .gw-sidebar          Glass sidebar panel (260px)
  .gw-sidebar-section  Logical section block
  .gw-sidebar-label    Section heading label
  .gw-sidebar-link     Nav link item
  .gw-sidebar-link.active  Highlighted with primary color

Example:
  <aside class="gw-sidebar">
    <div class="gw-sidebar-section">
      <div class="gw-sidebar-label">Main</div>
      <a class="gw-sidebar-link active" href="#">Dashboard</a>
      <a class="gw-sidebar-link" href="#">Projects</a>
      <a class="gw-sidebar-link" href="#">Settings</a>
    </div>
  </aside>

```


 # TABS
```html
  .gw-tabs       Container (pill-style tab bar)
  .gw-tab        Individual tab button
  .gw-tab.active Currently selected tab

  .gw-tab-content        Hidden by default
  .gw-tab-content.active Shown panel

Example:
  <div class="gw-tabs">
    <div class="gw-tab active" onclick="switchTab(this, 'tab1')">Overview</div>
    <div class="gw-tab"        onclick="switchTab(this, 'tab2')">Details</div>
  </div>

  <div id="tab1" class="gw-tab-content active">Panel 1</div>
  <div id="tab2" class="gw-tab-content">Panel 2</div>

  <script>
  function switchTab(el, id) {
    document.querySelectorAll('.gw-tab').forEach(t => t.classList.remove('active'));
    document.querySelectorAll('.gw-tab-content').forEach(c => c.classList.remove('active'));
    el.classList.add('active');
    document.getElementById(id).classList.add('active');
  }
  </script>
```


 # ALERTS
```html
  .gw-alert .gw-alert-success   Green glass alert
  .gw-alert .gw-alert-danger    Red glass alert
  .gw-alert .gw-alert-warning   Amber glass alert
  .gw-alert .gw-alert-info      Blue glass alert

Example:
  <div class="gw-alert gw-alert-success">File saved successfully.</div>
  <div class="gw-alert gw-alert-danger">Something went wrong.</div>
```


 # TOAST

Place this container once in your page:
  <div class="gw-toast-container" id="toastContainer"></div>
  
```html
Show a toast via JS:
  function showToast(message, duration = 3000) {
    const c = document.getElementById('toastContainer');
    const t = document.createElement('div');
    t.className = 'gw-toast';
    t.textContent = message;
    c.appendChild(t);
    setTimeout(() => {
      t.classList.add('hide');
      setTimeout(() => t.remove(), 300);
    }, duration);
  }

  showToast('Settings saved!');
```


# DIALOG (DRAGGABLE)
```html
HTML structure:
  <div class="gw-dialog-overlay" id="myOverlay">
    <div class="gw-dialog gw-draggable" id="myDialog">
      <div class="gw-dialog-header">
        <span class="gw-dialog-title">Dialog Title</span>
        <div class="gw-dialog-close" onclick="closeDialog()">&#x2715;</div>
      </div>
      <div class="gw-dialog-body">
        Your dialog content goes here.
      </div>
      <div class="gw-dialog-footer">
        <button class="gw-btn gw-btn-ghost gw-btn-sm" onclick="closeDialog()">Cancel</button>
        <button class="gw-btn gw-btn-primary gw-btn-sm">Confirm</button>
      </div>
    </div>
  </div>

Open / close:
  function openDialog()  { document.getElementById('myOverlay').style.display = 'flex'; }
  function closeDialog() { document.getElementById('myOverlay').style.display = 'none'; }

Make it draggable (add after page loads):
  makeDialogDraggable(document.getElementById('myDialog'));

  function makeDialogDraggable(dialogEl) {
    const header = dialogEl.querySelector('.gw-dialog-header');
    let isDragging = false, startX, startY, initLeft, initTop;

    dialogEl.style.position = 'fixed';
    dialogEl.style.left = ((window.innerWidth  - dialogEl.offsetWidth)  / 2) + 'px';
    dialogEl.style.top  = ((window.innerHeight - dialogEl.offsetHeight) / 2) + 'px';
    dialogEl.style.margin = '0';

    header.addEventListener('mousedown', e => {
      isDragging = true;
      startX = e.clientX;
      startY = e.clientY;
      initLeft = parseInt(dialogEl.style.left) || 0;
      initTop  = parseInt(dialogEl.style.top)  || 0;
      dialogEl.style.transition = 'none';
      document.body.style.userSelect = 'none';
    });

    document.addEventListener('mousemove', e => {
      if (!isDragging) return;
      dialogEl.style.left = (initLeft + e.clientX - startX) + 'px';
      dialogEl.style.top  = (initTop  + e.clientY - startY) + 'px';
    });

    document.addEventListener('mouseup', () => {
      isDragging = false;
      dialogEl.style.transition = '';
      document.body.style.userSelect = '';
    });
  }
```


 # TABLE

```html
Wrap the table in .gw-table-wrap for rounded corners.

  <div class="gw-table-wrap">
    <table class="gw-table">
      <thead>
        <tr>
          <th>Name</th>
          <th>Status</th>
          <th>Date</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Alice</td>
          <td><span class="gw-badge gw-badge-success">Active</span></td>
          <td>May 2026</td>
        </tr>
      </tbody>
    </table>
  </div>
```


 # PROGRESS BAR

```html
  .gw-progress           Track (full width)
  .gw-progress-bar       Fill bar (set width via style)
  .gw-progress-success   Green variant
  .gw-progress-danger    Red variant
  .gw-progress-sm        4px height
  .gw-progress-lg        14px height

Example:
  <div class="gw-progress">
    <div class="gw-progress-bar" style="width: 72%"></div>
  </div>

  <div class="gw-progress gw-progress-success gw-mt-2">
    <div class="gw-progress-bar" style="width: 45%"></div>
  </div>
```


# BADGE
```html
  .gw-badge                 Default (glass)
  .gw-badge .gw-badge-primary   Blue tinted
  .gw-badge .gw-badge-success   Green tinted
  .gw-badge .gw-badge-danger    Red tinted
  .gw-badge .gw-badge-warning   Amber tinted

Example:
  <span class="gw-badge gw-badge-primary">New</span>
  <span class="gw-badge gw-badge-success">Active</span>
  <span class="gw-badge gw-badge-danger">Critical</span>
```


# CHIP

```html
  .gw-chip          Pill-shaped selectable tag
  .gw-chip.active   Selected state (primary color)
  .gw-chip-close    X button inside chip

Example:
  <span class="gw-chip active">Design</span>
  <span class="gw-chip">Development</span>
  <span class="gw-chip">React
    <span class="gw-chip-close">&#x2715;</span>
  </span>
```


# AVATAR

```html
  .gw-avatar-sm   32×32
  .gw-avatar      42×42 (default)
  .gw-avatar-lg   56×56
  .gw-avatar-xl   80×80

  .gw-avatar-group  Overlapping group (wrap avatars)

With initials:
  <div class="gw-avatar">JD</div>

With image:
  <div class="gw-avatar gw-avatar-lg">
    <img src="photo.jpg" alt="User">
  </div>

Avatar group:
  <div class="gw-avatar-group">
    <div class="gw-avatar gw-avatar-sm">A</div>
    <div class="gw-avatar gw-avatar-sm">B</div>
    <div class="gw-avatar gw-avatar-sm">C</div>
  </div>
```


# DROPDOWN

```html
  .gw-dropdown         Wrapper (position: relative)
  .gw-dropdown-menu    The floating panel
  .gw-dropdown-menu.right  Align to right edge
  .gw-dropdown-item    Clickable row
  .gw-dropdown-item.danger  Red destructive action
  .gw-dropdown-divider Horizontal separator

Opens on hover. Add class .open for JS control.

Example:
  <div class="gw-dropdown">
    <button class="gw-btn">Options</button>
    <div class="gw-dropdown-menu">
      <div class="gw-dropdown-item">Edit</div>
      <div class="gw-dropdown-item">Duplicate</div>
      <div class="gw-dropdown-divider"></div>
      <div class="gw-dropdown-item danger">Delete</div>
    </div>
  </div>
```


# TOOLTIP

```html
  .gw-tooltip          Wrapper element
  .gw-tooltip-text     The floating label (hidden by default)

Shows on hover.

Example:
  <span class="gw-tooltip">
    Hover me
    <span class="gw-tooltip-text">This is the tooltip</span>
  </span>
```


# LOADER

```html
  .gw-loader           Spinning ring (default 40px)
  .gw-loader-sm        22px
  .gw-loader-lg        60px
  .gw-loader-pulse     Pulsing filled circle

Example:
  <div class="gw-loader"></div>
  <div class="gw-loader gw-loader-sm"></div>
  <div class="gw-loader-pulse"></div>

Skeleton placeholder:
  .gw-skeleton  Shimmering placeholder block

  <div class="gw-skeleton" style="height: 20px; width: 200px;"></div>
  <div class="gw-skeleton gw-mt-2" style="height: 80px;"></div>
```

 # MARQUEE

```html
  <div class="gw-marquee">
    <div class="gw-marquee-inner">
      Item 1 &nbsp;&nbsp; Item 2 &nbsp;&nbsp; Item 3
      &nbsp;&nbsp; Item 1 &nbsp;&nbsp; Item 2 &nbsp;&nbsp; Item 3
    </div>
  </div>

Tip: Duplicate content inside .gw-marquee-inner for
a seamless loop. Pauses on hover.
```


# DIVIDER

```html
  <hr class="gw-divider">

  With label:
  <div class="gw-divider-label">OR</div>
```


# GRID

```html
  .gw-grid .gw-grid-1    1 column
  .gw-grid .gw-grid-2    2 columns
  .gw-grid .gw-grid-3    3 columns
  .gw-grid .gw-grid-4    4 columns
  .gw-grid .gw-grid-5    5 columns

  Gap control:
  .gw-gap-sm   10px
  .gw-gap      20px (default)
  .gw-gap-lg   32px

Collapses to 1 column on mobile (<768px).

Example:
  <div class="gw-grid gw-grid-3 gw-gap-lg">
    <div class="gw-card">1</div>
    <div class="gw-card">2</div>
    <div class="gw-card">3</div>
  </div>
```


# FLEX UTILITIES

```html
  .gw-flex          display: flex
  .gw-flex-center   flex, centered both axes
  .gw-flex-between  flex, space-between
  .gw-flex-end      flex, justify-end
  .gw-flex-col      flex, column direction
  .gw-flex-wrap     flex-wrap
  .gw-items-center  align-items: center
  .gw-items-start   align-items: flex-start
```

# SPACING

```html
Margin top:     .gw-mt-1 to .gw-mt-5
Margin bottom:  .gw-mb-1 to .gw-mb-4
Padding all:    .gw-p-1  to .gw-p-4
Padding X:      .gw-px-1 to .gw-px-3
Padding Y:      .gw-py-1 to .gw-py-3

Scale: 1=8px, 2=16px, 3=24px, 4=32px, 5=48px
```


 # HOVER EFFECTS

```html
  .gw-hover-float   Floats up 5px on hover
  .gw-hover-scale   Scales up 3% on hover
  .gw-hover-glow    Blue glow shadow on hover
  .gw-hover-bright  Brightness boost on hover
```


#  ANIMATIONS

```html
  .gw-fade-in    Fade in
  .gw-slide-up   Slide up from below
  .gw-slide-in   Slide in from left

Stagger delays (combine with animation classes):
  .gw-delay-1   80ms
  .gw-delay-2   160ms
  .gw-delay-3   240ms
  .gw-delay-4   320ms
  .gw-delay-5   400ms

Example — staggered cards:
  <div class="gw-card gw-slide-up gw-delay-1">Card 1</div>
  <div class="gw-card gw-slide-up gw-delay-2">Card 2</div>
  <div class="gw-card gw-slide-up gw-delay-3">Card 3</div>
```


#  UTILITY SHORTCUTS

```html
  .gw-w-full       width: 100%
  .gw-h-full       height: 100%
  .gw-rounded      border-radius: var(--gw-radius)
  .gw-rounded-full border-radius: 999px
  .gw-opacity-50   opacity: 0.5
  .gw-opacity-75   opacity: 0.75
  .gw-truncate     overflow ellipsis, no wrap
```


#  CSS VARIABLES — OVERRIDE ANYTHING

```html
Add this after the CDN link to customize:

  <style>
    :root {
      --gw-primary:       #7c3aed;   /* purple brand */
      --gw-primary-light: #a78bfa;
      --gw-primary-glow:  rgba(124, 58, 237, 0.35);
      --gw-radius:        12px;      /* sharper corners */
      --gw-blur:          30px;      /* more blur */
    }
  </style>
```
Every color, radius, blur level, and shadow uses
CSS variables so you control the whole system.



# COMPLETE PAGE STARTER TEMPLATE

```html
  <!DOCTYPE html>
  <html data-theme="dark">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My App</title>
    <link rel="stylesheet"
      href="https://cdn.jsdelivr.net/gh/sdurgesh4/glasswinui/glasswin-ui.css">
  </head>
  <body>

    <div class="gw-container">

      <nav class="gw-navbar">
        <a class="gw-navbar-brand" href="#">MyApp</a>
        <div class="gw-nav-links">
          <a href="#" class="active">Home</a>
          <a href="#">About</a>
        </div>
        <div class="gw-nav-actions">
          <button class="gw-theme-toggle" onclick="
            const h = document.documentElement;
            h.dataset.theme = h.dataset.theme === 'light' ? 'dark' : 'light';
          ">Toggle Theme</button>
        </div>
      </nav>

      <div class="gw-grid gw-grid-3 gw-mt-3">
        <div class="gw-card gw-slide-up gw-delay-1">
          <div class="gw-card-title">Card One</div>
          <div class="gw-card-body">Content here.</div>
        </div>
        <div class="gw-card gw-slide-up gw-delay-2">
          <div class="gw-card-title">Card Two</div>
          <div class="gw-card-body">Content here.</div>
        </div>
        <div class="gw-card gw-slide-up gw-delay-3">
          <div class="gw-card-title">Card Three</div>
          <div class="gw-card-body">Content here.</div>
        </div>
      </div>

    </div>

  </body>
  </html>
```


# LICENSE: MIT
# GitHub: github.com/sdurgesh4/glasswinui
====================================================
