 # Data Visualization with Matplotlib

This project contains a collection of Jupyter Notebooks demonstrating how to create various types of plots using the [Matplotlib](https://matplotlib.org/) library in Python. It serves as a practical guide for visualizing data effectively.

## 📋 Prerequisites

Ensure you have the following installed:

- Python 3.x
- Jupyter Notebook
- Pandas
- Matplotlib

You can install the required libraries using the commands found in `requirement.txt.txt` (or simply run):

```bash
pip install pandas matplotlib
```

## 📂 Project Structure

The repository is organized into the following directories:

### `Data/`
Contains the datasets used in the notebooks.
- `Data.csv`: The primary dataset for plotting examples.

### `Notebooks/`
Contains Jupyter Notebooks for different plot types:
- **Bar_plot.ipynb**: Creating bar charts. Useful for comparing categorical data (e.g., sales by product).
- **Box_plot.ipynb**: Visualizing distributions with box plots. Ideal for showing statistical summaries and detecting outliers.
- **Fill_Between_plot.ipynb**: Using `fill_between` to shade areas. Great for highlighting regions like confidence intervals.
- **Histogram.ipynb**: Plotting histograms. data using histograms. Perfect for understanding the frequency distribution of a dataset.
- **Save_figure.ipynb**: Techniques for saving Matplotlib figures. Essential for exporting high-quality plots for reports.
- **Scatter_plot.ipynb**: Creating scatter plots. Best for showing relationships or correlations between two numerical variables.
- **Step_plot.ipynb**: Drawing step plots. Useful for time-series data where changes occur at discrete intervals.
- **pie_plot.ipynb**: Creating pie charts. Good for showing proportional parts of a whole (use with caution).
- **stem_plot.ipynb**: Creating stem plots. common in signal processing to visualize discrete data points.
- **HistoGram_plot.png**: Example output image of a histogram.

## 🚀 Usage

1. Clone or download the repository.
2. Navigate to the folder.
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open any of the notebooks in the `Notebooks/` directory to explore the code and visualizations.
