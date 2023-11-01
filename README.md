# Live Tracking System

## Overview

The Live Tracking System is a Python-based project that enables the visualization of trip data, identification of over-speeding segments, and display on an interactive map. This README provides an overview of the project, its features, and how to get started. This project was completed within the supervision of Techma Zone 

## Features

- Visualize trip routes and over-speeding segments on an interactive map.
- Customizable map styles using different tile layers.
- Informative popups with logos and website links.
- Suitable for tracking and analyzing trip data.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python (3.x)
- Required Python libraries: Pandas, Folium

## Installation

1. **Clone this repository:**

   ```bash
   git clone https://github.com/yourusername/live-tracking-system.git
   cd live-tracking-system

## Usage
1. Prepare your trip data:

   * Create or prepare your trip data in a CSV file (e.g., final_dataset.csv).
   * Ensure the data includes necessary columns such as "Date Time," "Latitude," "Longitude," and "over_speeding."

2. Modify the code:

   * Adapt the code to your specific data source and customization requirements.

3. Generate the interactive map:

   * Run the code to create the interactive map: python live_tracking_system.py

4. View the map:

The interactive map will be saved as an HTML file named "Live_tracking_trip_system.html."

## Contributing
Contributions are welcome! If you have ideas for improvements, bug fixes, or other enhancements, please open an issue or create a pull request.

## Acknowledgments
   * Folium: For the interactive map library.
   * Pandas: For data manipulation and analysis.
