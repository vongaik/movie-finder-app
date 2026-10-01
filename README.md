# 🎬 My Movie Finder App

This is a responsive single-page web application that lets users **search, browse, and explore movies and actors** using live data from *The Movie Database (TMDb) API*. The app dynamically fetches and displays content without page reloads offering a fast, interactive, and modern movie discovery experience.

[Visit site here](https://vongaik.github.io/movie-finder-app/)

<img width="2122" height="1346" alt="Screen Shot 2026-03-02 at 14 56 12" src="https://github.com/user-attachments/assets/1dac8719-0925-4110-89e4-255b272d8ece" />


---

## Key Features
- **Single Page Application (SPA):** All interactions happen on one page using dynamic content rendering.
- **Real-Time Movie Search:** Search movies by keywords using TMDb’s `/search/movie` REST endpoint.
- **Popular Movies View:** Fetches trending titles via `/movie/popular` and dynamically renders results.
- **Dynamic Actor Details:** Click on any actor to expand and view detailed info (biography, job title, etc.) from the `/person/{id}` endpoint.
- **Multiple Display Modes:** Switch between grid and list views with seamless layout toggling.
- **Pagination:** Results include fully functional pagination that updates dynamically based on API results.
- **Interactive UI:** Built with Mustache.js templates and jQuery to render API responses instantly.
- **Error Handling & UX Enhancements:** Gracefully handles missing data and enhances readability and user flow.

---

## Technologies Used
| Technology | Purpose |
|-------------|----------|
| **HTML5 / CSS3 / JavaScript (ES6)** | Core web app structure and interactivity |
| **jQuery** | DOM manipulation and event handling |
| **AJAX** | Asynchronous API requests for smooth, real-time updates |
| **Mustache.js** | Client-side templating for clean, reusable UI components |
| **JSON** | Data format for REST API responses |
| **TMDb RESTful API** | Provides movie, TV, and cast data |
| **GitHub Pages** | Hosting and deployment |

---

## What This Project Demonstrates
This project showcases my ability to:
- Build **fully functional SPAs** using RESTful APIs and client-side rendering.
- Write clean, modular JavaScript for **dynamic UI/UX**.
- Implement **real-world data fetching and state management** with AJAX.
- Use **templating engines** for scalable front-end design.
- Manage **API integration** and handle asynchronous logic effectively.
- Deploy and maintain front-end web apps using GitHub Pages.

---

## Project Architecture
The app is designed around modular JS functions:
- `loadPopularMovies()` – fetches and displays trending content.
- `searchMovies(pageNumber)` – dynamically queries and renders movie search results.
- `loadMovieDetails(movieId, $expandMovie)` – expands inline details for selected titles.
- `loadActorDetails(actorId, $expandCast)` – expands inline biography and credits for selected cast members.
- Pagination and event listeners handle user navigation and UI updates.

---

## Author
**Vongai Kwenda**  
Information Technology | Software Development | API Integration  
[GitHub Portfolio](https://github.com/vongaik)

---

## Future Enhancements
- Add favorites/watchlist functionality. 
- Implement lazy loading for improved performance.  
- Introduce local storage for offline movie list persistence.  

---

⭐ *Built from scratch as a solo project, focused on front-end engineering, clean UI design, and robust API integration.*
