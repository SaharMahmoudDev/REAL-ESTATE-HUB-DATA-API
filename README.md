# Real Estate Hub Data API

Mock property listings API (JSON) used by [Real Estate Hub](https://github.com/SaharMahmoudDev/REAL-ESTATE-HUB-TEAM), a team-built real estate listings app.

## What it contains

- `properties`: listings for sale or rent, each with title, type, status, price, currency, address, city, area, bedrooms, bathrooms, amenities, images, coordinates and listing date
- `agents`: agent records

The data lives in `db.json` and is served by [json-server](https://github.com/typicode/json-server) (version 0.17.4).

## Run locally

```bash
npm install
npx json-server --watch db.json --port 3001
```

Then open http://localhost:3001/properties.

## Related

- App: https://github.com/SaharMahmoudDev/REAL-ESTATE-HUB-TEAM
- Live demo: https://realestatehubteam.pages.dev/
