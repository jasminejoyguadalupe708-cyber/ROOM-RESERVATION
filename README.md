# Roomly — Room Reservation System

A responsive room-reservation demo built with plain HTML, CSS, and JavaScript.

## Features
- Browse four sample rooms with seat capacities and hourly rates.
- Filter rooms by type and reservation date.
- Make reservations with guest details, date, time, party size, and purpose.
- Prevent overlapping reservations for the same room and time.
- View and cancel reservations.
- Responsive layout for desktop and mobile.

## Run locally
Open `index.html` in a modern browser. No build tools or dependencies are required.

## Publish with GitHub Pages
1. Open the repository's **Settings**.
2. Select **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Choose branch `main` and folder `/ (root)`, then save.
5. Wait for GitHub Pages to publish the site; the Pages section will show its URL.

## Important demo limitation
This is a front-end prototype. Reservations are stored in the browser's local storage, so they are not shared across devices or users. It has no server-side database, login, or email notifications. For real multi-user bookings, connect a backend and database and validate availability server-side.
