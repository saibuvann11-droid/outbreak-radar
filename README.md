# Outbreak Radar

Early warning for disease outbreaks in Indian districts.

India's IDSP publishes weekly outbreak reports only as PDFs. This project turns them
into a clean open dataset, joins district weather, and forecasts outbreak risk per
district and disease 2–4 weeks ahead, shown on a map with the reasons behind each alert.

**Status:** work in progress.

## Layout
- `data/raw/` – original IDSP PDFs, never edited
- `data/interim/` – extracted but not yet cleaned
- `data/processed/` – final clean dataset
- `src/outbreak_radar/` – pipeline code
- `notebooks/` – exploration only
- `tests/` – tests
- `reports/` – figures and write-up
