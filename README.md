# Notion Music Widget

Minimal widget for Notion that plays one background track:
`https://www.youtube.com/watch?v=JCKBaJDRMw4`

Widget file: `notion-music-widget.html`

## Features

- Autoplay (usually muted because of browser autoplay policy)
- Infinite loop for one track
- Play/Pause and Mute/Unmute buttons

## How to use in Notion

1. Publish `notion-music-widget.html` on any static host (GitHub Pages, Netlify, Vercel, etc).
2. Copy the public page URL.
3. Paste this URL in Notion using `/embed`.

## Local preview

```powershell
python -m http.server 8080
```

Open:
`http://localhost:8080/notion-music-widget.html`
