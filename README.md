# Dijkstra Travel Planner
-A web application that helps users plan the shortest travel route between locations using Dijkstra’s algorithm.  
-It also displays live weather data, integrates Google Maps for visual routes, and shows place information using the Wikipedia API — all packed in a user-friendly UI.

---

## Features
```
-  Select source and destination cities to calculate the shortest route.
-  Implements Dijkstra’s algorithm for efficient route planning.
-  Live Weather API integration to show current weather of selected cities.
-  Real-time route display using Google Maps.
-  Travel booking links (bus/train) for quick access.
-  Get to know the place using Wikipedia integration.
-  Clean, interactive, and responsive frontend built with HTML, CSS, and JavaScript.
```
---

## Project Structure
```
├── index.html           # Main frontend interface
├── styles.css           # Styling for the UI
├── script.js            # Core JS for UI interactions and Dijkstra logic 
├── graph.json           # JSON file containing graph data (cities and connections) 
├── weather.js           # Fetches weather data using OpenWeatherMap API 
├── maps.js              # Handles Google Maps route display 
└── wiki.js              # Fetches Wikipedia info for the selected city
```
---

##  How It Works

### Frontend

1. User selects source and destination locations.
2. Dijkstra's algorithm runs in the browser to find the shortest route.
3. Results are shown:
   - Route on Google Maps.
   - Live weather at both cities.
   - Wikipedia summary of the destination.
   - Travel booking links.

###  Weather API
- We used the OpenWeatherMap API to fetch real-time weather data.
- It displays temperature, condition, and weather icon for the selected cities.

### Dijkstra Logic
- Graph of cities is stored as a JSON file.
- Dijkstra’s algorithm is implemented in JavaScript.
- Shortest path and distance are computed and displayed instantly.

---

##  Getting Started

1. Clone the Repository
```
git clone https://github.com/yourusername/dijkstra-travel-planner.git
cd dijkstra-travel-planner
```
