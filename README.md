# Student Attempts Visualisation

A small pandas and Plotly exercise. It groups records by student ID and level, calculates the mean attempt value for each group, and displays a scatter plot.

## Project structure

- `c107/code.py` — loads the dataset, aggregates attempts, and creates the chart.
- `c107/data.csv` — input data.

## Requirements

```bash
pip install pandas plotly
```

## Run

Run from the `c107` directory so the relative CSV path resolves:

```bash
python code.py
```

The chart uses point size and colour to represent the grouped mean attempt value.