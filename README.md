# Exploratory Data Analysis & Visualization with Python

A data analysis project exploring two datasets using Python, Pandas, NumPy, Seaborn, and Matplotlib. The project focuses on data preparation, descriptive statistics, exploratory data analysis, and visualizing relationships between numerical and categorical variables.

## Project Overview

This repository contains two Jupyter notebooks demonstrating exploratory data analysis and visualization techniques on different datasets:

* **Penguin Dataset Analysis** — explores physical characteristics and categorical attributes across penguin species.
* **Telescope Dataset Analysis** — examines numerical telescope data using statistical analysis and several visualization techniques.

The goal of the project was to practice transforming raw datasets into meaningful statistical summaries and visual representations that make relationships and distributions easier to understand.

## Technologies Used

* Python
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Jupyter Notebook

## Penguin Data Analysis

The `PenguinsDataVisualization.ipynb` notebook explores a dataset containing measurements and characteristics of several penguin species.

The analysis includes:

* Loading and inspecting the dataset with Pandas
* Identifying and removing records containing missing values
* Separating numerical and categorical attributes
* Calculating descriptive statistics including:

  * Mean
  * Median
  * Standard deviation
  * Minimum and maximum values
  * Quartiles
* Examining frequency distributions for categorical variables
* Comparing relationships between numerical measurements
* Creating categorical visualizations
* Generating pair plots
* Calculating correlations between numerical attributes
* Visualizing correlations using a heatmap

The dataset contains attributes such as species, island, bill dimensions, flipper length, body mass, and sex.

## Telescope Data Analysis

The `TelescopeDataVisualization.ipynb` notebook explores numerical telescope measurements and relationships among different attributes.

The analysis includes:

* Loading and preparing telescope data with Pandas
* Working with numerical attributes using NumPy
* Comparing relationships between features
* Creating scatter plots
* Visualizing probability density using kernel density estimation
* Creating pair plots for selected attributes
* Examining statistical relationships between variables
* Comparing different telescope attributes visually

## What I Learned

This project strengthened my understanding of the exploratory data analysis workflow, including how to:

* Clean and prepare datasets before analysis
* Use Pandas to organize and transform structured data
* Apply NumPy for numerical analysis
* Choose visualizations appropriate for different kinds of data
* Identify relationships between variables through plots and correlation analysis
* Use Jupyter Notebook to combine code, analysis, and visual results in a reproducible workflow

## Repository Structure

```text
Pandas-Seaborn-DataVisualization-Assignment/
├── PenguinsDataVisualization.ipynb
├── TelescopeDataVisualization.ipynb
└── README.md
```

## Running the Project

1. Clone this repository.
2. Install the required Python packages:

```bash
pip install pandas numpy seaborn matplotlib jupyter
```

3. Make the required datasets available to the notebooks.
4. Update the dataset paths if necessary.
5. Start Jupyter Notebook:

```bash
jupyter notebook
```

6. Open either notebook and run the cells sequentially.

## Future Improvements

Potential improvements to the project include:

* Moving datasets into a dedicated `data/` directory and using relative file paths
* Adding additional explanatory Markdown throughout the notebooks
* Expanding the analysis with additional statistical techniques
* Improving visualization labels and presentation
* Adding conclusions summarizing the most important findings from each dataset

## Author

**Glenn Fortunato**

Computer Science Graduate — Florida Atlantic University
