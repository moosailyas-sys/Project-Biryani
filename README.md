# Project Biryani — Phase 2 (Version 1)

This repository holds the **locked v1 spec** and a lightweight scaffold to help external developers build the app.

## What this repo contains
- `/spec/Final_Build_v1.txt` — the authoritative build request (no design, structure-first).
- `/app/` — empty app folder for the client (web PWA or React Native).
- `/server/` — empty folder for sync mock / future backend.
- `.github/ISSUE_TEMPLATE/` — templates to file scoped tasks.

## For Developers (TL;DR)
- **Offline-first** app, button-only UI, evidence-gated flows (photo+voice), voids need video.
- **NCR stays red** until manager clears; tolerance is **20%**.
- **IDs/filenames are short**; offline stubs rename on sync.
- See `/spec/Final_Build_v1.txt` for the full acceptance criteria.

## Suggested stacks
- **Web PWA**: React + TypeScript + Dexie (IndexedDB) + Workbox (PWA).
- **Mobile**: React Native (Expo) + SQLite + background sync.

## Getting Started (non-coders)
1. Create a new repository on GitHub (public or private).
2. Upload the contents of this folder (drag-and-drop via GitHub web).
3. Open an Issue using the templates to hire/build specific parts.
4. Share repo link with your developer(s).
