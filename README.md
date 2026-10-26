# Car-Go Dealership Inc.

Website for Car-Go Dealership Inc., 257 Centennial Pkwy N, Hamilton ON.

## Files
- `index.html`: the website
- `cars.json`: your cars for sale (see `cars.example.json`)
- `reviews.json`: customer reviews you want to show
- `images/`: car photos
- `carfax/`: CARFAX PDFs
- `logo.jpg`: logo

## Add a car
1. Upload the photo to `images/` and the CARFAX PDF to `carfax/` (Add file → Upload files).
2. Open `cars.json`, click the pencil icon, and add an entry like the one in `cars.example.json`. Separate cars with commas.
3. Click Commit changes. The site updates in about a minute.

Customers can click a car to see all its details. Every line except year, make, model and price is optional: trim, body, km, color, transmission, fuel, drivetrain, vin, desc, features, photos (several photos), carfax.

Remove a car by deleting its entry. Mark it sold with `"sold": true`.

## Add a review
Add `{"name": "Sam", "rating": 5, "text": "Great experience!", "date": "2026-10-20"}` to `reviews.json`.

## Publish
Settings → Pages → Deploy from a branch → `main` / root → Save.
