# Course Mapper

A browser-based tool for mapping golf courses on satellite imagery. Exports JSON course files for **EzyGolfer Pro** (iOS) and **MatchPlayGolf** (Android).

Open `course-mapper.html` directly in any desktop browser — no server or installation required.

## What it does

- Satellite map (ArcGIS default; optional Google Maps Satellite with your own API key)
- For each hole, place tee box and green centre markers, set par and stroke index, optionally add hazards (bunker, water, OB, trees) and a driver landing marker
- Multi-tee support: add named tees (White, Blue, Red etc.) with Course Rating and Slope Rating
- Export the full course as a JSON file
- Import the JSON via **Settings → Import Course Mapper** in the app

## How to use

1. Open `course-mapper.html` in a desktop browser (Chrome or Safari recommended)
2. Navigate the map to your course — use zoom 17–18 for hole detail
3. Work through holes 1–18, placing TEE and GREEN markers, setting par and stroke index
4. Optionally add tees with Course/Slope Ratings via the Tees panel
5. Export → Download JSON File
6. In the app: **Settings → Import Course Mapper** and select the file

## Compatible apps

- **EzyGolfer Pro** (iOS) — Settings → Import Course Mapper
- **MatchPlayGolf** (Android) — Settings → Import Course Mapper
