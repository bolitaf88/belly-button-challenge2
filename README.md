# belly-button-challenge2


# Interactive Web Visualizations with Plotly and D3.js

## Overview

This codebase contains a web application designed to visualize and explore data related to a "belly button challenge." The application utilizes Plotly.js and D3.js libraries to create interactive visualizations based on microbial data obtained from belly buttons.

## Features

- **Data Loading**: The application fetches data from an external JSON file hosted on Amazon S3.
- **Dropdown Menu**: A dropdown menu is populated with available names from the dataset, allowing users to select different individuals' data for visualization.
- **Charts**:
  - **Bar Chart**: Displays microbial sample data in a horizontal bar chart.
  - **Bubble Chart**: Represents microbial sample data in a bubble chart format.
- **Demographic Information**: Displays demographic details corresponding to the selected individual.
- **Chart Updates**: On selection change, the charts and demographic information update dynamically to show data specific to the chosen individual.
- **Gauge**: Initializes a gauge chart representing demographic characteristics.

## Code Structure

- **Initialization**:
  - `initApp`: Loads data and initializes the application. Runs the specified callback function upon data load completion.
  - `init`: Initializes HTML elements and charts.
- **Data Handling**:
  - `getDemographic`: Retrieves demographic information based on the selected individual.
  - `getSample`: Retrieves the microbial sample data for the selected individual.
- **Dropdown and Dashboard Update**:
  - `populateDropdown`: Populates the dropdown menu with available names.
  - `updateDashboard`: Updates the dashboard elements upon dropdown selection change.
- **Chart Updates**:
  - `updateBarChart`: Updates the bar chart based on the selected individual's data.
  - `updateBubbleChart`: Updates the bubble chart based on the selected individual's data.
- **Other Functions**:
  - `updateDemographicInfo`: Updates and displays demographic information.
  - `prepBarData`: Prepares data for the bar chart display.
    ![Visual](https://github.com/bolitaf88/belly-button-challenge2/blob/main/images/belly_button1.png)

## Usage

To use this application:
1. Clone or download this repository.
2. Open the `index.html` file in a web browser.
3. Explore the dropdown menu to visualize different individuals' data.

## Data Source

The data used in this application is sourced from an external JSON file hosted on Amazon S3.

## References 
1. Jay Hastings - https://github.com/jayhjman
2. Sunday Akiyesi - https://github.com/Sundakiy
3. Justin Bisal - Course instructor
4. James Newman - Course Intructor
5. AskBCS course Assistant.
