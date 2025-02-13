Leaflet Earthquake Visualization

Overview

This project is a visualization tool for earthquake data using Leaflet.js and D3.js, displaying real-time earthquake data from the USGS GeoJSON Feed. The application plots earthquakes on an interactive map, with marker size corresponding to earthquake magnitude and color indicating depth.

Project Structure

leaflet-challenge/
│── Leaflet-Part-1/
│   ├── index.html
│   ├── static/
│   │   ├── css/
│   │   │   ├── style.css
│   │   ├── js/
│   │   │   ├── logic.js

Features

Earthquake Data Visualization: Displays earthquake locations with circle markers.

Marker Scaling: The size of each marker represents the magnitude of the earthquake.

Color Gradient: Depth is represented using a color scale from green (shallow) to red (deep).

Popups: Clicking on a marker reveals earthquake details (magnitude, depth, location).

Layer Control: Users can toggle different base maps and overlays.

Legend: A color-coded legend provides context for depth values.

Technologies Used

Leaflet.js - Interactive maps.

D3.js - Fetch and parse GeoJSON data.

HTML/CSS/JavaScript - Frontend structure and styling.

How to Run

Clone this repository:

git clone https://github.com/your-username/leaflet-challenge.git

Navigate to the Leaflet-Part-1 directory:

cd leaflet-challenge/Leaflet-Part-1

Open index.html in a web browser.

File Descriptions

index.html - The main webpage structure.

style.css - Styling for the map and legend.

logic.js - Contains JavaScript logic for fetching and displaying earthquake data.

Data Source

Earthquake data is retrieved from the USGS GeoJSON Feed:
USGS Earthquake Data

Credits

USGS for real-time earthquake data.

Leaflet and D3.js for mapping and data visualization.

This project is part of a challenge to improve earthquake data visualization and awareness.


