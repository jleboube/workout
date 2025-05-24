# workout


# Project Structure
```
workout/
├── docker-compose.yml
├── Dockerfile
├── nginx.conf
├── www/
│   ├── index.html
│   ├── manifest.json
│   └── sw.js
└── README.md
```



# Baseball Workout Calendar

Workout Schedule for a Father and his Son

A containerized workout tracking application for baseball training.

## Quick Start

1. Clone this repository
2. Run: `docker compose up -d`
3. Visit: http://localhost:8080
4. Start tracking your workouts!

## Features

- ⚾ Baseball-specific workout plans
- 📊 Weekly progress tracking
- 📱 Mobile-optimized PWA
- 🔧 Admin panel for customization
- 📈 Historical progress view
- 🐳 Docker containerized

## Commands

- `docker compose up -d` - Start the application
- `docker compose down` - Stop the application
- `docker compose logs -f` - View logs
- `docker compose restart` - Restart the application

## Accessing Your App

- Local: http://localhost:8080
- Network: http://YOUR_IP:8080
- Mobile: Add to home screen for app-like experience

## Data Storage

All workout data is stored locally in your browser's IndexedDB. Use the export feature in the admin panel to backup your data.

