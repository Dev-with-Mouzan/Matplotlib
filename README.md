<div align="center">

<img src="assets/matplotlib-logo.svg" alt="Matplotlib" width="220">

# Data Visualization with Matplotlib

*A hands-on collection of Jupyter notebooks for mastering data visualization with [Matplotlib](https://matplotlib.org/)*

![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-11557C?style=for-the-badge)
![pandas](https://img.shields.io/badge/pandas-2.x-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-brightgreen?style=for-the-badge)

</div>

---

## About

This repository is a practical, notebook-driven guide to **data visualization with Matplotlib**. Each plot type lives in its own folder, paired with a `usages.ipynb` notebook that explains **when** to reach for that chart so you learn not just *how* to draw a plot, but *why* you would choose it.

## Features

- **Plot-focused folders** — one folder per plot type, each fully self-contained.
- **When-to-use guidance** — every folder ships a `usages.ipynb` with 2–3 real-world use cases.
- **Real dataset** — examples are built on the World Happiness Report (`Data/Data.csv`).
- **Beginner friendly** — notebooks are simple, runnable step-by-step, and easy to remix.

## Tech Stack

<div align="center">

<img src="https://cdn.simpleicons.org/python/3776AB" alt="Python" width="36" height="36" title="Python">
<img src="https://cdn.simpleicons.org/pandas/150458" alt="pandas" width="36" height="36" title="pandas">
<img src="https://cdn.simpleicons.org/jupyter/F37626" alt="Jupyter" width="36" height="36" title="Jupyter">
<img src="assets/icons/matplotlib.svg" alt="Matplotlib" width="36" height="36" title="Matplotlib">

</div>

| Tool | Purpose |
| ---- | ------- |
| [Python](https://www.python.org/) | Core programming language |
| [Matplotlib](https://matplotlib.org/) | 2D plotting and visualization |
| [pandas](https://pandas.pydata.org/) | Data loading and manipulation |
| [Jupyter Notebook](https://jupyter.org/) | Interactive development environment |

## Project Structure

```
Matplotlib/
├── Data/
│   └── Data.csv                    # World Happiness Report dataset
├── Bar_plot/
│   ├── Bar_plot.ipynb              # bar chart example
│   └── usages.ipynb                # when to use bar charts
├── Box_plot/
│   ├── Box_plot.ipynb              # box plot example
│   └── usages.ipynb
├── Fill_Between_plot/
│   ├── Fill_Between_plot.ipynb     # fill_between example
│   └── usages.ipynb
├── Histogram/
│   ├── Histogram.ipynb             # histogram example
│   └── usages.ipynb
├── pie_plot/
│   ├── pie_plot.ipynb              # pie chart example
│   └── usages.ipynb
├── Save_figure/
|   ├── HistoGram_plot.png          # sample output image
│   ├── Save_figure.ipynb           # exporting figures
│   └── usages.ipynb
├── Scatter_plot/
│   ├── Scatter_plot.ipynb          # scatter plot example
│   └── usages.ipynb
├── stem_plot/
│   ├── stem_plot.ipynb             # stem plot example
│   └── usages.ipynb
├── Step_plot/
│   ├── Step_plot.ipynb             # step plot example
│   └── usages.ipynb
├── assets/
│   ├── matplotlib-logo.svg         # project logo
│   └── icons/
│       └── matplotlib.svg          # Matplotlib icon
├── README.md
└── requirement.txt
```

## Plot Types at a Glance

| Folder | Plot | Typical use |
| --- | --- | --- |
| `Bar_plot/` | Bar charts | Comparing categorical data (e.g., sales by product). |
| `Box_plot/` | Box plots | Statistical summaries and detecting outliers. |
| `Fill_Between_plot/` | `fill_between` | Highlighting regions like confidence intervals. |
| `Histogram/` | Histograms | Understanding the frequency distribution of a dataset. |
| `pie_plot/` | Pie charts | Showing proportional parts of a whole (use with caution). |
| `Save_figure/` | Saving figures | Exporting high-quality plots for reports. |
| `Scatter_plot/` | Scatter plots | Relationships or correlations between two numerical variables. |
| `stem_plot/` | Stem plots | Visualizing discrete data points (signal processing). |
| `Step_plot/` | Step plots | Time-series data where changes occur at discrete intervals. |

## Prerequisites & Installation

Ensure you have the following installed:

- Python 3.8+
- Jupyter Notebook

Install the required libraries using the commands in [`requirement.txt`](requirement.txt):

```bash
pip install -r requirement.txt
```

or simply:

```bash
pip install pandas matplotlib
```

## Usage

1. Clone or download the repository.
2. Navigate to the project folder.
3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open any plot folder (e.g., `Bar_plot/`) and run its notebook. Each folder's `usages.ipynb` explains when that plot type is best applied.

## Contributing

Contributions are welcome. Feel free to open an [issue](https://github.com/) or submit a pull request — adding a new plot type folder or improving an existing notebook is a great way to contribute.
