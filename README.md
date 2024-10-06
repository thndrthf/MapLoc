# README for MapLocFINAL (macOS)

**Description**:
`MapLocFINAL` is a standalone application that reads weather and air quality data from saved files and visualizes it on a map using Folium. This tool is ideal for analyzing and comparing environmental conditions across multiple locations, presented on an interactive map.

**Usage**:
1. Place the `.txt` files containing weather and air quality data in the same directory as `MapLocFINAL`. The filenames should start with `WeatherAirQualityData_` for the program to recognize them.
2. Double-click `MapLocFINAL` or run it from the terminal:
   ```bash
   ./MapLocFINAL
   ```
3. The script will generate an HTML file (`CombinedFoliumMap_<timestamp>.html`), which will open automatically in your default browser. This map will display the locations with markers containing detailed weather and air quality information.

**Manual Data Management**:
- **Data Folder Management**: All `.txt` files used for data visualization should be saved in the same directory as the executable.
- You can manually add or remove these files to manage the locations visualized in the output map.

**Example Data File Format**:
- The script recognizes `.txt` files with sections labeled "Current Weather Information" and "Air Quality Information." Each line in the file should follow the format: `<Key>: <Value>`.


# README for MapViewFINAL2 (macOS)

**Description**:
`MapViewFINAL2` is a standalone application designed to visualize collected weather and air quality data on an interactive map. This version focuses on giving an overview of multiple datasets with an optimized zoom feature for a broader spatial perspective.

**Usage**:
1. Place the `.txt` files containing weather and air quality data in the same directory as `MapViewFINAL2`. The filenames should follow the naming convention `WeatherAirQualityData_`.
2. Double-click `MapViewFINAL2` or run it from the terminal:
   ```bash
   ./MapViewFINAL2
   ```
3. The application will generate an HTML file (`CombinedFoliumMap_<timestamp>.html`) containing all the visualized data. The map will open automatically in the default browser.

**Manual Data Management**:
- **Folder Explanation**: The data files (`WeatherAirQualityData_*.txt`) should be stored in the same directory as the executable. You can manually add, edit, or remove these files to control which data gets visualized in the map.

**Example Data File Format**:
- Each `.txt` file should contain sections titled "Current Weather Information" and "Air Quality Information." Each key-value pair should be formatted as `<Key>: <Value>`.
