# Netflix Titles: Exploratory Analysis

A beginner-friendly exploration of a static Netflix titles dataset with **8,807 records**. The notebook looks at the mix of movies and TV shows, content ratings, country metadata, and years titles were added.

## Files

- `Netflix Data.ipynb` — analysis notebook with data checks, charts, and takeaways.
- `netflix_titles.csv` — dataset used by the notebook.

## Selected findings

- Movies account for **6,131 titles (69.6%)**; TV shows account for **2,676 (30.4%)**.
- **TV-MA** is the most common rating (3,207 records), followed by **TV-14** (2,160).
- The United States appears most often in country metadata (3,689 title-country entries), followed by India (1,046) and the United Kingdom (804). A title can list multiple countries, so these counts are not unique-title totals.
- Some metadata is missing, especially director, cast, and country. The notebook fills selected text fields with `Unknown` for analysis.

## Run

Open the notebook in Jupyter and run the cells from top to bottom. The loader works when Jupyter starts in this folder or from the repository root. The notebook uses `pandas`, `numpy`, and `matplotlib`.

## Limitations

This is a static catalog snapshot, not live Netflix data. The analysis describes the records in this file and does not measure viewership, quality, or current availability.
