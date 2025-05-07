# Consistency Tracker (Personal Project)

## Overview  
A personal productivity web application designed to track and reinforce daily work consistency. The app prompts users to log what they’ve done during defined work hours and visualizes progress using a GitHub-style heatmap. Built as a **PWA**, it runs seamlessly on both desktop and mobile devices with local-first data storage and offline access.

---

## Goals
- Build consistent work habits through gentle reminders
- Provide visual feedback via a streak/consistency heatmap
- Make it fast, minimal, private, and cross-platform

---

## Key Features
- **Working Hours Setup**: Define active hours and days
- **Daily Log Entry**: Quick, timestamped text entries
- **Heatmap Visualization**: Calendar-based progress view
- **Streak/Stats Tracker**: Longest streak, total days logged, etc.
- **Prompt System**: Browser-based local notifications during work hours
- **Offline Access & Installable**: Via PWA (Progressive Web App)

---

## Tech Stack
- **Frontend**: React + Vite
- **PWA Support**: `vite-plugin-pwa`
- **Storage**: `localStorage` or IndexedDB (`idb-keyval`)
- **Notifications**: Web Notification API
- **Visualization**: `react-calendar-heatmap`
- **Optional Packaging**: Tauri or Capacitor (for native builds)

---

## Architecture Overview
Frontend (React + Vite)
│
├── UI: Log Input, Heatmap, Stats, Settings
├── Local Storage (Persistence)
├── Notification Scheduler
└── PWA Service Worker for Offline Use

---

## Use Cases
- Logging daily accomplishments or focus sessions
- Visualizing work patterns or productivity consistency
- Tracking personal habit-building goals (e.g., writing, coding)

---

## Future Enhancements (Optional)
- AI-generated weekly summaries
- GitHub/Calendar integrations
- Tagging or categorizing entries
- Export logs to Markdown or CSV
- Desktop notification tray / background daemon
