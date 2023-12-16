
# IMDb Clone

Welcome to the IMDb Clone project! This web application emulates some of the key features of the popular Internet Movie Database (IMDb). Users can search for movies, view detailed information about specific movies, and manage a list of favorite movies.

## Overview

### Key Features

1. **Movie Search:**
   - Users can search for movies using a search bar on the index.html page.
   - The application utilizes the OMDB API to fetch and display search results dynamically.
   - Each search result includes a button to add the movie to the user's favorites list.

2. **Movie Details:**
   - Users can click on a movie in the search results to view detailed information on the movie.html page.
   - The application fetches and displays information such as the movie's poster, title, plot, year, director, genre, runtime, and IMDb rating.

3. **Favorites Management:**
   - Users can add movies to their favorites list by clicking the "Add to Favourites" button in the search results.
   - The favorites list is stored in the browser's local storage for persistence across sessions.
   - On the favourites.html page, users can view and manage their list of favorite movies.
   - Each movie in the favorites list includes a button to remove it from the list.

### Project Structure

The IMDb Clone is organized into three main JavaScript files:

1. **`search.js`:**
   - Handles movie search functionality and displays search results.
   - Allows users to add movies to their favorites list.

2. **`movieDetails.js`:**
   - Retrieves and displays detailed information about a specific movie.
   - Renders movie details on the movie.html page.

3. **`favourites.js`:**
   - Manages the display and removal of movies from the user's favorites list.
   - Renders favorites dynamically on the favourites.html page.

### Getting Started

To run the IMDb Clone:

1. Include the provided JavaScript files in  HTML pages.
2. Obtain an OMDB API key and update it in the files.
3. Customize HTML pages to include necessary elements.
4. Run the application and enjoy the IMDb-like experience of searching and managing favorite movies.

### Image of the website
![images](https://github.com/Manidheeraj123/imdb_clone/assets/100212243/38c91402-4639-45ea-b3cd-f6b5995412ee)




