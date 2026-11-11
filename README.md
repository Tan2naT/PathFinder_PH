# PathFinder PH - Location Alarm & Navigator

PathFinder PH is a mobile-responsive web application designed for commuters and travelers in the Philippines. It allows users to set a destination on a map and triggers an audible/vibrating alarm once they arrive within a specified radius.

## 🚀 Features
- **Live GPS Tracking:** Real-time location monitoring using the Geolocation API.
- **Arrival Alarm:** Audio synth alerts (via Tone.js) and vibration patterns when reaching the destination.
- **Smart Routing:** Displays the walking path and calculates ETA using the OSRM (Open Source Routing Machine).
- **Location Search:** Integrated Nominatim Geocoding to find places across the Philippines.
- **Simulation Mode:** Test the app's functionality without leaving your seat.
- **Responsive Design:** Built with Tailwind CSS for a seamless mobile experience.

## 🛠️ Tech Stack
- **Frontend:** HTML5, Tailwind CSS
- **Maps:** [Leaflet.js](https://leafletjs.com/)
- **Audio:** [Tone.js](https://tonejs.github.io/)
- **Icons:** FontAwesome
- **Data:** OpenStreetMap & OSRM

## ⚙️ How to Use
1. **Host on HTTPS:** Geolocation features require a secure connection. GitHub Pages is perfect for this.
2. **Search or Tap:** Use the search bar to find a destination or tap anywhere on the map.
3. **Set Radius:** Choose your preferred alert distance (50m to 500m).
4. **Arm Alarm:** Click the "ARM LOCATION ALARM" button.
5. **Permissions:** Ensure you grant Location and Audio permissions when prompted by your browser.

## ⚠️ Important Notes
- **Privacy:** This app processes location data entirely in the browser. No location data is stored or sent to a server (except for geocoding and routing requests to OSM/OSRM).
- **Battery:** Continuous GPS usage can impact battery life.
- **Accuracy:** GPS accuracy depends on your device and environmental factors (towers, buildings, etc.).

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).
```

### 2. The `LICENSE` File
It is standard practice to include a license. Create a file named `LICENSE` and paste the MIT License:

```text LICENSE
MIT License

Copyright (c) 2023 PathFinder PH

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.