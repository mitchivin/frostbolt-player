# Frostbolt IPTV

A desktop IPTV player for Windows. Built for large Xtream playlists, a clean TV guide, and real control over EPG and backup streams.

Live / download at [frostbolt.xyz](https://frostbolt.xyz/).

**Public beta:** Xtream login only.

<p align="center">
  <img width="1920" height="1080" alt="frostBolt1" src="https://github.com/user-attachments/assets/8485ae6f-3489-4235-8737-c38373b50b1e" />
  &nbsp;
  <img width="1919" height="1079" alt="Screenshot 2026-07-11 174233" src="https://github.com/user-attachments/assets/9b8242e0-5f8e-43f7-b023-3fb113df2ba5" />
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

Public beta. Downloads at [frostbolt.xyz](https://frostbolt.xyz/).
