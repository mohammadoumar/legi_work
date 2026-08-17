# legi_work

Exploration of US legislative bill data (119th Congress, 2025-2026), sourced from LegiScan.

## Structure

- `datasets/` — raw CSV/JSON bill data (gitignored, not tracked in this repo)
- `work/` — notebooks for exploring and analyzing the data
  - `dataset_explore.ipynb` — loads `bills.csv` and inspects bill records (id, status, title, description, actions, etc.)

## Setup

Data is not included in the repo. Place the extracted dataset under `datasets/` matching the paths referenced in the notebooks before running them.
