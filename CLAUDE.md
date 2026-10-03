# CLAUDE.md

`floodresponsemw` is an openwashdata R data package with water point
assessments from the USAID Flood Response in Malawi (2019-2020),
collected with mWater.

## Package facts

- Raw data: `data-raw/usaid flood response malawi 2019.csv`.
- Processing script: `data-raw/data_processing.R`. It reads the raw data
  and writes `data/floodresponsemw.rda` and the CSV and XLSX exports in
  `inst/extdata/`.
- Data dictionary: `data-raw/dictionary.csv`.
- Branches: work and review PRs go to `dev`; `main` holds released
  versions.

## Reviews and releases

Reviews and releases follow the installed pkgreview skills.
`/review-package` starts a review, `/review-issue` works through one
review issue, `/create-release` makes a release and `/add-doi` adds the
Zenodo DOI. The skills hold the steps and the current standards, so this
file does not repeat them.
