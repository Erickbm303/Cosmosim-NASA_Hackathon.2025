☄️ CosmoSim - Meteor Impact Simulator

A web-based simulator for visualizing meteor impacts on Earth — including effects on nearby cities, earthquake zones, and tsunami potential.
Now fully hosted on Cloudflare.

🌍 Overview

The Meteor Impact Simulator allows users to model meteor collisions with Earth and see how different impact parameters affect surrounding areas.
It integrates NASA Near-Earth Object (NEO) data along with historical earthquake and tsunami datasets to estimate impact consequences and show the proximity of major cities to the impact site.

✨ Features

☄️ Meteor Impact Simulation – Calculates crater and tsunami radii based on input parameters

🌊 Earthquake & Tsunami Data Integration – Incorporates real historical records

🏙️ City Proximity Visualization – Displays how close major cities are to the impact area

📈 NASA NEO Dataset – Uses authentic space object data for meteor selection

⚙️ Parameter Adjustment – Customize factors like water depth, meteor size, and density

💻 Cloud-Hosted Web App – No setup required beyond uploading data files

🧩 Project Structure

meteor_impact_interface_HTML_Send.html – Main interface

meteor_impact_interface_Javascript_send.js – Core simulation and logic

excel_data/ – Directory containing required datasets:

neo_data_five_highlighted_only.csv – NASA Near-Earth Objects data

global_earthquake_30_data_clean.csv – Historical earthquake data

tsunamis_cleaned.csv – Historical tsunami data

☁️ Cloud Deployment

The app runs entirely in the cloud via Cloudflare Workers — no installation required.

🔧 Setup Instructions

Download the three CSV files from this repository:

neo_data_five_highlighted_only.csv

global_earthquake_30_data_clean.csv

tsunamis_cleaned.csv

Visit the live simulator:
👉 https://cosmosim-v3.erickdamian-buitrago.workers.dev/

Upload the files in their respective fields.

Select a meteor from the NASA dataset.

Click on the map to choose an impact point.

Press Simulate to view crater, tsunami, and city impact results.

🧠 Usage Summary

Upload CSV datasets.

Choose a meteor from the dropdown menu.

Select an impact location.

Adjust any parameters as desired.

Click Simulate and explore the results — including crater size, tsunami radius, and city proximity.
