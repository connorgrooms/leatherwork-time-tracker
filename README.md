# Leatherwork Time Tracker

A small, single-page web app to track how long different parts of a leatherworking project take.  

Designed to be run in a browser on an iPad in landscape mode.

## Features

- **Project-based tracking**
  - Create projects (e.g. “This wallet test run 1”).
  - Projects are listed in the left sidebar, ordered by **most recently created**.
  - Rename the current project from the header.

- **Task-specific timers per project**
  - Pricking / Stitching  
  - Cutting  
  - Skiving  
  - Edge finishing  
  - Glueing / Assembly  
  - Other  
  - Only **one timer can run at a time**; starting one automatically pauses the others.
  - Timers show `HH:MM:SS` and continue correctly even if the page is closed or the device sleeps.

- **Total time per project**
  - The header shows the **total elapsed time** across all task timers for the active project.

- **Local, offline-first storage**
  - All data is stored in `localStorage` under `leatherwork_time_tracker_v1`.
  - No backend, accounts, or network calls.

## Tech stack

- Static HTML + CSS
- Vanilla JavaScript
- Browser `localStorage` for persistence
   