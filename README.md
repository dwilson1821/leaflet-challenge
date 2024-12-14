# Leaflet Earthquake Visualization  

## Overview  

This project uses **Leaflet.js** to create an interactive map for visualizing global earthquake data provided by the **United States Geological Survey (USGS)**. The goal is to display the magnitude, depth, and location of earthquakes in a meaningful way to help the USGS educate the public and secure funding for earthquake research and related programs.  

The project includes:  
- Earthquake markers sized by magnitude.  
- Earthquake markers colored by depth.  
- Popups with detailed information about each earthquake.  
- A legend providing context for the data.  

---

## Repository Structure  

The repository is organized as follows:  

```  
leaflet-challenge/  
│  
├── Leaflet-Part-1/  
│   ├── index.html                # Main HTML file for the map  
│   ├── static/  
│   │   ├── js/  
│   │   │   └── logic.js          # JavaScript for map creation and data visualization  
│   │   └── css/  
│   │       └── styles.css       # Optional custom styles  
│   └── README.md                # Documentation for Part 1  
│  
└── Leaflet-Part-2/ (Optional)  
    ├── index.html  
    ├── static/  
    │   ├── js/  
    │   │   └── logic.js          # JavaScript for advanced visualizations  
    │   └── css/  
    │       └── styles.css  
    └── README.md                # Documentation for Part 2  
```  

---

## Features  

### 1. Interactive Earthquake Map (Part 1)  
- **Data Source**: USGS GeoJSON Feed (e.g., "All Earthquakes from the Past 7 Days").  
- **Markers**:  
  - **Size**: Reflects the magnitude of the earthquake.  
  - **Color**: Represents the depth of the earthquake (darker for greater depths).  
- **Popups**: Provide detailed information, including:  
  - Magnitude.  
  - Depth.  
  - Location (latitude and longitude).  
- **Legend**: Explains the color scale for earthquake depths.  

---

## Deployment  

The visualization is deployed using **GitHub Pages**.  

### Access the Live Map:  
[Deployed Earthquake Visualization](https://your-username.github.io/leaflet-challenge/Leaflet-Part-1)  

---

## Getting Started  

### Prerequisites  
Ensure you have the following installed locally:  
- A code editor (e.g., VS Code).  
- Git for version control.  

### Installation  

1. **Clone the Repository**  
   ```bash  
   git clone https://github.com/your-username/leaflet-challenge.git  
   cd leaflet-challenge/Leaflet-Part-1  
   ```  

2. **Run the Visualization Locally**  
   Open `index.html` in your browser to view the map locally.  

3. **Push Changes**  
   Push changes to your GitHub repository:  
   ```bash  
   git add .  
   git commit -m "Add feature or fix"  
   git push origin main  
   ```  

4. **Deploy to GitHub Pages**  
   - Go to your repository settings.  
   - Enable GitHub Pages under the "Pages" section.  
   - Choose the `main` branch and save.  

---

## Technical Details  

### Libraries Used  
- **Leaflet.js**: For map creation and visualization.  
- **D3.js**: For fetching and processing GeoJSON data.  
- **HTML/CSS/JavaScript**: For structuring, styling, and scripting the visualization.  

### Data Handling  
- **Source**: USGS GeoJSON feed (e.g., [All Earthquakes from the Past 7 Days](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson)).  
- Markers are created dynamically based on longitude and latitude.  
- Depth and magnitude are used for color and size customization, respectively.  

---

## Example Screenshots  

### Earthquake Map  
![Earthquake Map Example](screenshots/earthquake_map.png)  

### Popups  
![Popup Example](screenshots/popup_example.png)  

### Legend  
![Legend Example](screenshots/legend_example.png)  

---

## Part 2 (Optional)  

The second part of the challenge adds advanced visualizations by incorporating additional datasets, such as tectonic plate boundaries, and layering these on the map.  

Key features include:  
- Overlaying tectonic plate boundaries.  
- Providing additional context for earthquake data.  
