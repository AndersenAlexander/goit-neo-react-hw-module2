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
  public/: Contains static assets (e.g., bg.mp4 and index.html).
  src/: Contains all the React source code:
    index.css: Global CSS styles to ensure the entire app is centered and styled uniformly.
    main.jsx: The entry point that bootstraps the React app.
    App.jsx: The main component that handles application logic (state, local storage, conditional rendering) and renders the child components.
    components/: Each component resides in its own folder along with its corresponding CSS Module file.

## Design

![Screenshot 2025-03-03 001434](https://github.com/user-attachments/assets/ca663996-06f9-4347-a90e-189c1e3967f6)

![Screenshot 2025-03-03 001415](https://github.com/user-attachments/assets/5488088c-01e6-4a4b-b6dd-a31066bfdb7e)

## Usage
  Submit Feedback: Click the “Good”, “Neutral”, or “Bad” buttons to submit your feedback. The statistics will update immediately.
  Reset Feedback: Once feedback is provided, a “Reset” button appears allowing you to clear all the feedback.
  Persistent State: Refreshing the page retains the feedback data due to local storage integration.
  Background Video: The video plays in the background, providing an engaging visual experience.
  
## License
This project is licensed under the MIT License.

## Contributing
Contributions are welcome! Feel free to fork this repository, make your changes, and submit a pull request. If you encounter any issues or have suggestions, please open an issue on GitHub.



## 
This detailed description, along with the project structure (platform map), should provide a comprehensive overview of your project for anyone visiting your GitHub repository.








