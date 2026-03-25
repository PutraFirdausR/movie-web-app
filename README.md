<div align="center">
<h1>🎬 Movie Web App</h1>
<p>A simple web application for searching and viewing information about your favorite movies, built purely with HTML, CSS, and JavaScript.</p>

<p>
<a href="https://github.com/PutraFirdausR/movie-web-app/stargazers">
<img src="https://img.shields.io/github/stars/PutraFirdausR/movie-web-app?style=social" alt="Stars" />
</a>
<a href="https://github.com/PutraFirdausR/movie-web-app/network/members">
<img src="https://img.shields.io/github/forks/PutraFirdausR/movie-web-app?style=social" alt="Forks" />
</a>
</p>
</div>

<br />

## 📌 About the Project

Movie Web App is an interactive frontend project that allows users to search for movie titles and view details (such as poster, release year, and plot). Movie data is fetched in real-time using the Fetch API from a third-party movie data provider.

This project is perfect for practicing basic DOM manipulation, asynchronous JavaScript (Async/Await & Fetch), and responsive interface design.

## 🚀 Key Features

* Movie Search: Type a movie title and get search results instantly.
* Detailed Information: Displays the movie poster, title, release year, and other details.
* Responsive Design: Adapts to any screen size, suitable for both PC and mobile devices.
* Light & Fast: Runs directly in the browser without the need for additional compilation.

## ⚙️ Technologies Used

* HTML5 - For the framework and structure of the page.
* CSS3 - For styling, layout, and visual animation.
* JavaScript (ES6+) - For application logic, DOM manipulation, and API calls (Fetch API).

## 🛠️ How to Use

Because this project uses pure HTML, CSS, and JS, you don't need to install any modules or libraries.

### Steps:

1. **Clone this repository:**
```bash
git clone [https://github.com/PutraFirdausR/movie-web-app.git](https://github.com/PutraFirdausR/movie-web-app.git)
```
2. **Go to the project folder:**
```bash
cd movie-web-app
```
3. **Run the application:**
Simply double-click the `index.html` file to open it in your default browser. *(Alternative: Use the "Live Server" extension in VS Code for a better experience).*

### 🔑 API Key Settings (If Using an External API)
If this application retrieves data from an API such as OMDB or TMDB, make sure you replace `API_KEY` in the `script.js` file (or your own JS file) with your own API key.
```javascript
// Example in script.js file
const API_KEY = 'insert_your_api_key_here';
