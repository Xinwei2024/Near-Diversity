# Lexical Diversity Replication

## Usage

1. Extract the ZIP archive.
2. Copy `prefix_profiles.csv` into the `LD_replication/data/` folder.
3. Keep the original folder structure unchanged.
4. Open RStudio and run:

```r
source(file.choose(), encoding = "UTF-8")  # Select replicate.R
run_all()
```

The script automatically loads the data, reproduces the statistical analyses, and generates Figures 2 and 3.

## Output

- `results/`: Statistical results (CSV files).
- `results/figures/`: Figures (300-dpi PNG files).

**Requirements:** Base R only. No additional packages or working-directory changes are required.
