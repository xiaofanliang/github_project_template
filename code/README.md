# Code

Scripts and notebooks that reproduce the analysis end-to-end — either `.py` scripts or `.ipynb` notebooks, whichever fits the stage better.

## Conventions

- Numbering is a suggestion for typical pipeline order (clean → analyze → visualize), not a requirement — merge stages into fewer files or notebooks if that fits your workflow better. If you do keep multiple files, prefix each with a two-digit number for the order it should run in (e.g., `01_clean_data.py`, `02_analyze.py`) and run them in that order.
- Each stage reads from `../data/raw/` or `../data/processed/` and, if it produces data, writes back to `../data/processed/` — never overwrite `raw/`.
- List dependencies in `requirements.txt` (or an `environment.yml` if you use conda) so anyone can recreate your environment. See the root README's "Set up the environment" section.

## Example files

`01_clean_data.py`, `02_analyze.py`, and `03_visualize.py` are placeholders showing one possible split (cleaning, analysis, visualization). Delete them and replace with your own code — as one file, a notebook, or several, whatever fits.
