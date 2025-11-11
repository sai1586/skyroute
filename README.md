# SkyRoute

SkyRoute is a web-based application that displays real-time and forecasted weather conditions along a road trip route between two locations. It integrates mapping, weather forecasting, and AI travel insights into a unified interface for travelers.

## Features
- Real-time weather conditions along a selected route
- Hourly weather forecast based on travel time
- Interactive map visualization with weather icons
- AI-based travel insights (optional)
- Responsive design for desktop and mobile

## Tech Stack
- Frontend: React 18, TypeScript, TailwindCSS
- Backend: Django 5, Django REST Framework
- Database: PostgreSQL
- Caching: Redis
- Weather API: OpenWeatherMap One Call 3.0
- Map API: Google Maps Directions / OpenRouteService
- AI Layer: OpenAI API (Optional)
- Deployment: Docker, AWS/Render

## Getting Started
Project folders:
- `frontend/` - React app
- `backend/` - Django API
- `infrastructure/` - Docker, deployment, configs

## Functional Requirements
- User inputs source and destination
- System fetches and displays optimal route
- Fetch real-time and forecast weather data
- Provide AI-generated travel recommendations (optional)
- Display visual weather charts and conditions

---
See `.github/copilot-instructions.md` for architecture and reference.