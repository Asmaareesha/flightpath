# FlightPath: Flight Planning Simulator

A flight planning simulator that runs entirely in your browser. Choose departure, destination, optional alternate and via waypoints, aircraft and conditions. It returns route, distance, time, a full fuel breakdown, weight and range checks, a navigation log and an animated map.

**Simulation only. Never use it for real navigation or dispatch.**

## Features
- 100+ airports (ICAO or IATA codes) and 9 aircraft, from the ATR 72 to the A380
- Coastline map with graticule, great-circle route, "Fly it" playback and vertical profile
- Waypoint editor: add via points by airport code or `lat/lon`, or click the map
- Wind per leg, temperature deviation, routing inefficiency
- Fuel: taxi, trip, contingency, alternate, final reserve, extra, in kg, lb and litres, plus CO2
- Go / Caution / No go checks, shareable links, copy briefing, export JSON, print, light and dark mode

## Use
Open `index.html` in a browser. Everything is inside that one file. To publish it, use GitHub Pages (Settings, Pages, deploy from branch `main`, folder `/ (root)`).

Aircraft figures are rounded approximations of public data. Coastlines are simplified and not survey accurate.

MIT licensed. Made by Asma Areesha Hanifi.
