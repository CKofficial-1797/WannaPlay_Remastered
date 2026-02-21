# GameHub

A modern video game discovery and browsing application built with React and TypeScript.

## Overview

GameHub is a responsive web application that allows users to browse, search, and discover video games. It features detailed game information, media galleries, platform filtering, and genre-based navigation powered by the RAWG Video Games Database API.

## Features

- **Game Discovery** - Browse thousands of games with infinite scroll
- **Advanced Filtering** - Filter games by genre and gaming platform
- **Search Functionality** - Real-time search across game titles
- **Sorting Options** - Sort results by relevance, rating, or release date
- **Game Details** - View comprehensive game information including screenshots and trailers
- **Dark Mode** - Toggle between light and dark themes
- **Responsive Design** - Optimized for desktop and mobile devices
- **Performance** - Skeleton loading states and efficient data fetching

## Tech Stack

- **Frontend Framework** - React 18 with TypeScript
- **UI Library** - Chakra UI for accessible components
- **State Management** - Zustand for global state
- **Data Fetching** - Axios + React Query
- **Routing** - React Router v6
- **Build Tool** - Vite
- **Icons** - React Icons

## Getting Started

### Prerequisites

- Node.js 16+ and npm

### Installation

1. Clone this repository
   ```bash
   git clone https://github.com/CKofficial-1797/WannaPlay_Remastered.git
   cd WannaPlay_Remastered
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Get a RAWG API key
   - Visit [RAWG API Documentation](https://rawg.io/apidocs)
   - Create an account and generate an API key
   - Add it to `src/services/api-client.ts`

4. Start the development server
   ```bash
   npm run dev
   ```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build

## Project Structure

```
src/
├── components/     # Reusable UI components
├── pages/          # Page components
├── hooks/          # Custom React hooks
├── services/       # API clients and utilities
├── entities/       # TypeScript type definitions
├── data/           # Static data constants
├── store.ts        # Global state management
├── theme.ts        # Chakra UI theme configuration
└── routes.tsx      # Application routing
```

## License

This project is provided as-is for educational purposes.
