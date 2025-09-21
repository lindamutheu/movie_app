Movie Recommendation App  

A modern, responsive, and production-ready movie recommendation platform built with Next.js 15 (React 19)  and powered by The Movie Database (TMDB) API. The goal of this project is to showcase clean architecture, scalable frontend development, and real-world practices like authentication, state management, testing, and CI/CD.  


This project fetches real-time movie data from TMDB and allows users to:  

- Discover trending & popular movies  
- View detailed movie information (cast, crew, ratings)  
- Search for movies by title or keyword  
- Authenticate with Firebase  
- Experience smooth pagination and data caching

Tech Stack

Frontend

Next.js 15
React 19
Tailwindcss v4
TanStack React Query 
Axios
Typescript

Authentication

Login/Signup handled via Firebase Authentication
- Auth state stored in React Context
- Protected routes redirect unauthenticated users to the login page


Testing

Jest

Other Tools

CI/CD Pipeline for Linting and automatic deployment

App Features

- Movie List – Browse popular and trending movies.
- Movie Details – View full details including title, overview, cast, crew, ratings, and more.
- Search Functionality – Search movies by title or keyword.
- Pagination – Efficiently load movies without overwhelming the UI.
- Authentication – Secure login using Firebase Authentication.
- Data Caching – Cached API requests for better performance using React Query.
- Loaders – Smooth loading experience while fetching data.
- Responsive UI– Optimized for desktop and mobile devices.

Performance & Accessibility
  
- Lighthouse Score:90+ (Performance, Accessibility, SEO)
- Lazy Loading: Images and API data are loaded progressively
- Responsive: Fully mobile-first and cross-browser compatible

  
Architecture
  
  The app follows a feature-based architecture with separation of concerns

System Requirements
  
- Node.js >= 18.x  
- npm >= 9.x  
- Modern browser (Chrome, Edge, Firefox, Safari)

Future Improvements
  
  Add user-specific watchlist
  Implement dark mode toggle
  Support multi-language UI
  

