# Tuungane

Location-based matchmaking demo for people in Kenya. Static site for Netlify.

Live demo stores profiles, likes, matches, and chats in the browser (localStorage). Geolocation is requested in the browser; if denied, Nairobi CBD is used as the fallback point.

## Run locally

Open `index.html` in a browser, or:

```bash
python3 -m http.server 8080
```

## Deploy

Connect this repo to Netlify. Publish directory is `.` (no build step).
