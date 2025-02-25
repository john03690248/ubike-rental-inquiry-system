# Ubike Rental Inquiry System

This is a web-based system that displays YouBike station information in New Taipei City. It retrieves real-time bike availability data from the government open data API and visualizes the information using Highcharts gauge charts and Google Maps.

## Features

- Select an area to display YouBike station information
- Real-time bike availability and empty slot data
- Highcharts gauge chart visualization for bike status
- Google Maps integration to show station locations
- Live digital clock display

## Requirements

- XAMPP (Apache + PHP)
- Google Maps API Key

## Installation

1. **Clone the repository**
   ```sh
   git clone https://github.com/john03690248/ubike-rental-inquiry-system.git
   ```

2. **Move the project to XAMPP directory**
   ：Place the `ubike-rental-inquiry-system` folder into the `htdocs` directory of XAMPP:
   ```sh
   mv ubike-rental-inquiry-system /xampp/htdocs/
   ```

3. **Set up Google Maps API Key**
   ：Open `index.html`, find the following line, and replace `YOUR_GOOGLE_MAPS_API_KEY` with your actual API key:
   ```html
   <script async defer src="https://maps.googleapis.com/maps/api/js?key=YOUR_GOOGLE_MAPS_API_KEY&callback=initMap"></script>
   ```

4. **Start XAMPP**
   ：Open the XAMPP control panel and start the Apache server.

5. **Access the website**
   ：Open your browser and go to:
   ```
   http://localhost/ubike-rental-inquiry-system/index.html
   ```

## Data Sources

- [New Taipei City YouBike Open Data](https://data.gov.tw/)
- [Google Maps API](https://developers.google.com/maps/documentation/javascript)
- [Highcharts](https://www.highcharts.com/)
