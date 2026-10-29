# ShowTime — Online Movie Ticket Booking Prototype

A responsive frontend prototype based on the original Online Ticket Booking project. It is built with HTML, CSS, and vanilla JavaScript, so no installation or backend is required to demonstrate the main user flow.

## Run the project
1. Extract the ZIP file.
2. Open `Online_Ticket_Booking-main`.
3. Double-click `index.html`, or open the folder in VS Code and use Live Server.

## Features
- Responsive movie discovery page with a dark, modern interface.
- Search movies by title or genre and filter by genre.
- All Movies, Trending, and Top Rated tabs.
- City selector and events section.
- Seat selection with available, occupied, and selected states.
- Date and show-time selection.
- Automatic ticket count and total price calculation.
- Demo booking confirmation with a booking ID.
- My Bookings view; demo bookings persist in browser `localStorage`.
- Uses sample movie/event data. No real payment or server-side booking occurs.

## Files
- `index.html` — page structure and booking dialogs.
- `styles1.css` — responsive design and component styling.
- `app.js` — sample data, filtering, seat selection, price calculation, and local demo booking storage.
- `Book.html`, `ticket.html`, `styles2.css` — original project files retained for reference.

## College demonstration note
This is a frontend-only prototype. Movie data, occupied seats, and bookings are demo data stored in the browser. A real deployment would need an API, database, user authentication, and a payment provider.
