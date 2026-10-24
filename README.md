# Room Reservation & Room Observation

This repository includes two standalone browser-based prototypes:

- **Room Reservation:** `index.html` — browse rooms, make bookings, and manage reservations.
- **Room Observation:** `room-observation.html` — record room inspections and conditions, filter observations, track follow-up status, and export records to CSV.

## Run locally
Download or clone the repository and open either HTML file in a modern browser. No build tools or dependencies are required.

## Publish with GitHub Pages
1. Open the repository **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/ (root)`, then save.
4. After publishing, the reservation page is at the site root and the observation page is available at `/room-observation.html`.

## Demo limitations
Both pages store data in the browser's local storage. Records are not shared across users or devices, and browser storage is not a substitute for a backup or secure database. For a real multi-user system, add a backend/database, access controls, and server-side validation.
