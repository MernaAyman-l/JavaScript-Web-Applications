# JavaScript Web Applications

A curated collection of three browser-based projects built with **HTML, CSS, and Vanilla JavaScript**. The projects demonstrate practical DOM manipulation, CRUD operations, search, filtering, sorting, and asynchronous API integration.

## Projects

| Project | What it demonstrates | Run |
| --- | --- | --- |
| [CRUD Table Manager](./01-CRUD-Table-Manager/index.html) | Create, read, update, and delete records; form validation; safe DOM rendering | Open `index.html` |
| [Movie Search Showcase](./02-Movie-Search-App/index.html) | Movie cards, live search, image fallbacks, safe external links | Open `index.html` |
| [Product Shop](./03-Product-Shop/index.html) | Fetch API data, loading/error states, category filters, price sorting | Open `index.html` |

## Tech Stack

- HTML5
- CSS3 (responsive layouts, Flexbox, transitions)
- Vanilla JavaScript (ES6+)
- DOM APIs and event listeners
- Fetch API and asynchronous JavaScript

## Getting Started

1. Clone or download this repository.
2. Open any project's `index.html` file in a modern browser.
3. The CRUD and movie projects work without a build step. The movie app loads poster images and Google Fonts from external services.
4. The Product Shop requires an internet connection to retrieve products from the Fake Store API.

No package manager, framework, or build process is required.

## Project Notes

- The CRUD app stores records in memory only. Refreshing the page resets the list.
- The movie catalogue is a small static sample. Poster images are loaded from TMDB's image CDN; the external links are trailer links, not full movie streams.
- The Product Shop combines selected category filters with the chosen price sort order. Its product data is provided by the Fake Store API.
- User- and API-provided text is inserted using safe DOM text APIs rather than interpolated into HTML.

## Learning Outcomes

These projects provide practice with:
- Selecting and updating DOM elements.
- Handling form submissions and user input.
- Creating elements and attaching event listeners.
- Working with arrays using `map`, `filter`, and `sort`.
- Fetching remote data with `async/await`.
- Handling loading, empty, and error states.
- Writing maintainable client-side code without a framework.

## Author

**Merna Ayman Louis**  
Computer Science Graduate — Helwan University

- GitHub: [MernaAyman-l](https://github.com/MernaAyman-l)
- Portfolio: [Personal Portfolio](https://mernaayman-l.github.io/Portfolio-Website/)
- LinkedIn: [Merna Ayman](https://www.linkedin.com/in/merna-ayman-l/)

---

This repository is an organized collection of selected learning projects. The original repositories are preserved separately.
