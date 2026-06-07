# Premium Developer Portfolio - LOGIN S

A modern, highly responsive developer portfolio built for **LOGIN S** (B.E. CSE AIML student & MERN Stack Developer) following the professional **60-30-10 Color Ratio Rule**.

## 🎨 Design System & The 60-30-10 Color Rule
The visual layout was crafted to follow the standard design rule for color harmony:
- **60% Dominant (Canvas & Page Background):** Dark Deep Slate/Navy (`#0b0f19`) provides a soft, premium backdrop that makes elements pop without straining the eyes.
- **30% Secondary (Layout Structural elements, borders, main text):** Cool slate panels (`#162238` / `#1e293b`), off-white typography (`#f8fafc`), and slate-grey subtext (`#94a3b8`) structure the layout clean and readable.
- **10% Accent (Highlights, borders, calls to action, states):** Neon/Electric Cyan (`#00f2fe`) and Deep Indigo (`#4facfe`) blend to draw the eye to critical visual buttons, active states, progress indicators, and graphics.

## ✨ Interactive Features
- **Typewriter Effect:** Cycles through professional titles (MERN Stack Developer, CSE AIML Student, AI Developer).
- **Project Filters:** Smooth grid sorting that filters projects dynamically between categories (AI & ML, Web/MERN, Hardware/IoT).
- **Timeline Progression:** Custom-designed steps detailing internship experience and academic qualifications.
- **High-Performance Scroll Reveals:** High-speed `IntersectionObserver` scroll listener which fades-in elements on demand.
- **Responsive Navigation:** Smooth glassmorphic navigation bar transitions from desktop layouts to a mobile drawer menu.
- **Simulated Contact Engine:** Provides responsive, asynchronous form feedback for message submissions.

## 🚀 Getting Started

### Prerequisites
You only need a modern web browser to open the portfolio, as there are no heavy frameworks, compiler steps, or packages to compile.

### Running Locally
To run the portfolio on your local computer:

1. **Directly open the index file:**
   Simply double-click `index.html` to open it in your browser.

2. **Using a local web server (Recommended):**
   Using a web server enables accurate performance testing of fonts, icons, and page assets.
   - If you have Python installed, run:
     ```bash
     python -m http.server 8000
     ```
     Then navigate to `http://localhost:8000` in your browser.
   
   - If you have Node.js and npm installed, run:
     ```bash
     npx serve .
     ```
     Then navigate to the URL provided in the console.

## 📁 File Structure
```text
Portfolio/
├── index.html     # Semantic structure and content layout
├── style.css      # Core styles, variables, grid layouts, animations
├── script.js     # Interactivity, typewriter, filters, scroll effects
└── README.md      # Project details
```
