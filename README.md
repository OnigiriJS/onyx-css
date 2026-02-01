# 💎 Onyx CSS Framework

## Quick Start

### Option 1: Full Bundle
```html
<link rel="stylesheet" href="framework/onyx.css">
<link rel="stylesheet" href="framework/onyx.min.css"> // Optional
```

### Option 2: Modular (Recommended)
```html
<!-- Core (required) -->
<link rel="stylesheet" href="framework/core/variables.css">
<link rel="stylesheet" href="framework/core/reset.css">
<link rel="stylesheet" href="framework/core/layout.css">

<!-- Components (choose what you need) -->
<link rel="stylesheet" href="framework/components/buttons.css">
<link rel="stylesheet" href="framework/components/cards.css">

<!-- Utilities (optional) -->
<link rel="stylesheet" href="framework/utilities/all-utilities.css">
```

## Directory Structure

```
onyx-css/
├── framework/
│   ├── core/
│   │   ├── variables.css    (CSS custom properties)
│   │   ├── reset.css        (Base styles & reset)
│   │   └── layout.css       (Grid, flex, container)
│   ├── components/
│   │   ├── buttons.css      (Button components)
│   │   ├── cards.css        (Card components)
│   │   ├── forms.css        (Form elements)
│   │   ├── navigation.css   (Navbar, tabs, pagination)
│   │   ├── alerts.css       (Alerts & notifications)
│   │   ├── badges.css       (Badge components)
│   │   ├── modals.css       (Modal dialogs)
│   │   ├── dropdowns.css    (Dropdown menus)
│   │   ├── tooltips.css     (Tooltips & popovers)
│   │   ├── tables.css       (Table components)
│   │   ├── progress.css     (Progress bars & spinners)
│   │   ├── accordion.css    (Accordion components)
│   │   ├── avatar.css       (Avatars & images)
│   │   └── lists.css        (List groups)
│   ├── utilities/
│   │   ├── display.css      (Display utilities)
│   │   ├── position.css     (Position utilities)
│   │   ├── typography.css   (Text utilities)
│   │   ├── colors.css       (Color utilities)
│   │   ├── borders.css      (Border utilities)
│   │   ├── effects.css      (Shadows, opacity)
│   │   ├── layout-utils.css (Overflow, sizing)
│   │   ├── responsive.css   (Responsive utilities)
│   │   ├── animations.css   (Animation classes)
│   │   └── all-utilities.css (All utilities combined)
│   └── onyx.css             (Full bundle)
└── README.md
```

## Import Order

**IMPORTANT:** Always maintain this order:

1. `framework/core/variables.css` ← MUST be first!
2. `framework/core/reset.css`
3. `framework/core/layout.css`
4. Component modules (any order)
5. Utility modules (any order)

## License

BSD-3-Clause license

---

**💎 Onyx CSS Framework v1.0**
