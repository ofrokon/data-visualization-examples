# Data Visualization Examples

This repository contains Python scripts demonstrating various data visualization techniques using matplotlib and seaborn libraries. It accompanies the Medium post "The Art of Data Visualization: Telling Stories with Your Data".

## Table of Contents
1. [Installation](#installation)
2. [Usage](#usage)
3. [Visualizations](#visualizations)
4. [Contributing](#contributing)
5. [License](#license)

## Installation

To run these scripts, you need Python 3.6 or later. Follow these steps to set up your environment:

1. Clone this repository:
   ```
   git clone https://github.com/ofrokon/data-visualization-examples.git
   cd data-visualization-examples
   ```

2. (Optional) Create and activate a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage

To generate all visualizations, run:

```
python create_visualizations.py
```

This will create PNG files for each visualization in the current directory.

## Visualizations

This script generates the following visualizations:

1. `bar_chart.png`: A simple bar chart comparing values across categories.
2. `line_chart.png`: A line chart showing sine and cosine functions.
3. `scatter_plot.png`: A scatter plot demonstrating the relationship between two variables.
4. `heatmap.png`: A heatmap visualizing a 2D array of data.
5. `box_plot.png`: A box plot showing the distribution of data across different groups.

## Contributing

Contributions to this project are welcome! Please fork the repository and submit a pull request with your suggested changes.

## License

This project is open source and available under the [MIT License](LICENSE).

---

For more information on data visualization techniques and best practices, check out the accompanying Medium post: [The Art of Data Visualization: Telling Stories with Your Data](https://medium.com/@mroko001/the-art-of-data-visualization-telling-stories-with-your-data-1f77e180449e)

For questions or feedback, please open an issue in this repository.
