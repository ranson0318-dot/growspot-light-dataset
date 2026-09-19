# GrowSpot light datasets

Three open datasets about indoor light for houseplants, mirrored from [growspotapp.com/data/](https://growspotapp.com/data/). Each file is released under Creative Commons Attribution 4.0, so you can reprint it or build on it, commercially or not, as long as the attribution line travels with the file.

This repository is a mirror. The dataset pages on growspotapp.com are the canonical home, the DOIs point at the newest version, and corrections go in there first.

| File | Rows | Snapshot | Dataset page | DOI |
|---|---|---|---|---|
| [`indoor-light-measurements.csv`](data/indoor-light-measurements.csv) · [`.json`](data/indoor-light-measurements.json) | 4 rows summarising 204 readings | 2026-08-20 (rev 2026-08-28) | [growspotapp.com/data/indoor-light-measurements/](https://growspotapp.com/data/indoor-light-measurements/) | [10.5281/zenodo.22023337](https://doi.org/10.5281/zenodo.22023337) |
| [`species-light-levels.csv`](data/species-light-levels.csv) · [`.json`](data/species-light-levels.json) | one row per species | 2026-09-05 | [growspotapp.com/data/species-light-levels/](https://growspotapp.com/data/species-light-levels/) | [10.5281/zenodo.22023337](https://doi.org/10.5281/zenodo.22023337) |
| [`published-light-figures.csv`](data/published-light-figures.csv) · [`.json`](data/published-light-figures.json) | 562 rows | last changed 2026-09-12 | [growspotapp.com/data/published-light-figures/](https://growspotapp.com/data/published-light-figures/) | [10.5281/zenodo.22172762](https://doi.org/10.5281/zenodo.22172762) |

Every CSV starts with a comment line that repeats its snapshot date, licence and attribution, so the provenance stays with the file when it is copied on its own.

## The three datasets

### Indoor light measurements

What a light meter reads at real spots in real homes. Aggregates only: per-band and per-environment quantiles, never a single household's raw readings.

Notes on what the file does not cover, and the column glossary, live on the dataset page: https://growspotapp.com/data/indoor-light-measurements/

### Species light levels

The light tier for every species in the GrowSpot care library, one row per species, with the lux boundary between one tier and the next written down rather than implied.

Notes on what the file does not cover, and the column glossary, live on the dataset page: https://growspotapp.com/data/species-light-levels/

### What the published sources say about indoor light

Every figure and statement about houseplant light we read while writing the guides, transcribed one at a time with units left exactly as each source writes them. Two rows that contradict each other both stay.

Notes on what the file does not cover, and the column glossary, live on the dataset page: https://growspotapp.com/data/published-light-figures/

## One caveat before reusing the published-figures file

The compilation is ours to license. The quoted sentences in it are not: each remains the property of the publisher named in its row, so keep the `source_url` column with the file when you redistribute it.

## Citation

```
GrowSpot (2026). Indoor light datasets for houseplants. growspotapp.com/data/
  Indoor light measurements: https://doi.org/10.5281/zenodo.22023337
  Species light levels: https://doi.org/10.5281/zenodo.22023337
  What the published sources say about indoor light: https://doi.org/10.5281/zenodo.22172762
```

A machine-readable version is in [CITATION.cff](CITATION.cff).

## Corrections

If a row looks wrong or a column is missing something you needed, open an issue here or write to growspotapp@gmail.com. Corrections go into the next snapshot and the DOI keeps pointing at the newest one.

If you would rather have an answer for one spot than a file to analyse, the [free spot checker](https://growspotapp.com/spot-checker/) runs in the browser.

---

Mirror built 2026-09-19 from the live files at https://growspotapp.com/data/. Licence: [CC BY 4.0](LICENSE).
