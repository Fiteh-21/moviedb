# Netflix Clone UI

A modern React-based Netflix-style streaming landing page built with Vite. This project demonstrates a polished UI experience with dynamic TMDB-powered content, responsive navigation, interactive banner controls, and category carousels.

## Key Features

- **React + Vite** application with fast development and optimized bundling.
- **TMDB integration** using Axios to fetch trending titles, Netflix originals, top rated movies, and genre collections.
- **Dynamic banner** with randomly selected Netflix original content and streamlined detail actions.
- **Carousel slider** for movie rows using `swiper`.
- **Interactive header** with search toggle, notifications indicator, and profile dropdown.
- **Clean component structure** with reusable Banner, Header, DisplayRow, SlideShow, and MovieCard components.

## Tech Stack

- React 19
- Vite
- Axios
- Swiper
- React Router DOM
- Lucide React icons
- ESLint

## Project Structure

- `src/App.jsx` — application shell and page layout
- `src/Components` — reusable UI components
- `src/Utility/MovieInstance.js` — Axios instance for TMDB API requests
- `src/Utility/requestUrls.js` — TMDB endpoints and API key configuration
- `src/Data/Data.js` — static movie metadata and sample content

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Fiteh-21/moviedb.git
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the project root and add your TMDB API key:
   ```env
   VITE_TMDB_API_KEY=your_tmdb_api_key_here
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open the local URL shown in the terminal to view the application.

## Available Scripts

- `npm run dev` — start the Vite development server
- `npm run build` — build the production bundle
- `npm run preview` — locally preview the production build
- `npm run lint` — run ESLint across the project

## Notes

- The app uses The Movie Database (TMDB) API. You must provide a valid API key in `VITE_TMDB_API_KEY`.
- The UI is designed to mimic a streaming service landing page and can be extended to support routing, authentication, and custom content filtering.

## Future Improvements

- Add full routing for `TV Shows`, `Movies`, and `My List` pages
- Implement persistent search with filtering and live results
- Add user authentication and profile management
- Improve mobile responsiveness and accessibility

## License

This repository is provided as a demo project and can be adapted for educational or portfolio use.
