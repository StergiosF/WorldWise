# 🌍 WorldWise

A web application that helps users keep track of the places they've visited. The app provides an interactive map to mark visited locations, view past trips, and explore more about cities and countries.

## Live Demo

Check out the live version here: https://worldwise-stergios.netlify.app

## About The Project

[![Homepage Preview](/public/app_preview.png)](https://worldwise-stergios.netlify.app)

WorldWise is a travel-tracking web application that allows users to log their journeys and view the places they visit on an interactive map. Users can explore detailed information about each city or country they’ve been to.

### Features

- **Interactive Map**: Powered by **Leaflet.js**, allowing users to mark visited locations.
- **Track Visited Places**: Save cities and countries you’ve traveled to.
- **Wikipedia Integration**: Get more details about each location.
- **React Routing**: Smooth navigation between different sections.
- **Fake Authentication**: Simulated login/logout for a personalized experience.
- **Context API**: Centralized state management for tracking user locations.
- **Optimized Performance**: Uses `useMemo` and `useCallback` for efficient rendering.
- **Lazy Loading**: Dynamically loads components to improve performance.

## Built With

This application is built using the following technologies:

- [React](https://reactjs.org/) – Frontend framework
- [React Router](https://reactrouter.com/) – Client-side navigation
- [React Context API](https://react.dev/reference/react/useContext) – State management
- [useMemo & useCallback](https://react.dev/reference/react/useMemo) – Performance optimization
- [React Lazy & Suspense](https://react.dev/reference/react/lazy) – Lazy loading for performance boost
- [Leaflet.js](https://leafletjs.com/) – Interactive maps
- [Netlify](https://www.netlify.com/) – Deployment

## Getting Started

Follow these steps to set up the project locally.

### 🔗 Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repo:

   ```bash
   git clone https://github.com/StergiosF/WorldWise
   ```

2. Navigate to the project directory:

   ```bash
   cd WorldWise
   ```

3. Install NPM packages:

   ```bash
   npm install
   ```

4. Start the quiz server:

   ```bash
   npm run server
   ```

5. Start the development server:

   ```bash
   npm run dev
   ```
