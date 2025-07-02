# Research Insight Tracker

A simple web application for scoring research insights to determine their potential impact on product development.

## What it does

This tool helps you evaluate research findings by scoring them across three dimensions:
- **Jobs-to-be-Done (JTBD)**: How well the insight addresses user needs
- **Efficiency**: How much efficiency improvement it provides  
- **Delight**: What level of user satisfaction it creates

Each dimension is scored 0-5, and the total score determines the impact level:
- **High Impact** (12-15 points): Act on immediately
- **Moderate Impact** (8-11 points): Consider for future development
- **Low Impact** (4-7 points): Limited actionable value
- **No Impact** (0-3 points): May not warrant action

## How to use

1. Download or clone this repository
2. Open `index.html` in any web browser
3. Click "Score Foundational Insights"
4. Fill in your insight details and scores (0-5 for each dimension)
5. Click "Calculate Score" to see the results

## Files in this project

- `index.html` - The main page with the form and interface
- `script.js` - Handles the scoring logic and form validation
- `style.css` - Makes everything look nice
- `fonts/` - Custom fonts used in the design

## Making changes

This is a static website, so you can edit it with any text editor:

### To modify the scoring ranges:
Edit lines 152-164 in `script.js` where the impact levels are defined.

### To change the appearance:
Edit `style.css` to modify colors, fonts, or layout.

### To add new fields or sections:
1. Add HTML elements in `index.html`
2. Add corresponding JavaScript in `script.js` for any new functionality
3. Style new elements in `style.css`

## Requirements

- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No server or special software needed

---
## Code created by Carlos Alvarez

---

This is a standalone tool - no database, no installation, just open and use!
