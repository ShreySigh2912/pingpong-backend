# Ping Pong Game Backend

Backend service for the Ping Pong game analytics dashboard.

## Setup Instructions

1. Install dependencies:
```bash
npm install
```

2. Create a .env file based on .env.example:
```bash
cp .env.example .env
```

3. Start MongoDB locally or update MONGODB_URI in .env

4. Start the server:
```bash
npm run dev
```

## API Endpoints

### Events
- POST /api/events - Record a game event
- GET /api/analytics/overview - Get overall analytics
- GET /api/analytics/daily - Get daily statistics

## Development

Run in development mode:
```bash
npm run dev
```

## Production

Start the server:
```bash
npm start
```