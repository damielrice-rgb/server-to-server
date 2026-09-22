# Server-to-Server Connection Project

This project is a basic Express.js server that serves HTML pages using Node.js.

## Features

- Created an Express server using Node.js
- Used routes to serve different pages
- Created a home route (`/`) for the main page
- Created a contact route (`/contact`) for the contact page
- Used the `path` module to locate HTML files
- Used `res.sendFile()` to send HTML files to the browser
- Ran the server locally on port 3000

## How to Run

Install the dependencies:

```bash
npm install
```

Start the server:

```bash
node server.js
```

Then open:

```text
http://localhost:3000
```

The contact page can be found at:

```text
http://localhost:3000/contact
```
