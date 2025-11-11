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

### Project Folders
- `frontend/` — React app (TypeScript, TailwindCSS)
- `backend/` — Django API (Django REST Framework)
- `infrastructure/` — Docker, deployment, configs

### Running Locally with Docker
1. Make sure you have Docker and Docker Compose installed.
2. In the project root, run:
	```bash
	cd infrastructure
	docker-compose up --build
	```
3. Backend (Django) will be available at http://localhost:8000
4. Frontend (React) will be available at http://localhost:3000

### Troubleshooting React Setup
If you see errors about conflicting files (e.g., Dockerfile, .dockerignore) when running `npx create-react-app`, temporarily move those files out of the `frontend` folder, run the command, then move them back.

### Functional Requirements
- User inputs source and destination
- System fetches and displays optimal route
- Fetch real-time and forecast weather data
- Provide AI-generated travel recommendations (optional)
- Display visual weather charts and conditions

---
See `.github/copilot-instructions.md` for architecture and reference.