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

<br>

## What’s Inside?

### Matplotlib (`*_plt.ipynb`)

| Category | Plot Types |
|----------|------------|
| **Basic** | Line, bar (vertical/horizontal/stacked/grouped), pie, scatter |
| **Statistical** | Histogram, KDE (via `np.histogram`), boxplot, violin (via `mpl_toolkits`) |
| **Advanced** | Donut, stack‑plot, twin axes, polar plots, 3‑D surfaces |
| **Layout & Styling** | `plt.subplots`, `GridSpec`, custom `rcParams`, color cycles, annotations, text boxes, legends |
| **Export** | Saving figures in high‑resolution PNG/PDF, transparent backgrounds, tight layout |

### Seaborn (`*_sns.ipynb`)

| Category | Plot Types |
|----------|------------|
| **Relational** | `scatterplot`, `lineplot`, `regplot`, `lmplot` |
| **Distribution** | `histplot`, `kdeplot`, `boxplot`, `violinplot` |
| **Categorical** | `barplot`, `countplot`, `stripplot`, `swarmplot` |
| **Multivariate** | `pairplot`, `jointplot`, `heatmap`, `pairgrid` |
| **Faceting** | `FacetGrid`, `catplot`, `pairplot` with hue/style/size |
| **Styling** | Themes (`darkgrid`, `whitegrid`, `ticks`), palettes, context scaling |

### Project Showcases

| Project | Goal | Key Visualisations |
|---------|------|-------------------|
| **Project 01 – Coffee Production Analysis** | Explore global coffee production (1990‑2018) | Bar charts, line charts, stacked area, pie charts |
| **Project 02 – Brazil Coffee Dashboard** | Show Brazil’s rise as coffee leader | GridSpec dashboard with text, pie, stacked plots, custom annotations |
| **Project 03 – Used‑Car Price EDA** | Analyse factors affecting car resale price | Pair‑plot, heatmap, regression plots, categorical bar/box plots |
<br>
<br>

## Project Showcases

Explore end-to-end data analysis projects that apply these visualization techniques to real-world datasets.

### Project 1: Coffee Production Analysis
An exploratory analysis of global coffee production trends from 1990-2018. This project uses `matplotlib` to create bar charts, line charts, stack plots, and pie charts to uncover insights into top-producing nations.

### Project 2: Brazil's Coffee Dominance Dashboard
A dashboard-style visualization created with `GridSpec` that tells the story of Brazil's growing dominance in the global coffee market. It combines text, pie charts, and a stack plot into a single, cohesive graphic.

### Project 3: Used Car Price Exploration
An in-depth Exploratory Data Analysis (EDA) of a used car dataset. This project leverages `seaborn`'s statistical plotting capabilities (`pairplot`, `heatmap`, `lmplot`, `barplot`) to investigate the relationships between vehicle attributes like make, condition, and odometer reading, and their final selling price.

<br>

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

```

## Contributing

Contributions are welcome! Feel free to:

- Add new notebooks that cover missing plot types or advanced techniques.
- Improve existing notebooks (add comments, refactor code, fix bugs).
- Submit pull requests with new visualisation projects or data‑driven case studies.

Please follow the usual GitHub workflow:

1. Fork the repo.
2. Create a feature branch (`git checkout -b my-feature`).
3. Commit your changes (`git commit -am "Add XYZ plot"`).
4. Push and open a Pull Request.
---

*Happy plotting! 🎨*
