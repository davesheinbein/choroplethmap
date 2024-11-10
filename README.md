# Visualize Data with a Choropleth Map

This project visualizes the educational attainment of U.S. adults aged 25 and older, specifically highlighting the percentage with a bachelor's degree or higher from 2010-2014. The choropleth map dynamically displays each county’s educational statistics, making it easy to compare educational attainment across regions.

## Live Demo

You can view and interact with the project on [CodePen](https://codepen.io/dsDeveloper/pen/oNKwaeN) 

## Features

- **Interactive Map**: Displays each U.S. county color-coded based on educational attainment, with tooltips for additional details on hover.
- **Dynamic Tooltips**: Hovering over a county reveals detailed information about its educational attainment percentage.
- **Legend**: A color-coded legend provides context for the choropleth shading, showing percentage ranges for different color bands.
- **Loading Spinner**: A spinner displays while the data is loading, enhancing the user experience.
- **Responsive Layout**: The map container and tooltip are designed for optimal viewing on different screen sizes.

## Technology Stack

- **D3.js**: For creating the SVG map elements and scaling data to the color spectrum.
- **TopoJSON**: Converts geographical data to JSON for mapping.
- **CSS**: Styled for a modern, gradient-background UI with tooltip and map container effects.
- **HTML**: Simple HTML structure including header, description, and SVG container.

## Files

- **index.html**: Defines the map container, tooltip, loading spinner, and references the D3 and TopoJSON libraries.
- **style.css**: Adds styles for the map, including the background gradient, tooltip, legend, and loading spinner.
- **script.babel**: Contains JavaScript for fetching and visualizing county and education data. It builds the map, calculates color scales, and handles tooltip interaction.

## Installation

To use this project locally:

1. Clone this repository.
2. Open `index.html` in a web browser.
3. Ensure an internet connection to access the D3 and TopoJSON libraries.

## Usage

- Hover over any county to see its name, state, and percentage of adults with a bachelor's degree or higher.
- Refer to the color-coded legend to understand the shading and educational attainment distribution.

## License

A [Pen](https://codepen.io/dsDeveloper/pen/oNKwaeN) by [DsDev](https://codepen.io/dsDeveloper) on [CodePen](https://codepen.io).

[License](https://codepen.io/license/pen/oNKwaeN).
