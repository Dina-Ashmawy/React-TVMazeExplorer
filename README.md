# TVMaze Explorer React App

This project is a React application that allows users to browse TV shows, view their episodes and seasons, mark favorites, and more. It utilizes the TVmaze API for fetching show data.

## Features

- **Homepage:**
  - Displays a list of favorite TV shows.
  - Allows searching across the TVmaze database.
  - Paginates through a list of TV shows.
  
- **Selected Show Seasons Page:**
  - Lists all seasons of a selected TV show.
  
- **Selected Show Season Episodes Page:**
  - Lists episodes for a selected season of a TV show.

- **Favorites Management:**
  - Users can mark or unmark shows as favorites.
  - Favorite shows are remembered between sessions.

- **Responsive Design:**
  - Supports mobile displays with a minimum width of 320 pixels.

- **Additional Features:**
  - Time zone selector for displaying episode dates.
  - Last 5 search queries accessible in the search box.
  - Notifications for adding or removing favorites.
  - Eye-catching design.
  - Unit testing

## Tech Stack

- **Framework:** React 18 with TypeScript
- **State Management:** Redux Toolkit
- **Data Fetching:** RTK Query (Redux Toolkit Query)
- **Routing:** React Router DOM
- **Styling:** Styled Components
- **Testing:** Jest with React Testing Library
- **Build Tool:** Vite
- **Code Quality:** ESLint, Prettier


## Installation and Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Dina-Ashmawy/React-TVMazeExplorer.git
   cd React-TVMazeExplorer
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the development server:**
   ```bash
   npm start
   ```
   or
   ```bash
   npm run dev
   ```
   
   The app will be available at `http://localhost:5173` (or another port if 5173 is in use).

## Available Scripts

- `npm start` or `npm run dev` - Start the development server
- `npm run build` - Build the app for production
- `npm run preview` - Preview the production build locally
- `npm run lint` - Run ESLint to check code quality
- `npm run format` - Format code using Prettier
- `npm test` - Run unit tests with Jest


## Screenshots
I have included screenshots of the application to help you understand its functionality and appearance. You can find these screenshots in the following directory:

[app/screenshots](./screenshots)
