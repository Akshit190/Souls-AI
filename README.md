
# AI Question Answering Website

This is a simple AI-powered question-answering web application. Users can ask questions through the frontend, and the backend fetches responses from an AI API.

## Features
- Interactive user interface to ask questions.
- Backend server to fetch AI-generated responses.

## Requirements
- Node.js and npm installed.
- An OpenAI API key.

## Setup Instructions
1. Clone this repository or extract the ZIP file.
2. Navigate to the project directory and install dependencies:
   ```
   npm install express body-parser node-fetch
   ```
3. Replace `YOUR_OPENAI_API_KEY` in `server.js` with your OpenAI API key.
4. Start the server:
   ```
   node server.js
   ```
5. Open the `index.html` file in your browser or navigate to `http://localhost:3000`.

## File Structure
- `public/index.html`: The frontend HTML file.
- `server.js`: Backend script for handling AI responses.
- `README.md`: Setup and usage instructions.
