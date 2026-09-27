# Machine Learning Notebook

A personal collection of Jupyter notebooks for learning and experimenting with machine learning. No fixed theme — just whatever model or dataset I'm curious about at the time.

## What's inside

Each notebook is self-contained and explores a different problem, for example:

- `hydration-model.ipynb` — predicting hydration levels from input features
- `movie-success-predictor.ipynb` — predicting whether a movie will do well

More notebooks get added as new ideas come up.

## Structure

```
ml-notebook/
├── README.md
├── requirements.txt
├── notebook-name-1/
│   ├── notebook.ipynb
│   ├── data/            # small/sample data only, or a script to fetch it
│   └── notes.md         # optional: what I learned, what didn't work
├── notebook-name-2/
│   └── ...
└── ...
```

Each experiment lives in its own folder so it can have its own data, notes, and (if needed) dependencies, without cluttering the others. As the repo grows, this keeps things easy to navigate — just look for the folder name matching the topic.

## Conventions

- **Naming:** folders and notebooks use `kebab-case` and a short descriptive name (`hydration-model`, not `notebook3`).
- **Data:** large datasets aren't committed — either a small sample is included or a script/link explains how to fetch the full data.
- **Notes:** each notebook starts with a short markdown cell explaining the goal, and ends with a takeaways/results cell.
- **Dependencies:** shared packages go in the root `requirements.txt`; if a notebook needs something unusual, it's noted at the top of that notebook.

## Setup

```bash
git clone <repo-url>
cd ml-notebook
pip install -r requirements.txt
jupyter notebook
```

## Why this repo exists

This is a scratchpad for learning — trying out models, datasets, and techniques without worrying about production code quality. Some notebooks will be polished, some will be messy experiments. That's fine; the point is to learn.
