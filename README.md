
# Flood Early Detection System | BMKG Data

## Overview

The **Flood Early Detection System** provides a real-time monitoring platform to predict and alert users about flood risks using BMKG (Indonesian Meteorological, Climatological, and Geophysical Agency) data. The system integrates weather data, real-time water levels, and AI-powered flood predictions to help communities prepare for potential flooding events. 

This web application is designed to monitor flood risk based on various environmental factors, including rainfall, water levels, soil moisture, and river capacities, and provides actionable insights for timely response.

## Features

- **Real-Time Monitoring**: View live weather data and flood risk levels for various regions.
- **Interactive Map**: Display real-time flood risk information on an interactive map.
- **AI-Based Risk Prediction**: Get AI-driven flood risk predictions based on historical data and real-time inputs.
- **Dynamic Data**: Visualize water levels, rainfall, and flood risk with interactive charts.
- **Location-Based Alerts**: Select locations to get real-time flood alerts and detailed analysis.
- **Comprehensive Location Analysis**: View detailed information such as water levels, rainfall, soil moisture, and more for selected locations.

## Technologies Used

- **HTML/CSS**: For the structure and styling of the webpage.
- **Tailwind CSS**: Utility-first CSS framework for styling the application responsively.
- **Font Awesome**: For adding icons to the interface.
- **Chart.js**: For visualizing rainfall and water level data with interactive charts.
- **JavaScript**: For handling interactivity, dynamic data updates, and real-time data simulation.

## Installation

This project uses basic HTML, CSS, and JavaScript, so it can be viewed directly in any modern browser without the need for complex installations. However, you will need to integrate the application with real-time data from the BMKG API for full functionality.

### Steps to Run Locally

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/shemilael/flood-early-detection-system.git
   ```

2. **Open the HTML File**:
   - Open the `index.html` file directly in your browser.

3. **Integrate with BMKG API**:
   - For real-time data, integrate the system with the BMKG API. You don't need to sign up for an API key on the BMKG website and follow their documentation for fetching weather and flood-related data.

4. **Run the Application**:
   - Open the `index.html` file in your browser to start monitoring real-time flood data.

## Usage

- **Select Location**: Use the location dropdown to choose a region and view live flood data, weather, and risk levels.
- **View Charts**: The Rainfall and Water Level charts will automatically update with real-time data, showing the historical trends of rainfall and water levels.
- **Flood Alerts**: If there’s a risk of flooding, an alert banner will display the flood warning for your selected region.
- **Run Comprehensive Analysis**: Use the "Run Comprehensive Analysis" button to get a detailed analysis and recommendations based on the current flood risk for the selected location.

## Customization

- You can customize the **locations** by updating the dropdown options in the HTML file.
- The **AI Model** can be enhanced or replaced with a more advanced model to improve flood risk predictions.
- You can also add more **data visualizations** or **alerts** depending on the needs of the application.

## Example Screenshots

- **Main Dashboard**: View real-time weather and flood data with dynamic charts.
- **Flood Map**: An interactive map displaying flood risk across various regions.
- **Comprehensive Location Analysis**: Detailed flood risk analysis and recommendations.

## Contributing

If you would like to contribute to this project, feel free to fork the repository, make improvements, and submit a pull request. You can help by adding more data sources, improving the UI/UX, or enhancing the flood prediction model.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

For more information or to contribute, visit the [GitHub repository](https://github.com/shemilael/flood-early-detection-system).
