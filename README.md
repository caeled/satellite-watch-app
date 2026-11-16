# Satellite Watch — desktop app

The Satellite Watch room from Steven Powell's **Everyday Cool** collection as its own
installable app for Windows and macOS. Pick a satellite family — space stations,
Starlink, GPS, weather, Hubble, amateur radio, Iridium and more — watch them move on a
live world map with ground tracks, and see the next passes over your spot. Fresh orbit
data from CelesTrak with a bundled snapshot so it still works offline.

- The room on the web: https://caeled.github.io/everyday-cool/projects/satellite-watch/
- The collection: https://caeled.github.io/everyday-cool/

## Downloads

Grab the installer for your system from the
[latest release](https://github.com/caeled/satellite-watch-app/releases/latest):

- **Windows:** `Satellite.Watch_<version>_x64-setup.exe`
- **macOS (Intel + Apple Silicon):** `Satellite.Watch_<version>_universal.dmg`

The installers are unsigned hobby builds: Windows SmartScreen and macOS Gatekeeper
will warn on first run; choose "More info → Run anyway" (Windows) or right-click →
Open (macOS).

## Build

Tauri v2 shell around the room's own web files in `dist/`. Tagging `v*` builds and
publishes the release via GitHub Actions.

Idea by Steven Powell. Built with the Council: Grok Bot built the room, Muse made
the banner and packaged the app.
