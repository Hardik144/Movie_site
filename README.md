# 🎬 MovieHub - React Movie Website

**MovieHub** is a sleek and simple React-based movie website where users can:

- 🔍 Search for movies
- 🗓️ View movie titles with their release year
- 🖼️ See poster images of movies
- ❤️ Add movies to their favorite list

---

## 🚀 Features

- **Movie Listing**: Browse popular movies with their posters and release years.
- **Search Functionality**: Instantly find movies by name using the search bar.
- **Favorites Section**: Add and view your favorite movies in a separate section.

---

## 🛠️ Tech Stack

- **Frontend**: React, JavaScript, CSS
- **API**: [The Movie Database (TMDb)](https://www.themoviedb.org/)
- **State Management**: React Hooks (`useState`, `useEffect`)

---

## 🔑 API Key

This project uses the TMDb API. To run the app, you'll need an API key:

1. Sign up at [TMDb](https://www.themoviedb.org/)
2. Go to [API Settings](https://www.themoviedb.org/settings/api) and generate a key
3. Create a `services/api.js` file in the root of the project and add:

```env
REACT_APP_TMDB_API_KEY=your_api_key_here
