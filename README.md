# TutorTots Popup Interface

## Overview
This project implements a simple **popup UI for TutorTots**, built with HTML and styled using the **Bulma CSS framework**. The interface allows users to start or stop the TutorTots service via clearly labeled buttons.

---

## Features
- Clean, responsive layout using Bulma
- Start and Stop buttons for user interaction
- Minimal and accessible design
- Designed for use as a browser extension popup or lightweight web interface

---

## UI Components
- **Title:** TutorTots  
- **Prompt:** Asks the user whether they want to activate TutorTots  
- **Start Button:** Triggers activation logic (handled in `popup.js`)  
- **Stop Button:** Triggers deactivation logic (handled in `popup.js`)  

---

## Usage
1. Open `popup.html` in a browser **or**
2. Use it as the popup page for a browser extension
3. Implement Start/Stop behavior inside `popup.js`

---

## Dependencies
- **Bulma CSS** (local `bulma.min.css` file)

---

## Notes
- All interactive behavior is handled in `popup.js`
- This file focuses only on structure and styling
- Additional accessibility features (ARIA labels, keyboard handling) can be added if needed

---

## Purpose
This UI was created as a lightweight control panel for activating and deactivating TutorTots in a simple and user-friendly way.

