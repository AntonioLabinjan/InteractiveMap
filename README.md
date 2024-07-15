# Interactive Map with Distance Calculation

Welcome to the **Interactive Map with Distance Calculation** project! This web application allows users to search for places, add markers, select two specific locations, and calculate the distance between them. Built using Leaflet.js, it offers a simple yet powerful way to explore geographical data and measure distances.

## Features

- **Search for Places**: Use the search bar to find and add locations to the map.
- **Add Markers**: Click on search results to add draggable markers to the map.
- **Select Locations**: Choose two locations from the list to calculate the distance between them.
- **Distance Calculation**: Easily calculate and display the distance between two selected locations in kilometers.


## Getting Started

### Prerequisites

- A modern web browser
- Internet connection (for loading map tiles and geocoding)

### Installation

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/your-username/interactive-map.git
    ```
2. Navigate to the project directory:
    ```bash
    cd interactive-map
    ```
3. Open `index.html` in your web browser to view the application.

## Usage

1. **Search for Places**: Enter a location in the search bar and click the "Search" button.
2. **Add Markers**: Click on the search results to add markers to the map. Each marker is draggable for fine-tuning its position.
3. **Select Locations**: Click the "Select" button next to two locations in the list to mark them for distance calculation.
4. **Calculate Distance**: Click the "Calculate Distance" button to see the distance between the two selected locations displayed in an alert box.

## Code Structure

- **index.html**: The main HTML file containing the structure of the web page, script with map and CSS styles.

## Dependencies

- [Leaflet.js](https://leafletjs.com/): A powerful, open-source JavaScript library for mobile-friendly interactive maps.
- [Leaflet Control Geocoder](https://github.com/perliedman/leaflet-control-geocoder): A plugin for geocoding control in Leaflet.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork this repository.
2. Create a new branch with your feature or bug fix:
    ```bash
    git checkout -b feature-name
    ```
3. Commit your changes:
    ```bash
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```bash
    git push origin feature-name
    ```
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to the [Leaflet.js](https://leafletjs.com/) community for providing such an amazing library.
- Thanks to the [OpenStreetMap](https://www.openstreetmap.org/) contributors for their invaluable data.
