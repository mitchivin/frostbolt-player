# Frostbolt IPTV

A desktop IPTV player for Windows. Built for large Xtream playlists, a clean TV guide, and real control over EPG and backup streams.

Live / download at [frostbolt.xyz](https://frostbolt.xyz/).

**Public beta:** Xtream login only.

<p align="center">
  <img src="https://github.com/user-attachments/assets/73a7acc2-5b66-482e-85f8-d22817645c57" alt="Frostbolt IPTV main guide with EPG grid and video player" width="480" />
  &nbsp;
  <img src="https://github.com/user-attachments/assets/d946c022-9cb0-4836-b9ff-69b91fa5912d" alt="Frostbolt IPTV desktop player interface" width="480" />
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
- Windows installer and portable builds

## Credits

Built by **[Mitch Ivin](https://mitchivin.com/)**.

## Disclaimer

Frostbolt is a media player. It does not host, provide, or resell channels or playlists. You bring your own legitimate provider credentials. Frostbolt does not endorse unauthorized use of copyrighted content.

## License

Public beta. Downloads at [frostbolt.xyz](https://frostbolt.xyz/).
