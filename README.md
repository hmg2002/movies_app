🎬 Movie Explorer

Movie Explorer is a responsive, full-stack React.js application that lets users search for movies, discover trending titles, and browse a complete list of movies — all with a seamless, optimized user experience.

The app integrates debounced search, trending list updates, and user search analytics, backed by a complete function app and database.

🚀 Features

✅ Optimized Search Experience


Debounced search input with a 500ms delay ensures minimal API calls while maintaining a responsive interface.

Search results fetched directly from TMDb (The Movie Database) API.

✅ Trending Movies


Displays a constantly updating trending movies list, synced in real-time from TMDb.

✅ Complete Movies List


Browse a full list of movies fetched from the TMDb API.

✅ User Search Analytics


User search queries and metrics are logged and tracked using Appwrite, providing valuable insights on search trends and activity.

✅ Full-stack Functionality


Backend functions and database logic handle analytics and trending updates. Fully functional on localhost for development and testing.


🛠️ Tech Stack

Frontend: React.js, React Hooks

APIs: TMDb (The Movie Database) API

Backend & Analytics: Appwrite (for user search metrics and database)

Deployment: Localhost (development)


📊 Key Statistics

🔎 Search input is debounced with a 500ms delay for optimal performance.

🌐 Runs on localhost during development (http://localhost:5173 by default).

📈 User search queries are logged and metrics calculated by Appwrite functions.

🔄 Trending list is updated dynamically as data from TMDb changes.


📦 Setup & Installation

1️⃣ Install dependencies:

bash

npm install


2️⃣ Start the app on localhost:

bash

npm start


The app will run on:

🌐 http://localhost:5173


🔗 External Services

TMDb API — for movie data and trending lists.

Appwrite — for backend functions, user analytics, and database storage.


📃 License

None.
