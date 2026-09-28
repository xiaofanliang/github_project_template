# Data

Datasets used in the project.

## Structure

- `raw/` — data exactly as obtained from its original source, unmodified. Never hand-edit these files; if something's wrong, fix it in re-download instructions instead.
- `processed/` — cleaned or derived data produced by the scripts in `code/` (e.g., the output of `01_clean_data.py`). These files should be fully reproducible by re-running the code, so it's fine if they need to be regenerated.

## What to include

- Files you're allowed to redistribute and that are small enough for GitHub (well under its 100MB hard limit — ideally under a few MB).
- An entry in the Data table in the root `README.md` for every dataset, including any you *can't* commit directly.

## What NOT to commit

- **DLBA data, or any other restricted/licensed data you accessed under a data use agreement.** This repo is public — do not upload it here. Describe the dataset (what it is, why you used it, how to request access) in the Data table in the root `README.md` instead of committing the file.
- Large files. Use Git LFS, or link to where the data can be downloaded instead.
- Any other data you don't have redistribution rights to. Document how to request access in the root README instead.
- Personally identifiable information (PII).

Only public data, or data your team scraped/collected/created yourselves, should actually be committed here.

## Example files

`raw/sample_parcels.csv` and `processed/sample_parcels_clean.csv` are placeholders showing the expected raw → processed pattern (matched to `code/01_clean_data.py`). Delete them and replace with your own data.
