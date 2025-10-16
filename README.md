# Meteor Impact Simulator

A web-based simulator for visualizing meteor impacts on Earth, including effects on cities, earthquake zones, and tsunami potential.

## Features

- Meteor impact simulation with crater and tsunami radius calculations
- Integration with historical earthquake and tsunami data
- City impact visualization
- Interactive map interface using Leaflet.js
- CSV data integration for NEOs, earthquakes, and tsunamis

## Project Structure

- `meteor_impact_interface_HTML_Send.html` - Main HTML interface
- `meteor_impact_interface_Javascript_send.js` - JavaScript logic
- `excel_data/` - Directory containing CSV data files:
  - `neo_data_five_highlighted_only.csv` - Near Earth Objects data
  - `global_earthquake_30_data_clean.csv` - Historical earthquake data
  - `tsunamis_cleaned.csv` - Historical tsunami data

## Setup

1. Clone the repository
2. Open `meteor_impact_interface_HTML_Send.html` in a web browser
3. The application will automatically load the CSV data from the excel_data directory

## Usage

1. Select a meteor from the dropdown menu
2. Click on the map to set an impact point
3. Adjust parameters (water depth, density, etc.)
4. Click "Simulate" to see the impact effects
5. View earthquake, tsunami, and city data within the impact radius