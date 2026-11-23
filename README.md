# React Movie Labs 2025

Weekly labs for Web App Development 2, building a movies app step by step with React and the TMDB API.

## What the labs build

- **Home page** listing movies from TMDB, with a title and genre filter.
- **Movie details** page with reviews.
- **Upcoming movies** page.
- **Favourites**, stored in a React context.
- **Write a review** form for favourite movies.
- **Caching** of API calls with TanStack Query, plus template components shared by the list and detail pages.

## Running it

1. Get a free API key from [TMDB](https://www.themoviedb.org/settings/api).
2. Create `movies/.env` with:

   ```
   VITE_TMDB_KEY=your_key_here
   ```

3. Run:

   ```bash
   cd movies
   npm install
   npm run dev
   ```

## Tools

JavaScript · React · Vite · React Router · Material UI · TanStack Query · TMDB API
