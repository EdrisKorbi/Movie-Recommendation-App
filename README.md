# 🎬 Movie App

Movie App is a frontend web application built with React and Vite, designed to explore movies, manage favorites, and view details powered by The Movie Database (TMDB) API. This application provides a seamless experience for movie enthusiasts to discover new films and keep track of their preferred ones.

## ✨ Features

-   **Search for Movies**: Easily find any movie using the search bar.
-   **View Popular Movies**: Discover trending and popular movies on the homepage.
-   **Add/Remove Favorites**: Mark movies as favorites and manage your personalized list.
-   **Pagination**: Navigate through extensive movie lists with easy-to-use pagination.
-   **Movie Details Modal**: Get detailed information about any movie through an interactive modal, fetched by movie ID.

## 🚀 Tech Stack

-   **Frontend**: React (Vite)
-   **Language**: JavaScript
-   **Styling**: CSS
-   **API**: The Movie Database (TMDB) API

## ⚙️ Installation & Setup

Follow these steps to get the Movie App up and running on your local machine.

### Prerequisites

Ensure you have Node.js and npm (or Yarn) installed.

### Clone the Repository

```bash
git clone https://github.com/EdrisKorbi/Movie-Recommendation-App.git
cd Movie-Recommendation-App
```

### Install Dependencies

```bash
npm install
# or
yarn install
```

### Environment Variables

This project uses environment variables for the TMDB API key. Create a `.env` file in the root directory of the project with the following content:

```
VITE_API_KEY="YOUR_TMDB_API_KEY"
```

Replace `YOUR_TMDB_API_KEY` with your actual API key from [The Movie Database (TMDB) API](https://www.themoviedb.org/documentation/api).

### Run the Application

```bash
npm run dev
# or
yarn dev
```

The application will typically run on `http://localhost:5173`.

## 🌟 Usage

1.  **Browse Popular Movies**: Upon launching the app, you'll see a list of popular movies.
2.  **Search**: Use the search bar at the top to find specific movies.
3.  **Favorites**: Click the heart icon on any movie card to add or remove it from your favorites list.
4.  **View Details**: Click on a movie card to open a modal with more detailed information about the movie.
5.  **Pagination**: Use the pagination controls to navigate through long lists of movies.

## 📂 Project Structure

The project follows a standard React/Vite application structure:

```
Movie-App/
├── public/
│   └── vite.svg
├── src/
│   ├── assets/             # Static assets like images, icons
│   ├── components/         # Reusable UI components
│   │   ├── MovieCard.jsx
│   │   ├── SearchBar.jsx
│   │   └── ...
│   ├── App.css             # Global application styles
│   ├── App.jsx             # Main application component
│   ├── index.css           # Root CSS file
│   ├── main.jsx            # Entry point of the React application
│   └── ...
├── .env.example            # Example environment file
├── .gitignore
├── index.html
├── package.json            # Project dependencies and scripts
├── vite.config.js          # Vite configuration
└── README.md
```

## 💡 Future Improvements

-   **User Authentication**: Implement user login/signup to store favorite movies persistently.
-   **Movie Filtering/Sorting**: Add options to filter movies by genre, release year, or sort by rating, popularity, etc.
-   **Responsive Design Enhancements**: Further optimize the UI for various screen sizes and devices.
-   **Error Handling & Loading States**: Improve user feedback with more robust error handling and distinct loading indicators.
-   **Offline Support**: Implement caching strategies for basic offline functionality.

## 📄 License

This project is licensed under the MIT License - see the `LICENSE` file for details. (Note: A `LICENSE` file should be created in the root of the project if one doesn't exist.)
