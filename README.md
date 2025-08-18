# Matplotlib & Seaborn Visualization Demos
![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C9FCC?style=for-the-badge&logo=seaborn&logoColor=white)


This repository is a comprehensive collection of Jupyter Notebooks demonstrating a wide range of data visualization techniques using Python's powerful `matplotlib` and `seaborn` libraries. From fundamental plots to intricate, multi-layered subplots, these examples serve as a practical guide for creating effective and publication-quality visualizations.

## What's Inside

The notebooks are structured to provide parallel examples for both libraries, showcasing their unique strengths and syntax. The repository covers an extensive list of chart types and customization options.

### Matplotlib (`*_plt.ipynb`)
- **Basic Plots:** Line graphs, bar charts (vertical, horizontal, stacked, grouped), pie charts, and scatter plots.
- **Advanced Charting:** Donut charts, stack plots, histograms, and plots with twin axes for different scales.
- **Customization & Layout:**
    - Detailed control over figures, subplots, and layouts using `plt.subplots` and `GridSpec`.
    - Customizing titles, labels, legends, colors, and line styles.
    - Adding annotations, text, and vertical/horizontal lines to highlight key information.
    - Global styling with `plt.style` and `rcParams`.

### Seaborn (`*_sns.ipynb`)
- **Statistical Plots:** Relational plots (`scatterplot`, `lineplot`), distribution plots (`histplot`, `kdeplot`, `boxplot`, `violinplot`), and categorical plots (`barplot`).
- **Advanced Visualizations:**
    - Regression plots (`regplot`, `lmplot`) to visualize linear relationships.
    - `jointplot` and `pairplot` for multivariate analysis.
    - `heatmap` to visualize matrix data, such as correlation matrices.
    - `FacetGrid` for creating grids of plots based on data subsets.

## Project Showcases

Explore end-to-end data analysis projects that apply these visualization techniques to real-world datasets.

### Project 1: Coffee Production Analysis
An exploratory analysis of global coffee production trends from 1990-2018. This project uses `matplotlib` to create bar charts, line charts, stack plots, and pie charts to uncover insights into top-producing nations.

### Project 2: Brazil's Coffee Dominance Dashboard
A dashboard-style visualization created with `GridSpec` that tells the story of Brazil's growing dominance in the global coffee market. It combines text, pie charts, and a stack plot into a single, cohesive graphic.

### Project 3: Used Car Price Exploration
An in-depth Exploratory Data Analysis (EDA) of a used car dataset. This project leverages `seaborn`'s statistical plotting capabilities (`pairplot`, `heatmap`, `lmplot`, `barplot`) to investigate the relationships between vehicle attributes like make, condition, and odometer reading, and their final selling price.

## Getting Started

To run these notebooks on your local machine, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/asutoshananda/python-library-matplotlib-seaborn_demos.git
    cd python-library-matplotlib-seaborn_demos
    ```

2.  **Install the required libraries:**
    ```bash
    pip install pandas numpy matplotlib seaborn openpyxl jupyter
    ```

3.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```

4.  Navigate to the `Matplotlib & Seaborn Coding/` directory to open and run the notebooks.

## Repository Structure

```
.
├── Matplotlib & Seaborn Coding/
│   ├── 01_plt.ipynb      # Matplotlib examples
│   ├── 01_sns.ipynb      # Seaborn examples
│   ├── ...               # More paired examples
│   ├── Project 01.ipynb  # Coffee Production Analysis
│   ├── Project 02.ipynb  # Brazil Coffee Dashboard
│   └── Project 03.ipynb  # Used Car Price EDA
└── Images/
    └── ...               # Saved plot images from notebooks
