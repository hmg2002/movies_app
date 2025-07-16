# 🎬 Movie Explorer
Movie Explorer is a responsive, full-stack React.js application that lets users search for movies, discover trending titles, and browse a complete list of movies — all with a seamless, optimized user experience.

The app integrates debounced search, trending list updates, and user search analytics, backed by a complete function app and database.

# 🚀 Features
- ✅ Optimized Search Experience
Debounced search input with a 500ms delay ensures minimal API calls while maintaining a responsive interface.
Search results fetched directly from TMDb (The Movie Database) API.

- ✅ Trending Movies
Displays a constantly updating trending movies list, synced in real-time from TMDb.

- ✅ Complete Movies List
Browse a full list of movies fetched from the TMDb API.

- ✅ User Search Analytics
User search queries and metrics are logged and tracked using Appwrite, providing valuable insights on search trends and activity.

- ✅ Full-stack Functionality
Backend functions and database logic handle analytics and trending updates. Fully functional on localhost for development and testing.

# 🛠️ Tech Stack
- Frontend: React.js, React Hooks
- APIs: TMDb (The Movie Database) API
- Backend & Analytics: Appwrite (for user search metrics and database)
- Deployment: Localhost (development)

# 📊 Key Statistics
- 🔎 Search input is debounced with a 500ms delay for optimal performance.
- 🌐 Runs on localhost during development (http://localhost:3000 by default).
- 📈 User search queries are logged and metrics calculated by Appwrite functions.
- 🔄 Trending list is updated dynamically as data from TMDb changes.

#📦 Setup & Installation
- 1️⃣ Install dependencies:
npm install

- 2️⃣ Start the app on localhost:
npm start

- The app will run on:
🌐 http://localhost:3000

# 🔗 External Services
- TMDb API — for movie data and trending lists.
- Appwrite — for backend functions, user analytics, and database storage.

# 📃 License
None.

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
