# MA2003B_Blank

This is an R project initialized with renv for dependency management.

## Project structure

- `R/` — functions, internal packages
- `data/` — raw input data
- `output/` — results, reports, figures
- `scripts/` — main analysis scripts
- `quarto/` — reproducible Quarto reports

## renv

To activate the environment:

```R
renv::activate()
```

## Quarto

Put your .qmd files inside `quarto/`.

To render reports:

```bash
quarto render quarto/
```
