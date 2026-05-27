# Lift — Training Tracker

A web-based strength training tracker for building, importing, and logging structured workout programs.

Lift allows users to either create a training plan directly in the app or upload a coach-designed Excel spreadsheet, then track every exercise, set, load, rep, and note through an interactive training interface.

## Live Demo

View the deployed version here: gym-training-plan.netlify.app

## Project Overview

Lift was designed as a lightweight, browser-based training system focused on simplicity, usability, and structured progression tracking.

The application supports two primary workflows:

1. **Program Builder**
   - Create training phases
   - Add training days
   - Configure exercises, sets, reps, RPE, and rest periods
   - Build complete multi-week training blocks directly in the app

2. **Excel Import**
   - Upload structured `.xlsx` training templates
   - Parse coach-created spreadsheets automatically
   - Convert spreadsheet data into interactive workout sessions

Once a program is loaded, users can:
- Track actual loads and reps
- Log notes for each set
- Mark exercises complete
- Navigate across phases, weeks, and training days
- View training dashboards and progression metrics

All data is processed and stored locally in the browser.

## Why This Project Exists

Many training apps are either:
- overly complex,
- focused on social/community features,
- or locked behind subscriptions and rigid templates.

Lift explores a more flexible workflow:
- coach-compatible,
- spreadsheet-friendly,
- minimalist,
- and highly customizable.

The goal was to create a clean training interface that combines:
- structured program design,
- detailed session logging,
- and lightweight analytics,
without requiring a backend-heavy infrastructure.

## Core Features

### Program Builder
- Create multi-phase programs
- Define custom week counts
- Add unlimited training days
- Configure exercises with:
  - sets
  - reps
  - RPE
  - rest periods
  - coaching notes

### Excel Upload System
- Import `.xlsx` workout plans
- Supports:
  - Lift template format
  - coach spreadsheet formats
- Automatic parsing and workout generation

### Training Session Tracking
- Week-by-week workout navigation
- Per-set load and rep logging
- Exercise completion tracking
- Session progress indicators
- Warm-up tracking
- Coach notes display

### Dashboard & Analytics
- Workout progress visualization
- Training volume tracking
- Exercise performance monitoring
- Historical progression charts

### Authentication & Sync
- Supabase-based authentication support
- Local browser persistence
- Session saving and recovery

## Tech Stack

- HTML
- CSS
- JavaScript
- Chart.js for workout analytics and visualizations
- SheetJS / XLSX for spreadsheet parsing and export
- Supabase for authentication and cloud sync support
- Netlify for deployment and hosting

## File Structure

```text
lift-training-tracker/
├── index.html
└── README.md
