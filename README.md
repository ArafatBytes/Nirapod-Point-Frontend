# Nirapod Point Frontend

A React-based crime mapping and analysis application for Bangladesh.

## Features

- Interactive crime map with real-time data
- Crime reporting system
- Risk analysis and statistics
- Safe route planning
- User authentication and management
- Admin dashboard

## Tech Stack

- React 18
- Vite
- Tailwind CSS
- Chakra UI
- React Router DOM
- Leaflet (for maps)
- Framer Motion (for animations)

## Development

1. Install dependencies:

   ```bash
   npm install
   ```

2. Start development server:

   ```bash
   npm run dev
   ```

3. Build for production:
   ```bash
   npm run build
   ```

## Deployment

This project is configured for deployment on Vercel. The API calls have been updated to work with the production backend at `https://nirapod-point-backend.onrender.com`.

### Environment Variables (Optional)

If you need to change the API URL, you can set the `VITE_API_URL` environment variable in your Vercel dashboard.

## API Configuration

The application connects to the backend API at `https://nirapod-point-backend.onrender.com`. All API calls use the full URL to ensure compatibility with production deployment.
