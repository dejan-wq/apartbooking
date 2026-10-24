# Apartment bookings 2026

Year-view booking calendar for an apartment. Static site: no build step.

## Deploy
1. Push these files to a GitHub repo.
2. In Vercel: Add New > Project > import the repo > Deploy (no settings needed).
3. Open the Vercel URL in Chrome on your phone > menu > Install app.

## Notes
- Bookings are saved in the browser (localStorage) on each device. They are not synced between devices.
- To use the same data on another device, add a backend (e.g. Supabase) in `persist`, `remove` and `connect` in index.html.
- To change the year, edit `const YEAR=2026;` in index.html.
