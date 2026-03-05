# Vortex Web (v10)

![Vortex Web Screenshot](https://raw.githubusercontent.com/Ren23447/Vortex-Web/refs/heads/main/Screenshot.png)

A cyberpunk-inspired, in-browser “mini browser” UI built with pure **HTML, CSS, and JavaScript**.

## Features
- Tabbed browsing + **drag & drop tab reordering**
- **Incognito tabs** (separate styling)
- Address bar with back/forward/refresh navigation
- **Bookmarks** manager + one-click bookmark current page
- Customizable **Quick Links** (add/remove, saved in localStorage)
- Sidebar panels: Bookmarks, Widgets, Gaming News, Settings
- Widgets: tab/bookmark stats, clock, simulated CPU/RAM monitor
- Settings: theme toggle, search engine selection, privacy toggles
- Proxy settings UI (direct / Ultraviolet / custom prefix)

## Tech
- Vanilla HTML/CSS/JS (no frameworks)
- State saved with **localStorage**
- Uses iframes for page loading (some sites may block iframing)

## Getting Started
1. Download/clone this repo
2. Open `index.html` in your browser

## Notes
- Gaming News loads via RSS-to-JSON (may fail if the API is down).
- Proxy options are UI-focused and may require a real backend for full support.

## Creator
Made by **Ren Hatsune**.
