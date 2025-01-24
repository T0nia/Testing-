# CineSeek - Movie Discovery Platform

CineSeek is a modern movie web app built with Next.js, TypeScript, and Tailwind CSS.

## App Features
- A responsive browsing interface
- Movie filter by release year/genre
- Advanced searching abilites
- Real-time movie data from MovieDatabase API
  
## Tech Stack
- Next.js 13+
- TypeScript
- Tailwind CSS
- FontAwesome Icons
- MovieDatabase API

# Project Structure
alx-movie-app/
├── components/
│   ├── commons/      # Reusable components
│   └── layouts/      # Layout components
├── interfaces/       # TypeScript interfaces
├── pages/           # Next.js pages
│   ├── api/         # API routes
│   └── movies/      # Movie-related pages
└── styles/          # Global styles

# API Documentation
## MovieDatabase API Overview
The MovieDatabase API provides access to movie information such as titles, release dates, and genres.

## Authentication
- API Key required in headers
- Rate limits apply based on plan
- Secure API key storage in environment variables
## Endpoints
- /titles/search: Search movies
- /titles/{id}: Get movie details
- /titles/series/{id}/episodes: Get series episodes.
## Error Handling
- 400: Bad Request
- 401: Unauthorized
- 404: Not Found
- 429: Rate Limit Exceeded
