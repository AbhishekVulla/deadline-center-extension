# deadline-center-extension
Chrome extension that unifies SUTD deadlines from eDimension and Gradescope

# Deadline Center – eDimension & Gradescope Companion

Chrome extension for SUTD students that pulls deadlines from **eDimension** and **Gradescope** into one clean dashboard, with calendar export.

![Main view](deadline-center-extension/main-view.png)

## Problem

Deadlines are scattered across eDimension, Gradescope and random chats. Students keep checking multiple pages and still miss things.

## What it does

- Scrapes deadlines from:
  - eDimension Calendar
  - Gradescope assignments
- Groups everything in one dashboard inside the browser
- Tags each item with the correct course (10.013, 10.015, 01.010, etc.)
- Filter by course and search by keyword
- Export selected deadlines to `.ics` and import into Google Calendar
- Add custom deadlines manually

All data stays local in the browser. No backend, no external server.

## Tech stack

- Chrome Extension, Manifest V3
- React + TypeScript
- Vite build
- Day.js for dates
- Chrome Storage API

## Installation For Users:

1. Extract the `dist/` folder
2. Open `chrome://extensions/` in Chrome
3. Enable "Developer mode"
4. Click "Load unpacked" 
5. Select the `dist/` folder
