# Project Title

## Getting Started with This Template

Click the green **Use this template** button at the top of this repo (not "Fork") to create your own copy or by git cloning the folder to your local folder. Don't push to edit this template repo directly.

> This repository documents your academic course project. It should allow another student, researcher, or practitioner to understand your methods and reproduce the shareable portions of your analysis without talking to you directly.

## Project Overview

**Team:** [Names] 

**External project context provided by:** Detroit Land Bank Authority

**Course:** Fall 2026, URP 535/UT 435/SI 536 – Introduction to Urban Informatics, University of Michigan

In 1–2 paragraphs:

- What planning question does this project investigate?
- Why does the question matter?
- What did you build/analyze?

[This can double as your project abstract — a short, plain-language summary that stands on its own for a reader who won't open the code.]

## Key Results

Summarize the major findings or outputs of the project.

[Optionally, include 1–2 key maps, figures, or screenshots here. You can link to `report/figures/`.]

## Data


| Dataset                                             | Source Link                             | Description                                                                           | Access                                                                                |
| --------------------------------------------------- | --------------------------------------- | ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| DLBA Parcel Inventory                               | [www.google.com](http://www.google.com) | Parcel-level ownership, land use, and structure condition for DLBA-managed properties | Restricted — available under a DLBA data use agreement; **not included in this repo** |
| American Community Survey (5-Year Estimates)        | [www.google.com](http://www.google.com) | Tract-level demographic and housing indicators                                        | Public — downloaded via Census API                                                    |
| City of Detroit Open Data Portal – Building Permits | [www.google.com](http://www.google.com) | Permit applications and status by parcel                                              | Public — CSV download                                                                 |
| Team site survey                                    | [www.google.com](http://www.google.com) | Field observations of vacant lot conditions, collected by the team                    | Created by team — included in `data/raw/`                                             |


**Do not upload DLBA (or other restricted/licensed) data to this public repository.** Only commit data that is publicly available or that your team scraped/collected/created yourselves. For any restricted dataset, describe it in the table above (source, description, how to request access) instead of committing the file — see `data/README.md` for details. The data table above is just an example. 

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
  - `figures/` — figures in your report.
  - `final_report.pdf` — the full final write-up (a link to GitHub repo, a link to interactive prototype if any, background, research questions/project goals, methods, results, limitations, reflection and discussion with readings) that you submit to Canvas.
- `docs/` (only if your project includes a web map or interactive prototype) — see "Web Map / Prototype" below.



## Web Map / Prototype (optional)

If your project includes an interactive web map or prototype, put `index.html` at the top level of a `docs/` folder, along with its `css/`, `js/`, and any data files it loads (e.g., GeoJSON) — not nested inside `code/` or `report/`. Keep all file paths relative so the map works both locally and once published. GitHub Pages can only serve a site from the repository root or a `/docs` folder on the default branch (not an arbitrary subfolder), so `docs/` is the one to use. To publish it: go to the repo's **Settings → Pages**, under "Build and deployment" choose "Deploy from a branch," pick `main` as the branch and `/docs` as the folder, then save — GitHub will publish the site at `https://<username>.github.io/<repo-name>/` within a few minutes.

## Reproducing the Analysis

A few sentences about how others can reproduce the analysis, such as what environment to setup (it is a good happen to set up requirement.txt so others can download the same versions of packages you used for your analysis), how to obtain the data from GitHub, and how to run the analysis (e.g., Scripts should be run in numerical order where applicable.)

## Limitations

Describe important limitations in the data, methods, and interpretation.

## Course Context

This repository documents an academic course project completed for URP 535/UT 435/SI 536 – Introduction to Urban Informatics at the University of Michigan. The project uses a real-world planning question as a learning context for practicing data and computational methods. It should not be interpreted as professional work performed for or on behalf of the external organization, or as a production-ready product.

## Acknowledgments

We thank Detroit Land Bank for providing project context, data, and practitioner perspectives.