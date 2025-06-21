# Meloetta

**Meloetta** is a Python program for downloading Spotify playlists using [spotDL](https://github.com/spotDL/spotify-downloader). Unlike some alternatives, spotDL fetches songs directly from **YouTube Music**, ensuring higher consistency in audio quality by avoiding music video sources or poorly ripped audio.

## Features
- Download entire playlists from Spotify with ease.
- High-quality audio: downloads now default to **320kbps MP3** (as of June 21, 2025).
- Simple and fast setup — no need for custom Spotify Developer apps.

## Installation

1. Install [spotDL](https://pypi.org/project/spotdl/) via pip:

   ```bash
   pip install spotdl
   ```

2. Run Meloetta, paste your Spotify playlist link, and enjoy!

## Seasonal Theme: Pirouette Form

From **March 20th to June 21st**, Meloetta will display colors inspired by her *Pirouette Form* as a seasonal touch. 🍂

## Changelog

### 🆕 June 21, 2025
- Meloetta now downloads songs in **320kbps** by default.

### 🛠️ July 5, 2023
- Migrated from `spotify_dl` to `spotDL`, removing the need for `ffmpeg` and Spotify Developer setup.
- Major performance improvements for large playlists:
  - Previous version: ~15 hours for 655 songs.
  - Current version: ~55 minutes for the same playlist.
