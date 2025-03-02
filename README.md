# Topic 4: State and Forms by Alexander Andersen

## Overview


This repository contains a React-based feedback widget application built as part of the Topic 4: State and Forms homework. The application is designed for the "Sip Happens Café" and allows users to submit feedback (good, neutral, bad) while displaying real-time statistics such as the total number of feedbacks and the percentage of positive reviews. Additionally, the feedback is persisted between page reloads using local storage, and a full-screen background video enhances the visual appeal.

## Features
  Feedback Collection: Users can submit their feedback by clicking one of the buttons for good, neutral, or bad.
  Live Statistics: The app calculates and displays:
    Total feedback count (good + neutral + bad)
    Percentage of positive (good) feedback
  Reset Functionality: A reset button appears when feedback has been provided, allowing users to clear the statistics.
  Data Persistence: Feedback statistics are saved to local storage, so they persist even after the page is refreshed.
  Background Video: A full-screen background video (bg.mp4) enhances the visual experience.
  Modern Tech Stack: The project is built using React, Vite, and CSS Modules for modular styling.
  
## Technology Stack
  React – for building the user interface.
  Vite – for fast development, bundling, and serving the application.
  CSS Modules – to encapsulate component-specific styles.
  Local Storage API – to persist state across page reloads.
  HTML5 Video – used to display a dynamic, full-screen background.

## Installation and Setup
  1. Clone the repository:

    git clone https://github.com/your-username/goit-neo-react-hw-module2.git
    
  2. Navigate to the project directory:

    cd goit-neo-react-hw-module2
    
  3. Install dependencies:

    npm install
    
  4. Run the development server:

    npm run dev
  5. Open your browser and navigate to the provided local URL (usually http://localhost:5173).
  
## Project Structure (Platform Map)

    goit-neo-react-hw-module2/
    ├── node_modules/
    ├── public/
    │   ├── bg.mp4              // Full-screen background video file
    │   └── index.html          // HTML entry point for the app
    ├── src/
    │   ├── index.css           // Global styles (including centering and typography)
    │   ├── main.jsx            // React entry point that renders the App component
    │   ├── App.jsx             // Main component managing state, local storage, and layout
    │   └── components/
    │       ├── Feedback/
    │       │   ├── Feedback.jsx         // Displays feedback statistics (good, neutral, bad, total, positive %)
    │       │   └── Feedback.module.css  // Styles for the Feedback component
    │       ├── Options/
    │       │   ├── Options.jsx          // Contains feedback buttons and the Reset button
    │       │   └── Options.module.css   // Styles for the Options component
    │       └── Notification/
    │           ├── Notification.jsx     // Displays a message when no feedback has been collected
    │           └── Notification.module.css  // Styles for the Notification component
    ├── package.json
    └── vite.config.js
