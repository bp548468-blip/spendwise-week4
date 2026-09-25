# SpendWise - Week 4 Dashboard Shell

## What I Built
A personal finance dashboard called SpendWise. It shows spending overview for 6 categories: Food, Transport, Rent, Entertainment, Savings, and Utilities. This is Week 4 assignment focusing on layout using CSS Grid and Flexbox and theming.

Live Demo: https://bp548468-blip.github.io/SPENDWISE/

## Files in this Repo

### 1. index.html
- Main structure of the dashboard
- Contains:
    - Sidebar with logo and navigation (Dashboard, Transactions, Analytics, Budgets, Settings)
    - Header with title "Overview" and Add Expense button
    - 6 expense cards in a grid
- Each card shows category name, emoji icon, amount in KSh, transaction count, and progress bar
- Uses semantic HTML tags: `aside`, `nav`, `main`, `header`, `section`

### 2. style.css
- **Theming with CSS Variables (`:root`):**
    - `--brand: #0213AD` (main brand blue)
    - `--accent: #00D1A0` (green accent)
    - Used everywhere with `var(--brand)` so theme can change easily
- **Layout:**
    - `display: grid` on `.dashboard` -> creates 2 columns (sidebar 240px + main content 1fr)
    - `display: grid` on `.cards` -> responsive grid with `repeat(auto-fit, minmax(280px, 1fr))`
    - `display: flex` on `.sidebar` (column), `.header` (space-between), `.nav` (column), `.card-top` (space-between)
- **Styling:**
    - No absolute positioning used
    - Cards have border-radius, shadow, and progress bars
    - Inter font from Google Fonts
- Fully responsive and clean design

### 3. README.md
- This file - explains the project.

## How to Run
1. Clone repo
2. Open index.html in browser
3. Or view via GitHub Pages link

## Author
Beatrice - Week 4 Assignment - PLP / Power Learn Project
