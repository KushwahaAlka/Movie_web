```
# Cinema Scope - Your Movie Search Companion

## Overview

Cinema Scope is a web application that allows users to search for movies, view details, and manage a watchlist. Built with HTML, CSS, and JavaScript, this project fetches movie data from the OMDb API and presents it in an easy-to-use interface.

## Features

### HTML Features:

- **Semantic HTML:** Utilizes elements like `<header>`, `<nav>`, `<section>`, `<article>` for better structure and accessibility.
- **Forms:** Implements search functionality with `<input>` and `<button>` elements.
- **Media Elements:** Displays movie posters with the `<img>` tag.

### CSS Features:

- **Flexbox & Grid:** Leverages Flexbox for layout and Grid for arranging movie cards.
- **Responsive Design:** Ensures optimal viewing experience across different screen sizes (desktop, tablet, mobile).
- **Styling & Aesthetics:**  Implements a visually appealing design with custom colors, fonts, and spacing.

### JavaScript Features:

- **DOM Manipulation:**  Dynamically updates the webpage content based on user interactions and fetched data.
- **API Integration (Fetch API):** Fetches movie data from the OMDb API using asynchronous JavaScript.
- **Local Storage:** Persists the user's watchlist even after the browser window is closed.
- **Event Handling:** Listens for user events like search button clicks, adding/removing from watchlist, and more.

## Functionality

1. **Movie Search:**
   - Users can search for movies by title.
   - The application displays a grid of movie posters based on the search query.
2. **Movie Details:**
   - Clicking on a movie poster reveals details about the movie, including plot, director, actors, and ratings.
3. **Watchlist Management:**
   - Users can add movies to their watchlist.
   - The watchlist is persisted using local storage, so users can access it even after closing the browser window.
   - Users can remove movies from their watchlist.
4. **Error Handling:**
   - The application gracefully handles cases where movie data cannot be fetched or when the API is unavailable.
   - Informative error messages are displayed to the user.

## Project Structure

- `index.html`: The main HTML file for the movie search page.
- `watchlist.html`:  HTML file for the watchlist page.
- `style.css`:  The stylesheet for the application's visual presentation.
- `app.js`: The JavaScript file containing the logic for the movie search page.
- `watchlist.js`: The JavaScript file managing the watchlist functionality.

## How to Use

1. Clone or download the repository.
2. Open `index.html` in a web browser.
3. Start searching for movies, explore details, and manage your watchlist. 
```