# Template GitHub Repository for EpiPandit Lab
## Quantitative veterinary epidemiology and disease ecology lab
==============================

**This code:** is about the humming birds data records from ( 1991-2016). By applying codes to this data we will find out which birds survive and which doesn't and why. First it shows you the structure of the data, including the rows and the columns, analysis of 5000 birds, the hospital that had the busiest number of birds, the ones survived and the ones died, their admission through the years, graphs, and issues with the code. 

**The main features and functionalities:** installing packages, loading libraries, reading files, structure of file, seed, grouping, summarizing, making graphs, calculating proportions and making graphs. 

**Output the code generates is:** data structure, data column and rows, number survives and number died, addimision rates, tables, proportions, and graphs. Segregating data according to different groups. 



## Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make setup` or `make conda-create`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third-party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. The naming convention is a date (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `03132024-pranav-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── environment.yml   <- The environment file for reproducing the analysis environment, e.g.
    │                         generated with `conda create -f environment.yml`
    │
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to process data
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │
    │   └── visualization  <- Scripts to create exploratory and results-oriented visualizations

--------


## Setup Instructions
------------
1. Clone the repo
2. Create a virtual environment
3. Install the requirements
4. Run the notebooks

```bash
git clone
cd EpiPandit_Template
make conda-create
conda activate EpiPandit_Template
make setup
jupyter notebook
```
<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>.</small></p>
