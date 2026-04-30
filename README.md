# ror-fundref-data

Mapping data between ROR (Research Organization Registry) and FundRef identifiers, extracted from the ROR dataset and kept up to date via an automated GitHub Actions workflow. 

## Data

The `data/ror_fundref.csv` file contains mappings between ROR identifiers and FundRef identifiers, extracted from the ROR dataset which is published under CC0 (public domain):                                                                                                                 - ROR data: https://ror.org/about/

## Sync workflow

The GitHub Actions workflow runs every Monday and automatically updates the mapping data from the latest ROR release.
