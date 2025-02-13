# Leaflet Earthquake Visualization

## Overview

​<light>This project is a visualization tool for earthquake data using Leaflet.js and D3.js.</light>​ It displays real-time earthquake data from the USGS GeoJSON Feed. The application plots earthquakes on an interactive map, with marker size corresponding to earthquake magnitude and color indicating depth.

## Project Structure


## Features

<p>-   **Earthquake Data Visualization:** Displays earthquake locations with circle markers.
-   **Marker Scaling:** The size of each marker represents the magnitude of the earthquake.
-   **Color Gradient:** Depth is represented using a color scale from green (shallow) to red (deep).
-   **Popups:** Clicking on a marker reveals earthquake details (magnitude, depth, location).
-   **Layer Control:** Users can toggle different base maps and overlays.
-   **Legend:** A color-coded legend provides context for depth values.</p>

## Technologies Used

<p>-   Leaflet.js - Interactive maps.
-   D3.js - Fetch and parse GeoJSON data.
-   HTML/CSS/JavaScript - Frontend structure and styling.</p>

## How to Run

<p>1.  Clone this repository:</p>

leaflet-challenge/

│── Leaflet-Part-1/

│   ├── index.html

│   ├── static/

│   │   ├── css/

│   │   │   ├── style.css

│   │   ├── js/

│   │   │   ├── logic.js

2.  Navigate to the `Leaflet-Part-1` directory:

bash

    git clone https://github.com/your-username/leaflet-challenge.git

    

3.  Open `index.html` in a web browser.

## File Descriptions

-   `index.html` - The main webpage structure.

-   `style.css` - Styling for the map and legend.

-   `logic.js` - Contains JavaScript logic for fetching and displaying earthquake data.

## Data Source

Earthquake data is retrieved from the USGS GeoJSON Feed: [USGS Earthquake Data](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php)

## Example Map Screenshot

(Insert an image of the working visualization here)

## Future Enhancements

-   Implement `Leaflet-Part-2` for additional data layers.

-   Add user filtering options (e.g., filter by magnitude or date).

-   Improve UI with more interactive elements.

## Credits

-   [USGS](https://www.usgs.gov/) for real-time earthquake data.

-   [Leaflet](https://leafletjs.com/) and [D3.js](https://d3js.org/) for mapping and data visualization.

This project is part of a challenge to improve earthquake data visualization and awareness.
