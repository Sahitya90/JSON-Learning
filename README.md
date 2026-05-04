# Taco Recipe Viewer 🌮

A web app that displays detailed taco recipes based on user selection. 
Built to understand how JSON data is parsed and passed from server to frontend using EJS templates.

## Tech Used
- Node.js (ES Modules)
- Express.js
- EJS (Embedded JavaScript Templates)
- Body Parser
- JSON

## How to Run
1. Clone the repo
2. Run `npm install`
3. Run `node index.js`
4. Open `http://localhost:3000`

## How it Works
1. User selects a taco type (Chicken, Beef or Fish)
2. Form sends a POST request to /recipe
3. Server parses the JSON data and picks the correct recipe
4. Recipe is passed to EJS template and rendered on the page

## What I Learned
- How JSON data is structured and parsed using JSON.parse()
- How to pass data from Express server to EJS templates
- How EJS conditionals work with if/else blocks
- How switch statements handle multiple route cases
- Difference between res.render() and res.redirect()
