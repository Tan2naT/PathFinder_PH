# PathFinder PH

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

PathFinder PH is a specialized, mobile-responsive web application designed to assist commuters and travelers across the Philippines. By utilizing real-time Geolocation and geofencing technology, the app allows users to set a destination and receive an immediate audible and physical (vibration) alert upon arrival within a designated radius.
## 🚀 Key Features
*   **Real-Time GPS Tracking:** High-precision location monitoring using the browser's native Geolocation API.
*   **Arrival Notifications:** Dual-alert system featuring a synthesized audio alarm (via Tone.js) and custom vibration patterns for mobile devices.
*   **Intelligent Routing:** Live visualization of walking paths and dynamic ETA calculations powered by the OSRM (Open Source Routing Machine).
*   **Localized Search:** Integrated geocoding through Nominatim, optimized for locating cities, landmarks, and streets within the Philippines.
*   **Diagnostic Simulation:** A built-in "Walk Simulation" mode to verify alarm triggers and routing logic without requiring physical movement.
*   **Mobile-First Design:** A dark-mode, high-contrast interface built with Tailwind CSS for optimal outdoor visibility.

## 🛠️ Technology Stack

*   **Mapping:** [Leaflet.js](https://leafletjs.com/) for interactive map rendering.
*   **Audio Engine:** [Tone.js](https://tonejs.github.io/) for cross-browser compatible alarm synthesis.
*   **Styling:** [Tailwind CSS](https://tailwindcss.com/) for a responsive, modern UI.
*   **Routing Data:** [OpenStreetMap](https://www.openstreetmap.org/) & [OSRM](http://project-osrm.org/).
*   **Icons:** [FontAwesome 6](https://fontawesome.com/).

## ⚙️ Installation & Deployment

Since PathFinder PH is a client-side application, it requires no backend installation.

1.  **Clone the Repository:**
