# Tokyo Hub — Family Itinerary

Day-by-day itinerary site for the Cultural Compass Adventures Tokyo Hub (October 20–26, 2026). Built for worldschooling families to check meeting times, meeting points, activities, pricing, and maps for each day of the hub.

## Structure

Single static page — `index.html` — no build step required.

- Day tabs switch between the 7 days of the hub
- Each day has a Leaflet/OpenStreetMap map of that day's key locations (falls back to a plain message if the map CDN is unreachable)
- Pricing, hours, and logistics notes are marked as either ✅ confirmed or ⚠️ flagged for a manual double-check before publishing

## Local preview

Just open `index.html` in a browser — no server needed.

## Deploy

This is a static site — deploys as-is on Vercel, Netlify, GitHub Pages, or any static host.
