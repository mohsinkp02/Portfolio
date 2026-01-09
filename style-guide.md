# Portfolio Design System & Style Guide

## 1. Core Visual Identity

### Color Palette
**Primary Colors**
- **Navy 900 (Background):** `#0f172a` (Tailwind: `bg-slate-900` / Custom `navy-900`)
- **Navy 800 (Cards/Surfaces):** `#1e293b` (Tailwind: `bg-slate-800` / Custom `navy-800`)
- **Cyan 500 (Accent):** `#06b6d4` (Tailwind: `text-cyan-500`, `bg-cyan-500`)

**Text Colors**
- **Primary Text:** `#f8fafc` (Slate 50)
- **Secondary Text:** `#cbd5e1` (Slate 300)
- **Muted Text:** `#94a3b8` (Slate 400)

### Typography
**Font Families**
- **Headings:** `Playfair Display`, serif (Weights: 600, 700)
- **Body:** `Inter`, sans-serif (Weights: 300, 400, 500)
- **Code/Tech:** `JetBrains Mono`, monospace

**Scale**
- **H1:** `text-4xl md:text-6xl`
- **H2:** `text-3xl md:text-4xl`
- **Body:** `text-base` (1rem)

## 2. UI Components

### Buttons
**Primary Button**
- **Background:** Transparent with Cyan Border or Solid Cyan
- **Text:** Cyan or Navy (on solid)
- **Border:** `border-2 border-cyan-500`
- **Radius:** `rounded-full`
- **Padding:** `px-6 py-2` or `px-8 py-3`
- **Hover:** `bg-cyan-500 text-slate-900` or `scale-105`

### Cards (Projects/Certificates)
- **Background:** `bg-slate-800` or `bg-navy-800`
- **Border:** `border border-slate-700`
- **Radius:** `rounded-xl` or `rounded-2xl`
- **Hover:** `border-cyan-500/50 shadow-lg shadow-cyan-500/20 transform -translate-y-1`

### Profile Images
- **Container:** Circular (`rounded-full`)
- **Aspect Ratio:** 1:1 (`aspect-square`)
- **Fit:** `object-cover`
- **Position:** `object-center` (or `object-top` for portraits)
- **Border:** `border-4 border-cyan-500/30`

## 3. Spacing & Layout
- **Section Padding:** `py-20` (5rem) or `py-24` (6rem)
- **Container:** `max-w-7xl mx-auto px-4 sm:px-6 lg:px-8`
- **Grid Gap:** `gap-6` or `gap-8`

## 4. Interactive States
- **Transitions:** `transition-all duration-300 ease-in-out`
- **Focus:** `focus:outline-none focus:ring-2 focus:ring-cyan-500 focus:ring-offset-2 focus:ring-offset-slate-900`

## 5. Responsive Breakpoints
- **Mobile:** Default (< 640px)
- **Tablet:** `md:` (>= 768px)
- **Desktop:** `lg:` (>= 1024px)
