# Project Title

> **Using this template:** This repo is your project deliverable — it should let a reader understand *and* reproduce your project without talking to you directly. Replace every `[bracketed]` placeholder below, delete this callout, and swap out the example files in `data/`, `code/`, and `report/` for your own.

**Team:** [Names]
**Partner organization:** Detroit Land Bank
**Course:** Fall 2026, URP 535/UT 435/SI 536 – Introduction to Urban Informatics, University of Michigan

## Project Overview

In 1–2 paragraphs:

- What planning question does this project investigate?
- Why does the question matter?
- What did you build/analyze?

[This can double as your project abstract — a short, plain-language summary that stands on its own for a reader who won't open the code.]

## Key Results

Summarize the major findings or outputs of the project.

[Include 1–2 key maps, figures, or screenshots here. See `report/figures/`.]

## Data


| Dataset                                             | Source Link                             | Description                                                                           | Access                                                                                |
| --------------------------------------------------- | --------------------------------------- | ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| DLBA Parcel Inventory                               | [www.google.com](http://www.google.com) | Parcel-level ownership, land use, and structure condition for DLBA-managed properties | Restricted — available under a DLBA data use agreement; **not included in this repo** |
| American Community Survey (5-Year Estimates)        | [www.google.com](http://www.google.com) | Tract-level demographic and housing indicators                                        | Public — downloaded via Census API                                                    |
| City of Detroit Open Data Portal – Building Permits | [www.google.com](http://www.google.com) | Permit applications and status by parcel                                              | Public — CSV download                                                                 |
| Team site survey                                    | [www.google.com](http://www.google.com) | Field observations of vacant lot conditions, collected by the team                    | Created by team — included in `data/raw/`                                             |


**Do not upload DLBA (or other restricted/licensed) data to this public repository.** Only commit data that is publicly available or that your team scraped/collected/created yourselves. For any restricted dataset, describe it in the table above (source, description, how to request access) instead of committing the file — see `data/README.md` for details.

## Methods and Workflow

Briefly describe the analytical workflow (a few sentences).

Raw Data
   ↓
Data Cleaning / Integration
   ↓
Analysis
   ↓
Visualization / Prototype

See `/code` for the scripts used at each stage.

## Repository Structure

- `data/` — raw and processed datasets. See `[data/README.md](data/README.md)`.
- `code/` — scripts/notebooks that reproduce the analysis. See `[code/README.md](code/README.md)`.
- `report/` — supporting visuals and the final written report:
  - `figures/` — one or two eye-catching images (a key map, chart, or prototype screenshot), referenced from "Key Results" above.
  - `final_report.pdf` — the full final write-up (background, methods, results, limitations, recommendations), for a reader who won't open GitHub at all.
- `docs/` (only if your project includes a web map or interactive prototype) — see "Web Map / Prototype" below.



## Web Map / Prototype (optional)

If your project includes an interactive web map or prototype, put `index.html` at the top level of a `docs/` folder, along with its `css/`, `js/`, and any data files it loads (e.g., GeoJSON) — not nested inside `code/` or `report/`. Keep all file paths relative so the map works both locally and once published. GitHub Pages can only serve a site from the repository root or a `/docs` folder on the default branch (not an arbitrary subfolder), so `docs/` is the one to use. To publish it: go to the repo's **Settings → Pages**, under "Build and deployment" choose "Deploy from a branch," pick `main` as the branch and `/docs` as the folder, then save — GitHub will publish the site at `https://<username>.github.io/<repo-name>/` within a few minutes.

## Reproducing the Analysis



### 1. Set up the environment

...

### 2. Obtain the data

...

### 3. Run the analysis

...

Scripts should be run in numerical order where applicable.

## Limitations

Describe important limitations in the data, methods, and interpretation.

## Course Context

This project was completed as part of URP 535/UT 435/SI 536 – Introduction to Urban Informatics at the University of Michigan. It is an academic course project using a real-world planning question as a learning context.

## Acknowledgments

We thank Detroit Land Bank for providing project context, data, and practitioner perspectives.