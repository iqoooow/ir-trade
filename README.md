# AURA Gold - XAUUSD Trading Color System

This repository contains the design system tokens and an interactive prototype of a XAUUSD (Gold) Position and Risk Calculator. The brand utilizes **Gold (`#C8A84B`)** as the key accent color set against a premium **Dark Navy (`#1a1a2e`)** background canvas.

## Design Philosophy

For financial products—especially gold trading—visual styling needs to convey **precision, value, and stability**.
- **Dark Navy (`#1a1a2e`)** creates a calm, professional, and deep space that reduces eye strain during long trading sessions.
- **Gold (`#C8A84B`)** is used selectively as an accent (highlights, brand logo, action buttons, active borders, and primary results) to represent wealth, focus, and gold trading itself.
- **BUY (Vibrant Green: `#10b981`)** and **SELL (Vibrant Red: `#f43f5e`)** are optimized with surrounding glow effects (`box-shadow`) to maintain high legibility and instantly communicate trade direction context.

---

## The CSS Color Variables

All variables are declared in `variables.css` and are fully responsive. Here is the direct mapping of variables:

### 1. Canvas & Backgrounds
* `--bg-primary` (`#0f0f1c`): The deepest navy, used as the main background of the page.
* `--bg-secondary` (`#1a1a2e`): The brand dark navy, used for primary containers, sidebars, and panels.
* `--bg-card` (`#23233c`): A slightly lighter navy, providing visual elevation for individual cards and widgets.
* `--bg-card-hover` (`#2d2d4d`): Interactive hover states for items/cards.

### 2. Accent Colors (Gold)
* `--color-gold` (`#C8A84B`): The main brand gold.
* `--color-gold-hover` (`#d8b85b`): A brighter gold for interactive hover states.
* `--color-gold-glow` (`rgba(200, 168, 75, 0.15)`): Subtle gold highlight glow for active cards.

### 3. Typography
* `--text-primary` (`#f1f3f9`): High-contrast light gray-blue, optimized for titles and active numerical values.
* `--text-secondary` (`#a3a8b8`): Balanced gray-blue, used for descriptions and labels.
* `--text-muted` (`#646a7e`): Low-contrast gray-blue, perfect for placeholders, inactive states, and captions.
* `--text-gold` (`#dfc888`): Light gold hue for highlight labels.

### 4. Trading Action Colors
* `--color-buy` (`#10b981`): Bullish Emerald Green.
* `--color-buy-bg` (`rgba(16, 185, 129, 0.1)`): Soft green background tint.
* `--color-sell` (`#f43f5e`): Bearish Coral Red.
* `--color-sell-bg` (`rgba(244, 63, 94, 0.1)`): Soft red background tint.

### 5. Borders & Outlines
* `--border-low` (`rgba(255, 255, 255, 0.04)`): Ultra-light divider lines.
* `--border-med` (`#2a2a47`): Standard input and card border color.
* `--border-gold` (`rgba(200, 168, 75, 0.35)`): Highlighted active card borders.

---

## File Structure

* [variables.css](file:///c:/Users/iqooow/Desktop/calculator/variables.css): Holds all token declarations, imports premium typography (Outfit and JetBrains Mono for numerical data), and sets global resets.
* [index.html](file:///c:/Users/iqooow/Desktop/calculator/index.html): An interactive dashboard showing live color swatches and a functioning XAUUSD Position Calculator.
* [package.json](file:///c:/Users/iqooow/Desktop/calculator/package.json): Simple local build and dev server config using Vite.

---

## How to Run Locally

To launch the interactive prototype local server:

1. **Install dependencies**:
   ```bash
   powershell -ExecutionPolicy Bypass -Command "npm install"
   ```

2. **Start the local server**:
   ```bash
   powershell -ExecutionPolicy Bypass -Command "npm run dev"
   ```

3. Open the local address printed in the terminal (usually `http://localhost:5173`) in your browser to view and interact with the color system and live calculator.
# ir-trade
