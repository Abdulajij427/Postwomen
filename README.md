# Postwomen

A lightweight clone of Postman for testing APIs, built entirely with **plain HTML, CSS and JavaScript**. No frameworks, no build step, no dependencies. Open it in a browser and start sending requests.

## Overview

Postwomen lets you build and send HTTP requests, then inspect the responses in a clean, readable interface. It was built to understand how API clients work under the hood: constructing requests with the Fetch API, handling headers and bodies, and rendering responses dynamically in the DOM.

## Features

- Send requests using **GET, POST, PUT, PATCH and DELETE**
- Enter any API URL and add **query parameters** as key/value pairs
- Add custom **request headers** with dynamic add/remove rows
- Write a **JSON request body** for POST, PUT and PATCH requests
- View the **response body** with pretty-printed JSON
- See the **status code**, **response time** and **response size**
- Inspect **response headers**
- Error handling for invalid URLs, invalid JSON and network failures
- Responsive layout with a simple, Postman-inspired UI

> Adjust this list to match exactly what your version supports.

## Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Structure of the app |
| CSS3 | Layout, styling and responsiveness |
| JavaScript (ES6+) | Request logic, DOM updates, Fetch API |

## Getting Started

### Run locally

```bash
# Clone the repository
git clone https://github.com/<your-username>/postwomen.git

# Go into the project folder
cd postwomen

# Open index.html in your browser
```

You can also use the VS Code **Live Server** extension for auto-reload while developing.

## Usage

1. Choose an HTTP method from the dropdown.
2. Enter the request URL, for example `https://jsonplaceholder.typicode.com/posts/1`.
3. Add query parameters or headers if needed.
4. For POST, PUT or PATCH, enter a JSON body.
5. Click **Send**.
6. Check the status, time, size, headers and body in the response panel.

## Project Structure

```
postwomen/
├── index.html    # App markup
├── style.css     # Styling
└── script.js     # Request handling and DOM logic
```

## What I Learned

- Making asynchronous requests with `fetch`, `async/await` and `try/catch`
- Building and parsing headers, query strings and JSON bodies
- Manipulating the DOM dynamically for key/value rows and response rendering
- Measuring request time and response size
- Handling CORS and network errors

## Known Limitations

- Requests run in the browser, so they are subject to **CORS** restrictions
- No saved collections, environments or request history yet

## Future Improvements

- Save request history and collections with `localStorage`
- Support for authentication (Bearer token, Basic auth)
- Form-data and raw text body types
- Dark mode
- Export and import requests

## Author

**Abdul**, web developer based in Pune.

## License

This project is open source and available under the [MIT License](LICENSE).
