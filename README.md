# WatchWhileEating 🍿

A front-end for browsing YouTube videos from the Lemmy community [!mealtimevideos@lemmy.cafe](https://lemmy.cafe/c/mealtimevideos).

Built because digging through forum threads while eating wasn't cutting it — wanted something that felt like browsing rather than scrolling.

## Features

- Browse video grid with sort (Hot, New, Top, Rising) and search
- Watch view with YouTube embed, comments, and related videos
- Material You theming (Pink & Blue, Light & Dark)
- Fully responsive — works on desktop and mobile
- Single HTML file — no build step, no framework

## Usage

Open the [live site](https://aksangi77.github.io/watchwhileeating/), or serve `index.html` locally:

```bash
python3 -m http.server 8080
```

## Data Source

All content comes from the [Lemmy API](https://lemmy.cafe/api/v3) — specifically the `!mealtimevideos` community. No cookies or third-party scripts (except the YouTube IFrame Player API for video playback).

## Analytics

This site uses [GoatCounter](https://www.goatcounter.com) — a lightweight, open-source, privacy-friendly analytics service. No cookies, no personal data collected, just aggregate page view counts. The dashboard is private.

## License

MIT
