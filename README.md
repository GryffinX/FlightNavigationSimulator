# ✈️ Flight Navigation Simulator

An **interactive flight path visualization and algorithm simulator** built using **Leaflet.js**.  
This web application lets users select source and destination cities, visualize routes, and run different pathfinding algorithms (A*, Bellman-Ford, and an optimized hybrid).  
You can also add obstacles on the map grid and see how algorithms navigate around them.

---

## 🌍 Live Demo

 ``` 
    https://flight-navigation-simulator.vercel.app
 ```
   

## 🚀 Features

- 🗺️ **Interactive Map Interface** using [Leaflet.js](https://leafletjs.com/)
- 🧭 **City Selection**: Choose “From” and “To” cities across Tamil Nadu.
- 🤖 **Algorithms Supported**:
  - A* Pathfinding (fast and efficient)
  - Bellman-Ford (handles obstacles/negative weights)
  - Optimized A* (includes diagonal movement)
- 🚧 **Obstacle Mode**:
  - Click on the map to add obstacles.
  - Save obstacles and visualize routes avoiding them.
- 🔲 **Grid Overlay**: Toggle visibility of the simulation grid.
- 🧩 **Dynamic Visualization**:
  - Paths are shown as polylines between selected cities.
  - Start and goal markers are clearly indicated.

---

## 🧠 Tech Stack

| Component | Technology |
|------------|-------------|
| **Frontend** | HTML5, CSS3, JavaScript |
| **Map Rendering** | Leaflet.js |
| **Styling** | Custom CSS (Responsive) |
| **Algorithms** | A*, Bellman-Ford, Optimized A* |

---

## 🏗️ Project Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/flight-navigation-simulator.git
cd flight-navigation-simulator
