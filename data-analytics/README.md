# Data analytics

A collection of small data analysis projects. Each folder includes a Jupyter notebook and the dataset used in it.

## Projects

### Indian Liver Patient Dataset

[Open the notebook](<indian-liver-patient/Indian Liver Patient Dataset.ipynb>) · [Open the CSV](<indian-liver-patient/Indian Liver Patient Dataset (Raw).csv>)

I explore the 583 patient records by status, age, and gender, then compare a few lab measurements. I also corrected the source file’s misaligned column labels before analyzing it. The results are descriptive and are not for medical use.

### Netflix titles

[Open the notebook](<Netflix data set/Netflix Data.ipynb>) · [Open the dashboard](<Netflix data set/Netflix Catalog Dashboard.html>) · [Open the CSV](<Netflix data set/netflix_titles.csv>)

I compare movies and TV shows, check common ratings and countries, and chart titles by year added. The dashboard gives a quick visual summary, with a filter for movies and TV shows. Open the HTML file in a browser to use it. The 8,807-row file is a snapshot, so it does not represent the current catalog.

## Running the notebooks

Open either notebook in Jupyter and run the cells from top to bottom. The data-loading cells work when Jupyter starts in the project folder or from the repository root. The notebooks use `pandas`, `numpy`, `matplotlib`, and `seaborn`.
