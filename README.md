# ALION Radio Player: updates

This repo is the update feed for **ALION Radio Player** (Windows). The app's **Check for updates** button
(bottom of the left sidebar) reads `latest.json` here and installs new versions by itself, so you only
install the player manually once.

- `latest.json`: the current version, its notes and the SHA-256 of the update file.
- `releases/<version>/app-<version>.json`: the update, checked against its SHA-256 before it's installed.

Current version: **1.3.0**: glass redesign, a Global tab with 50 world stations, seasonal backgrounds with light live animation
(auto by date: Halloween, Thanksgiving, Christmas, New Year's), and your own custom backgrounds.

Previous: 1.2.0 (Song ID's Spotify button opens the Spotify app, a ⟳ Reload button, and in-app updates).
