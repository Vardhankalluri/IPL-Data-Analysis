# IPL Data Analysis Using Python

A beginner-friendly exploratory data analysis project using Indian Premier League (IPL) match and ball-by-ball data.

## Project goals

- Explore match-level and ball-by-ball IPL data.
- Compare team wins.
- Identify leading run scorers.
- Identify leading wicket-takers.
- Create charts to communicate cricket statistics.

## Tools

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Project structure

```text
IPL-Data-Analysis/
├── data/
│   ├── matches.csv
│   └── deliveries.csv
├── IPL_Analysis.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/Vardhankalluri/IPL-Data-Analysis.git
   cd IPL-Data-Analysis
   ```

2. Create and activate a virtual environment (macOS):

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

3. Install dependencies:

   ```bash
   python3 -m pip install -r requirements.txt
   ```

4. Start Jupyter:

   ```bash
   jupyter notebook
   ```

5. Open `IPL_Analysis.ipynb` and run the notebook cells from top to bottom.

## Data

The notebook expects two CSV files in a local `data/` directory:

- `matches.csv`
- `deliveries.csv`

The datasets are not included in this repository yet. Obtain them from the original dataset source and check its licence and redistribution terms before committing or sharing the CSV files. Keep the filenames and folder structure shown above.

## Current analysis

- Load and inspect match and delivery records.
- Count wins by team.
- Aggregate batter runs.
- Count bowler-credited wickets (excluding dismissals not credited to the bowler).

## Notes

This is a learning project. Validate column names, dismissal rules, season coverage and data quality before treating results as definitive.
