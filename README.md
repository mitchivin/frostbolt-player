# Frostbolt IPTV

A desktop IPTV player for Windows. Built for large Xtream playlists, a clean TV guide, and real control over EPG and backup streams.

Live / download at [frostbolt.xyz](https://frostbolt.xyz/).

**Public beta:** Xtream login only.

<p align="center">
<img width="1536" height="864" alt="main-guide" src="https://github.com/user-attachments/assets/e524e40a-f458-4f9f-b785-e03dfe77618f" alt="Frostbolt Main Guide" />
</p>

## Features

- Main Guide with a full EPG grid, plus Marathons (24/7) and Live Events views
- Smart channel merging: SD / HD / backup lines under one row, with source switching
- Automatic failover when a live feed stalls or drops
- EPG time offsets globally, per provider, or per channel
- Guide opens once the first visible channels are ready; the rest loads in the background
- Channel scanner to probe stream health across your list
- Setup wizard built for large playlists (thousands of channels)
- Library blueprints to save / restore merges, names, and EPG links without exporting passwords
- Bulk edit for favourites and custom lists
- Frostbolt (blue) and Regrowth (green) themes
- HLS playback with VLC fallback when Chromium cannot decode the stream

<p align="center">
<img width="1536" height="864" alt="on-screen-display" src="https://github.com/user-attachments/assets/37ce0997-d969-4a7f-8533-d21ab6120df3" alt="Frostbolt Full Screen OSD" />
</p>

## Stack

- Electron, React, TypeScript, Vite
- hls.js / mpegts.js for in-app playback
- Local VLC transcode path for unsupported codecs
- Windows installer

## Credits

Built by **[Mitch Ivin](https://mitchivin.com/)**.

## Disclaimer

Frostbolt is a media player. It does not host, provide, or resell channels or playlists. You bring your own legitimate provider credentials. Frostbolt does not endorse unauthorized use of copyrighted content.

## License

Public Preview. Downloads at [frostbolt.xyz](https://frostbolt.xyz/).
