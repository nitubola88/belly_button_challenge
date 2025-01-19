
# Belly Button Biodiversity Dashboard

## Overview

This project involves building an interactive dashboard to explore the Belly Button Biodiversity dataset. The dataset catalogs the microbes that colonize human navels, revealing that a few microbial species are present in most people, while others are rare. The dashboard includes visualizations like bar and bubble charts and displays demographic metadata based on the dataset.

## Features

- **Bar Chart**: Displays the top 10 OTUs found in an individual.
- **Bubble Chart**: Shows each sample with `otu_ids` as x-values and `sample_values` as y-values, along with marker sizes and colors.
- **Demographic Metadata**: Displays an individual's demographic information.
- **Dropdown Menu**: Allows users to select different samples to update the charts and metadata dynamically.

## Getting Started

### Prerequisites

- Web browser
- Internet connection
- Basic knowledge of JavaScript, D3.js, and Plotly.js

### Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/belly-button-challenge.git
   ```
2. Navigate to the project directory:
   ```bash
   cd belly-button-challenge
   ```
3. Open `index.html` in your web browser to view the dashboard.

## Visualization Details

### Bar Chart

- **Values**: `sample_values` for the top 10 OTUs
- **Labels**: `otu_ids` for the y-axis
- **Hovertext**: `otu_labels`

### Bubble Chart

- **x-axis**: `otu_ids`
- **y-axis**: `sample_values`
- **Marker Size**: `sample_values`
- **Marker Color**: `otu_ids`
- **Hovertext**: `otu_labels`

### Metadata Panel

Displays demographic information such as `id`, `ethnicity`, `gender`, `age`, `location`, `bbtype`, and `wfreq`.

## Usage

1. Open the deployed site in a web browser.
2. Use the dropdown menu to select a sample.
3. Observe the bar and bubble charts updating to reflect the selected sample's data.
4. View the demographic information in the metadata panel.



