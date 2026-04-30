# Hello World Node.js Web App

A simple Node.js web application that displays "Hello World" in your browser.

## Project Structure

```
NodeJSProject/
├── package.json      # Project configuration and dependencies
├── server.js         # Express server
└── public/
    └── index.html    # HTML file served to the browser
```

## Requirements

- Node.js (v14 or higher)
- npm (comes with Node.js)

## Setup & Run

### 1. Install Dependencies
Open a terminal in this project directory and run:
```bash
npm install
```

### 2. Start the Server
```bash
npm start
```

You should see a message like:
```
Server is running on http://localhost:3000
```

### 3. Open in Browser
Open your web browser and navigate to:
```
http://localhost:3000
```

You should see a styled "Hello World" page with the current date and time.

## Stopping the Server
Press `Ctrl + C` in the terminal to stop the server.

## What's Included

- **Express.js**: A lightweight web framework for Node.js
- **HTML5**: A styled HTML page with gradient background
- **JavaScript**: Client-side script to display the current timestamp

## Customization

You can modify:
- `public/index.html` - Change the HTML content and styling
- `server.js` - Add more routes or middleware
- `package.json` - Add more dependencies as needed

Enjoy your Node.js web app!
