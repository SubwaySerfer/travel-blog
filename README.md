# Travel Blog Project

A modern travel blog platform built with Vue.js and FastAPI, allowing users to share their travel experiences with location-based search and AI-powered features.

## Features

### Core Functionality
- Create and manage blog posts about travel experiences
- Location-based search with autocomplete for countries and cities
- Interactive image slider for travel photos
- Comments system
- Multi-language support (EN, RU, TH)

### Technical Features
- Rich text editor for post creation
- Real-time search with API integration
- Responsive design with Tailwind CSS
- Authentication system
- AI-powered content suggestions
- Caching system for external API responses

## Tech Stack

### Frontend
- Vue 3 (Composition API)
- TypeScript
- Tailwind CSS
- Pinia for state management
- Vue Router
- i18n for localization
- Vue Use utilities

### Backend
- FastAPI
- MongoDB
- Redis for caching
- Motor for MongoDB integration

### External Services
- RestCountries API
- Unsplash API
- HuggingFace API

## Project Structure

The project is split into two repositories:

### Frontend Repository
```
frontend/
├── src/
│   ├── components/    # Reusable UI components
│   ├── views/         # Page components
│   ├── stores/        # Pinia stores
│   ├── services/      # API integration
│   ├── composables/   # Shared logic
│   ├── types/         # TypeScript definitions
│   ├── utils/         # Helper functions
│   ├── locales/       # Translation files
│   └── assets/        # Static resources
```

### Backend Repository
```
backend/
├── app/
│   ├── api/          # API endpoints
│   ├── models/       # Data models
│   ├── services/     # Business logic
│   ├── core/         # Core functionality
│   └── utils/        # Utility functions
```

## Getting Started

### Prerequisites
- Node.js (v16+)
- Python (3.9+)
- MongoDB
- Redis

### Local Development Setup
1. Clone both repositories
2. Install dependencies for frontend and backend
3. Set up environment variables
4. Start development servers

## Deployment

### Frontend
- Deployed on Vercel/Netlify
- Automatic deployments from main branch

### Backend
- Deployed on Railway/Render
- MongoDB hosted on MongoDB Atlas
- Redis hosted on Redis Labs free tier

## Environment Variables

List of required environment variables for both frontend and backend (refer to .env.example in each repository)

## Contributing

Guidelines for contributing to the project

## License

MIT License

## Authors

Aleksander

## Acknowledgments

- External APIs and services used
- Design inspiration
- Open source libraries