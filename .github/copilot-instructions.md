# SkyRoute Project Reference

## Project Overview
SkyRoute is a web-based application that displays real-time and forecasted weather conditions along a road trip route between two locations. It integrates mapping, weather forecasting, and AI travel insights into a unified interface for travelers.

## Project Goals
- Display real-time weather conditions along a selected route.
- Forecast hourly weather based on estimated travel time.
- Provide interactive map visualization with weather icons.
- Generate AI-based travel insights (optional).
- Offer responsive design for both desktop and mobile users.

## Technology Stack
- **Frontend:** React 18, TypeScript, TailwindCSS
- **Backend:** Django 5, Django REST Framework
- **Database:** PostgreSQL
- **Caching:** Redis
- **Weather API:** OpenWeatherMap One Call 3.0
- **Map API:** Google Maps Directions / OpenRouteService
- **AI Layer:** OpenAI API (Optional)
- **Deployment:** Docker, AWS/Render

## System Architecture
1. User inputs source and destination in the React frontend.
2. Request sent to Django REST API backend.
3. Backend fetches route coordinates using Google Directions API.
4. For each route checkpoint, weather data is fetched via OpenWeatherMap API.
5. Django service aggregates route, estimated arrival times, and forecast data.
6. React frontend displays the route and weather summary visually on the map.

## Functional Requirements
- FR1: User inputs source and destination.
- FR2: System fetches and displays the optimal route.
- FR3: Fetch real-time and forecast weather data along the route.
- FR4: Provide AI-generated travel recommendations (optional).
- FR5: Display visual weather charts and conditions.

---
This file serves as a reference for project architecture, goals, and technology stack.