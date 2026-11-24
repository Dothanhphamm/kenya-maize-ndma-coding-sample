# Kenya maize prices and weather: NDMA coding sample

Full reproducibility package for a Kenya maize-market study linking rainfall and temperature anomalies in maize-supplying regions to monthly retail maize-price inflation and volatility.

## Package

- `kenya-maize-ndma-coding-sample.zip` — the complete November 16, 2026 project archive.
- `PROJECT_STRUCTURE.md` — guide to the archive's code, outputs, and data.

The archive contains 95 files organized into Python, Stata, and ArcGIS workflows, exported figures and tables, observed NDMA panels, weather exposures, geography, source records, and audit materials.

## Research design

The package covers a 2008–2014 NDMA market panel with 1,932 market-month records and 1,930 observed prices. It estimates conditional associations between crop-phase weather exposures and retail price inflation and volatility. The package documents the catchment crosswalk, weather construction, fixed-effects specifications, CHIRPS rainfall checks, matched-sample and dynamic models, and source audits.

## Reproduction

Extract the archive and follow its internal `README.md`. The main workflow uses Python 3.12 and Stata 18 or later. ArcGIS Pro is required only for rebuilding the map layouts.

## Interpretation

The estimates are conditional associations, not causal effects. Historical shipment shares are unavailable, supplier exposure is approximated with documented routes and crop-area weights, and adjacent volatility windows share observations.

## Data and attribution

The archive includes source records and derived analysis data. Please retain the source citations and attribution instructions in the internal README when reusing the package.
