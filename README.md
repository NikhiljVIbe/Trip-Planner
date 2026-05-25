# Malaysia Trip Planner 🌴

An interactive family trip planner for **Bangalore / Mumbai → Kuala Lumpur → Langkawi**, built as a single-file static web app. Designed for families with toddlers — every hotel, flight, and itinerary item is filtered through one question: *will the little ones enjoy it too?*

## ✨ Features

- **Two departure cities** — Bangalore (BLR) or Mumbai (BOM), with hand-picked flights ranked by kid-friendliness
- **37 hotels** across KL (20) and Langkawi (17), filterable by Accor / Non-Accor and neighborhood
- **Distance + Indian guest ratings + vegetarian food** options listed for every hotel (Indian, Pizza, Italian, Thai, Japanese, Mediterranean)
- **3 plan styles per city** — Relaxed family, Active explorer, Indoor/AC heavy for KL; Beach + chill, Adventure, Culture for Langkawi
- **Visual saved itineraries** with animated flight arc, dot-connected day timeline, and activity photos
- **Booking links** to MakeMyTrip, Goibibo, Yatra, Booking.com, Agoda, Cleartrip, Skyscanner, Klook, GetYourGuide, Viator + brand-direct (Accor / Marriott / Hilton / IHG / Hyatt / Shangri-La)
- **Save unlimited plans** to localStorage with thumbnail previews on the saved cards
- **Fully responsive**, single HTML file — no build step

## 🚀 Run locally

```bash
python3 -m http.server 8080
```

Then open [http://localhost:8080](http://localhost:8080).

That's it — no dependencies, no node_modules, no build.

## 📁 Structure

```
trip-planner/
├── index.html      # entire app (HTML + inline CSS + inline JS)
├── README.md
└── .gitignore
```

## 🧪 Tech notes

- **Vanilla JS** — no framework
- **localStorage** for saved itineraries
- **Fraunces** serif + **Plus Jakarta Sans** body
- Photos use Unsplash with Picsum fallback
- Booking links use Google site-search redirects for aggregator reliability
