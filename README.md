# Week 7: JavaScript Best Practices

## Author
- **Name:**chesemchanel
- **GitHub:** [@chesemchanel](https://github.com/chesemchanel)
- **Date:** April 21, 2026

## Project Description
A single-page JavaScript application demonstrating professional coding practices, browser storage APIs, and clean code architecture. Built as part of IYF Weekend Academy Season 10, Week 7.

## Technologies Used
- HTML5
- CSS3 (custom properties, animations, responsive layout)
- Vanilla JavaScript (ES6+ modules pattern, IIFE, const/let)
- Web Storage API (localStorage + sessionStorage)

## Features Implemented

### Task 13.2 — To-Do List with localStorage
- Todos persist across page refreshes
- Completed state is saved
- Delete removes from storage
- Filter preference (All / Active / Completed) is saved
- Works correctly when storage is empty

### Task 13.3 — sessionStorage Form
- Auto-saves all fields every 5 seconds
- Recovers data on page refresh
- Clears saved data on submit

### Daily Challenges
- ✅ Day 1: Theme Persistence — light/dark toggle saved to localStorage
- ✅ Day 2: Recent Searches — last 5 searches saved, dropdown history, click to re-search
- ✅ Day 3: Form Auto-Save — sessionStorage auto-save every 5s with indicator

## Code Quality Practices Applied
- Meaningful variable/function names
- No magic numbers/strings (constants used)
- Functions do one thing (single responsibility)
- No deeply nested code (max 2-3 levels)
- Uses `const`/`let` — no `var`
- Proper error handling (try/catch on JSON.parse)
- No unused variables
- Strict equality (`===`) throughout
- Efficient DOM queries (cached references)
- No memory leaks (event delegation used)
- Error handling on all storage operations
- Consistent formatting and meaningful comments
- Code organized into logical IIFE modules

## How to Run
Open `index.html` in any modern browser. No build step required.

## Live Demo
[View Live Demo](https://github.com/chesemchanel/iyf-s10-week-07-chesemchanel)
