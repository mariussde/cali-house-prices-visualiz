# California Housing Data Visualization

This project visualizes the California housing dataset on an interactive map using Python libraries such as `folium`, `pandas`, and `matplotlib`. The map shows various housing statistics, including median house values, average rooms, population, and median income.

## Features

- Interactive map with circle markers representing different regions in California.
- Circle size represents the average number of rooms in a region.
- Circle color represents the median house value, with a gradient color scale from green (lower values) to red (higher values).
- Popups displaying detailed information about each region, including median house value, average rooms, population, and median income.
- A mini-map for easier navigation.

## Installation

To run this project, you need to have Python installed along with the required libraries. Follow the steps below to set up the environment:

1. **Clone the repository** (if hosted on a version control system):

   ```bash
   git clone https://github.com/yourusername/california-housing-visualization.git
   cd california-housing-visualization
   ```

2. **Install the required Python libraries**:

   You can install the necessary libraries using pip. Open a terminal or command prompt and run:

   ```bash
   pip install pandas matplotlib scikit-learn folium
   ```

## Usage

1. **Run the Script**:

   Open the terminal or command prompt in the directory where the script is located and run:

   ```bash
   python create_map.py
   ```

2. **View the Map**:

   The script will generate an HTML file named `california_housing.html` in the current working directory. Open this file in a web browser to view the interactive map.

## How It Works

- The script uses the California housing dataset from `sklearn.datasets`.
- It initializes a folium map centered on California.
- Circle markers are added for each data point, with size and color representing different housing attributes.
- A mini-map plugin is added for enhanced navigation.

## Customization

You can customize various aspects of the map:

- **Change Color and Size Parameters**: Modify the color gradient and size scaling in the script to suit your needs.
- **Add Additional Data**: Include more data attributes in the popups or adjust the visualization logic.

## License

This project is open-source and available under the MIT License.

## Acknowledgements

- The data used in this project is provided by the [California Housing dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html).
- This project uses the [folium](https://python-visualization.github.io/folium/) library for interactive mapping.
