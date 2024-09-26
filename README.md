# Data Analysis and Visualization Project

## Overview
This project performs data analysis and visualization on datasets provided via URLs, including public Google Drive links. It offers an exploratory data analysis (EDA) that includes generating various charts, graphs, and statistical information.

## Features

### Data Loading
- `carregar_dados`: Downloads CSV files either from Google Drive or a direct URL and loads them into a pandas DataFrame.

### Exploratory Data Analysis (EDA)
- `analise_exploratoria`: Displays the first rows of the dataset, general info, and descriptive statistics. It also generates visualizations of the data.

### Visualizations
The following charts are generated during the analysis:
- **Histogram**: For numerical data.
- **Bar Chart**: For categorical data.
- **Pie Chart**: For categorical data distribution.
- **Line Plot**: For comparing two numerical variables.
- **Scatter Plot**: To show relationships between two numerical variables.
- **Boxplot**: For visualizing the distribution of numerical variables.
- **Correlation Matrix**: For identifying correlations between numerical variables.

### Specialized Analysis
- `analise_especialista`: Allows users to add custom insights and conclusions after performing the exploratory analysis.

## Usage

1. Add your CSV URLs to the `urls` list in the `main` function.
2. Run the program to perform the analysis on each dataset.
3. The code will automatically display data insights and visualizations.

### Example

```python
urls = [
    "https://drive.google.com/file/d/1Yt8X9u62TWW-dkH4Kn-XYo4LegUcX_Ix/view?usp=sharing"
]
main(urls)
