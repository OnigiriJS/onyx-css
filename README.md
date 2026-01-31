# Onyx CSS Framework

**Onyx CSS** is a modern, production-ready CSS framework designed for **OnigiriJS**.  
It provides a dark-luxury design system, a rich set of reusable UI components, and a powerful utility layer — all written in pure CSS.

No JavaScript. No build step. Just drop it in and build.

---

## Features

- CSS custom property–driven design system
- Built-in dark theme with light theme override
- 25+ core UI components with extensive variants
- Utility classes for layout, spacing, typography, and responsiveness
- Framework-agnostic (works with any HTML or JS framework)
- Designed specifically for OnigiriJS

---

## Getting Started

### Include the CSS

Download `onyx.css` and include it in your project:

```html
<link rel="stylesheet" href="onyx.css">
````

---

## Themes

Onyx uses CSS variables for theming.

### Dark Theme (Default)

```html
<body>
```

### Light Theme

```html
<body data-theme="light">
```

You can override any token globally or per component:

```css
:root {
  --color-primary: #10b981;
}
```

---

## Design Tokens

Onyx exposes a full design token system via CSS variables:

* Colors
* Spacing scale
* Typography
* Border radius
* Shadows
* Z-index scale
* Transitions

This allows easy customization without modifying source files.

---

## Components

Onyx includes the following core component groups:

### Layout

* Container
* Grid system
* Flex utilities

### Typography

* Headings
* Paragraphs
* Inline text utilities
* Code blocks
* Blockquotes

### UI Components

* Buttons
* Cards
* Badges
* Alerts
* Toasts
* Modals
* Dropdowns
* Tabs
* Accordions
* Pagination
* Tooltips
* Popovers

### Forms

* Inputs
* Textareas
* Selects
* Checkboxes
* Radios
* Switches
* Input groups
* Validation states

### Data Display

* Tables
* List groups
* Avatars
* Images
* Progress bars
* Spinners
* Skeleton loaders

### Utilities

* Spacing
* Colors
* Borders
* Shadows
* Display
* Positioning
* Overflow
* Opacity
* Cursor
* Animations
* Responsive helpers

---

## Buttons

```html
<button class="btn btn-primary">Primary</button>
<button class="btn btn-outline">Outline</button>
<button class="btn btn-ghost">Ghost</button>
<button class="btn btn-lg btn-success">Large</button>
```

### Variants

* `btn-primary`
* `btn-secondary`
* `btn-success`
* `btn-warning`
* `btn-error`
* `btn-outline`
* `btn-ghost`
* `btn-link`

### Sizes

* `btn-xs`
* `btn-sm`
* `btn-lg`
* `btn-xl`

---

## Cards

```html
<div class="card card-hover">
  <h3 class="card-title">Card Title</h3>
  <p>Card content goes here.</p>
</div>
```

### Variants

* `card-hover`
* `card-shadow`
* `card-flat`
* `card-glow`

---

## Forms

```html
<div class="form-group">
  <label class="form-label">Email</label>
  <input type="email" class="form-control" placeholder="you@example.com">
</div>
```

### Validation States

* `.is-valid`
* `.is-invalid`

---

## Navigation

```html
<nav class="navbar">
  <a class="navbar-brand">Onyx</a>
  <ul class="navbar-nav">
    <li><a class="nav-link active">Home</a></li>
    <li><a class="nav-link">Docs</a></li>
  </ul>
</nav>
```

Includes:

* Navbar
* Breadcrumbs
* Tabs
* Pagination

---

## Responsive Utilities

Onyx includes responsive helpers for common breakpoints.

```html
<div class="grid md:grid-cols-2 sm:grid-cols-1">
```

### Breakpoints

* `lg:` ≤ 1024px
* `md:` ≤ 768px
* `sm:` ≤ 640px

---

## Animations

Utility animation classes:

* `animate-fadeIn`
* `animate-fadeOut`
* `animate-slideInUp`
* `animate-slideInDown`
* `animate-pulse`
* `animate-glow`

---

## Browser Support

* Chrome
* Firefox
* Safari
* Edge

Modern browsers with CSS variable support are required.

---

## Philosophy

Onyx CSS follows a few core principles:

* Consistent design tokens
* Predictable class naming
* Variants over duplication
* CSS-first, JavaScript optional
* Production-ready defaults

---

## Roadmap

* Optional JavaScript helpers (modals, toasts, dropdowns)
* Additional layout primitives
* Accessibility refinements
* Documentation site

---

## License

BSD-3-Clause License
© 2026 Onyx CSS

---

## Built for OnigiriJS

Onyx CSS is designed as the visual foundation of the **OnigiriJS ecosystem**, while remaining flexible enough for any project.

**Dark. Precise. Powerful.**
