# Mapty
# Mapty - Workout Tracker

![Mapty Logo](./logo.png)

## Table of Contents
- [Description](#description)
- [Key Features and Technologies](#key-features-and-technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

## Description
Mapty is a web application designed to help users track their running and cycling activities. The application uses the Leaflet.js library for mapping and geolocation, allowing users to log workouts based on their current location or by manually selecting a location on the map. All workout data is stored in the browser's local storage, ensuring that the data persists across sessions.

## Key Features and Technologies
- **Real-World Problem Solving**: The project addresses a practical problem by helping users track their running and cycling activities, which is a relevant and relatable use case.
- **Leaflet.js Integration**: Utilizes the Leaflet.js library for mapping and geolocation, showcasing the ability to integrate third-party libraries and work with maps.
- **Local Storage**: Stores data in the local storage, demonstrating knowledge of client-side storage, which is important for building offline-capable web applications.
- **Object-Oriented JavaScript**: Uses classes and inheritance (Workout, Running, and Cycling) to illustrate understanding of object-oriented programming in JavaScript.
- **Responsive Design**: Includes CSS for styling and responsiveness, indicating the ability to create visually appealing and user-friendly interfaces.
- **Event Handling**: Includes various event handlers for form submissions, input changes, and map interactions, showing the ability to manage user interactions effectively.

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/mapty-workout-tracker.git
    ```

2. Navigate to the project directory:
    ```bash
    cd mapty-workout-tracker
    ```

3. Open `index.html` in your preferred web browser.

## Usage
1. Open the application in your web browser.
2. Allow location access if prompted.
3. Click on the map to select a location or use your current location.
4. Fill out the workout form with the activity details and submit.
5. View your logged workouts in the sidebar and on the map.
6. Click on a workout in the sidebar to pan the map to the workout's location.

## Code Structure
Here's an overview of the code structure for the project:

### HTML (`index.html`)
- The main structure of the application, including the sidebar and map container.
- Includes external stylesheets and scripts.

### CSS (`style.css`)
- Styling for the application, including the sidebar, forms, and map.
- Uses CSS variables for consistent theming and colors.
- Responsive design to ensure the application is user-friendly on various devices.

### JavaScript (`script.js`)
- Contains the core logic and functionality of the application.
- Defines classes for workouts and the main application class.
- Handles geolocation, map interactions, form submissions, and local storage.
- Demonstrates object-oriented programming principles and event handling.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
This project is inspired by Jonas Schmedtmann's course. Special thanks to him for the guidance and inspiration.
