# Catan Tracker (Colonist.io Extension)
A lightweight browser extension that tracks game stats in real time while you play on [Colonist.io](https://colonist.io/).
It supports both **1v1** and **4-player** games, with a draggable/collapsible tracker panel, resource and dev-card tracking, dice analytics, and game history.
## What It Does
- Tracks opponent/resource estimates and your own resource gains
- Tracks development cards played and deck progress
- Shows dice roll distribution with compact hover graph
- Tracks 7s per player (1v1 and 4p)
- Saves completed games into local history
- Lets you manually adjust values when logs are incomplete
- Supports optional confirmation prompts
- Persists panel position and collapsed state across reloads
## Highlights
- **1v1 + 4-player modes**
- **Collapsible tracker bar** with hover popups for dice/dev stats
- **Resource breakdown popups** (starting, rolled, stolen, trades, spent, discarded, total)
- **Percentage-based bars** for quick visual distribution
- **Win/loss tinting in history** for saved games
- **Rescan mode** for mid-game attach/recovery
## How It Works
The extension reads visible Colonist log events and updates a local tracker state in real time.  
Data is stored in `localStorage` for persistence between reloads.
> Note: Some events (especially hidden robber steals) are estimated when exact card details are not visible in the log.
## Installation (Local / Unpacked)
1. Clone or download this repo
2. Open Chrome/Edge and go to extensions page:
   - Chrome: `chrome://extensions`
   - Edge: `edge://extensions`
3. Enable **Developer mode**
4. Click **Load unpacked**
5. Select this project folder
6. Open Colonist.io and start a game
## Privacy
- No backend/server required
- No account or login data sent anywhere
- All tracker state is kept locally in your browser storage
## Status
Active personal project — built for practical in-game decision support, speed, and readability.
