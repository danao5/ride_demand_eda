# NYC Taxi Mobility Demand Analysis & Forecasting

Self-directed analysis of NYC Yellow Taxi mobility demand using a 4M+ row trip dataset.

## Project scope

- Built a data preparation pipeline for trip-level taxi data.
- Engineered temporal, trip, fare, and location features.
- Developed regression models for trip-duration prediction.
- Forecast hourly ride demand.
- Investigated root causes and limitations of model performance.

## Repository contents

- `notebooks/mobility_eda.ipynb` - exploratory analysis and modeling workflow.
- `notebooks/latest_mobility_eda.ipynb` - latest consolidated workflow and outputs.
- `images/` - exported charts used to communicate findings.

## Data setup

The raw and cleaned Parquet datasets are intentionally excluded from Git because they are large generated artifacts. Place the following files in `data/` before running the notebooks:

- `yellow_tripdata_2026-05.parquet`
- `yellow_taxi_cleaned.parquet`

The notebooks use the May 2026 NYC Yellow Taxi trip data and require Python packages that support pandas, Parquet, plotting, and scikit-learn workflows.