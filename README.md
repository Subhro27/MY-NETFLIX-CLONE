# MY-NETFLIX-CLONE

# 🎬 Netflix Clone - Movie Listing and Detail Page

This project is a simple, static **Netflix clone** built with HTML, CSS, and JavaScript. It features a homepage displaying popular movies and a dynamic detail page for each selected movie.

## 📁 Project Structure
    index.html
    movie-detail.html


## 🔍 Features

### `index.html`
- Netflix-style homepage layout.
- Movie thumbnails with hover effects.
- Clickable cards redirecting to the movie detail page (`movie-detail.html?title=MovieName`).

### `movie-detail.html`
- Dynamic rendering of movie title and description based on URL parameter.
- Embedded video player with a sample video.
- Responsive layout with a fixed header.
- "More Like This" section showcasing related movies with clickable thumbnails.

## 🛠️ Tech Stack

- **HTML5**: Markup structure.
- **CSS3**: Responsive Netflix-style design.
- **Vanilla JavaScript**: Dynamic content rendering from URL parameters.

## 🚀 How to Run

1. Clone or download the repository.
2. Open `index.html` in any modern web browser.
3. Click on any movie card to navigate to the detail page.

> No backend or database required. This is a static frontend-only project.

## 🧠 Dynamic Behavior

On `movie-detail.html`, the movie title is extracted from the URL (e.g., `?title=Dark`) and used to:
- Display the title dynamically.
- Show a matching description (hardcoded in JS).
- Embed a sample video (same for all for now).

## 📝 To-Do / Suggestions

- Add a backend to fetch real data (Node.js, Firebase, etc.).
- Use a real video or trailer based on the movie.
- Improve accessibility and SEO with proper tags.
- Add responsiveness for smaller screens using media queries.

## 📸 Preview

> _(Include screenshots if possible)_

## 📄 License

This project is for educational/demo purposes only. Not affiliated with or endorsed by Netflix.
