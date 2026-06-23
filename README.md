# Project 2: Responsive Web Layout — DecodeLabs

## 📌 Goal
Build a responsive webpage that works seamlessly across mobile, tablet,
and desktop screen sizes using a mobile-first CSS strategy.

## ✅ Features Implemented
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">` set correctly
- **Mobile-first base CSS** — base styles target small screens, enhanced via `min-width` media queries
- Two breakpoints: `768px` (tablet) and `1024px` (desktop)
- **CSS Grid** for macro page layout (header/sidebar/main/footer)
- **Flexbox** for micro alignment (card gallery, nav items)
- Fluid typography using `clamp()` so text scales smoothly with viewport
- Hamburger navigation using the native **Popover API** (no JavaScript required)
- Accessible touch targets (44px × 44px minimum) for buttons
- No restricted zoom — fully pinch-to-zoom friendly

## 🗂 File Structure
```
project2/
├── index.html
├── style.css
└── README.md
```

## ▶️ How to Run
1. Open `index.html` in any modern browser (Chrome/Edge recommended for full Popover API support).
2. Resize the browser window or open DevTools → Device Toolbar to test responsiveness.

## 🧪 Testing Done
- Tested at 375px (mobile), 768px (tablet), 1024px+ (desktop) widths.
- Verified hamburger menu opens/closes via Popover API on small screens.
- Confirmed Grid layout re-flows correctly at each breakpoint.
- Checked touch target sizes meet accessibility minimums.
- Verified no horizontal scroll/overflow at any screen width.

## 🚀 Tech Used
HTML5, CSS3 (Grid + Flexbox + Media Queries + clamp() + Popover API)
