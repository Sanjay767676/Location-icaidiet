# ICAIDIET'26 - Campus Venue Navigator

Interactive, live GPS navigation web application for attendees of **ICAIDIET'26** (*International Conference on AI-Driven Innovation in Engineering and Technology*) at **SNS College of Technology - AI Campus**.

## Features

- **No Hall Selection Required:** Directly guides attendees through all sequential campus checkpoints from the Main Entrance to the AI Campus.
- **MapLibre GL JS Engine:** 100% free, high-performance vector/raster map powered by OpenStreetMap tiles (zero API keys required, zero watermarks).
- **Conference Typography & Color Palette:** Matches the official conference branding with solid cream-yellow theme (`#fdf08a`) and `Libre Baskerville` serif typography.
- **On-Device GPS Guidance:** Real-time distance and proximity detection to each campus waypoint.
- **Mobile First & Responsive:** Clean mobile viewport with full support for desktop browsers without horizontal overflow.

## Tech Stack

- **React 18** + **TypeScript**
- **Vite**
- **MapLibre GL JS**
- **Lucide React** Icons

## Local Development

```bash
# Install dependencies
npm install

# Start local development server
npm run dev

# Build for production
npm run build
```

## Deployment

Configured for immediate deployment on Vercel with single-page app rewrite rules in `vercel.json`.
Hosted at: `location.icaidiet26.tech`
