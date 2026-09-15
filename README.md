# Hospital Patient Recovery Analytics — Snowflake Project

CSV-driven Snowflake hospital analytics project covering ETL, a star-schema warehouse, OLAP queries, data-mining patterns, and visual reporting.

## Contents

- `data/patients.csv` — synthetic patient-admission source data
- `sql/` — Snowflake setup, ETL, warehouse, OLAP, and mining scripts
- `python/run_pipeline.py` — local preprocessing, dimensional extracts, audit log, and charts

## Run

1. Install dependencies: `python -m pip install -r requirements.txt`
2. Run local pipeline: `python python/run_pipeline.py`
3. In Snowflake, run SQL scripts in numeric order after uploading `data/patients.csv` to `PATIENTS_STAGE`.

The source data is synthetic and should not be replaced with real clinical records without approved privacy, security, and governance controls.
