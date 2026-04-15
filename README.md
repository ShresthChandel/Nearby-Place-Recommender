# Smart Nearby Places Recommender

A web application that recommends nearby places based on your current mood (Work, Date, Quick Bite, Budget). It automatically detects your location and provides personalized recommendations with details like distance, ratings, and open hours.

## Features

- **Geolocation**: Automatically detects user location on load.
- **Mood-Based Search**: Filters nearby places based on selected mood using Google Places API.
- **Split-Screen UI**: Interactive Map on the right and a detailed List View on the left.
- **Distance Calculation**: Real-time walking/driving distance from your location via Distance Matrix API.
- **Sorting Options**: Sort results by "Highest Rated" or "Closest Distance".
- **Responsive Design**: Works seamlessly on Mobile and Desktop devices.

## Tech Stack

- **Frontend**: React (Vite)
- **Styling**: Tailwind CSS
- **APIs**: Google Maps JavaScript API, Google Places API, Distance Matrix API
- **State Management**: React Context API / Hooks

## Getting Started

### Prerequisites

You will need a Google Cloud project with the following APIs enabled:
- Maps JavaScript API
- Places API
- Distance Matrix API

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file based on `.env.example` and add your Google Maps API key:
   ```env
   VITE_GOOGLE_MAPS_API_KEY=your_api_key_here
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```
