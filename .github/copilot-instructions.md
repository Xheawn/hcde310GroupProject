# Photo Window – Project Context

## Project Overview
Photo Window is a web application for UW students who want to discover photography spots around Seattle based on available time, photography preferences, and weather conditions.

## Tech Stack
- Backend: Python and Flask
- Frontend: HTML, CSS, JavaScript
- Interactive map: Leaflet
- Location data: Seattle Parks Viewpoints API (ArcGIS)
- Weather data: Open-Meteo API
- Data storage: Local JSON file for favorites

## Core Features
1. Users select available time, photography theme, and starting location.
2. The application recommends photography spots based on weather and proximity.
3. Users explore locations on an interactive Leaflet map.
4. Users save, view, and remove favorite locations.

## Development Guidelines
- Keep Flask routes and Python modules organized.
- Use real API data rather than invented location information.
- Handle loading, empty, and error states.
- Keep API keys and secrets out of the repository.
- Make forms and map information accessible.
- Use JSON for persistent favorites.

## Not Decided Yet
- Final recommendation scoring weights
- Additional photography themes
- Optional routing or travel-time API
