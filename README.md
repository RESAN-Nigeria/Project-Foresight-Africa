# Project Foresight Africa

**An open-source AI platform predicting climate-driven malaria surges 
2 to 4 weeks in advance to protect children in Northwest Nigeria.**

Developed by the Resilient Systems Alliance Nigeria (RESAN)
UNICEF Climate Ventures Cohort 2026|MIT License

---
## The Problem

Every August, malaria cases in Northwest Nigeria surge by 20-35% in a 
single month. In August 2022, confirmed cases across Kebbi, Sokoto, and 
Zamfara jumped from 328,048 to 444,200 an increase of 116,152 cases 
in 30 days. Routine DHIS2 surveillance showed zero warning in July.

During this surge, 94.4% of confirmed cases received no ACT treatment 
not because drugs were absent from Nigeria, but because commodity 
pre-positioning requires 2–4 weeks of advance notice that the health 
system did not have.

## The Solution

Project Foresight integrates:
- **DHIS2** malaria case surveillance data (weekly extraction via API)
- **ERA5** rainfall accumulation and temperature anomaly data
- **CHIRPS** precipitation datasets
- **Machine learning** surge prediction model trained on 2022–2024 data

Output: A weekly Transmission Risk Score (TRS) per state and LGA, 
triggering anticipatory alerts to State MOH malaria focal persons 
2–4 weeks before surge onset.

## Validation Evidence

The August surge pattern is reproducible every year:

| Year | July Cases | August Cases | Surge |
|------|-----------|-------------|-------|
| 2022 | 328,048   | 444,200     | +35.4% |
| 2023 | 291,155   | 355,439     | +22.1% |
| 2024 | 272,607   | 326,842     | +19.9% |

July DHIS2 data showed -0.6% MoM in 2022 — no warning signal.
July rainfall accumulation would have flagged the surge 2–4 weeks earlier.

## Study States
- Kebbi State, Nigeria
- Sokoto State, Nigeria  
- Zamfara State, Nigeria

## Principal Investigator
Michael Audu, MPH, MIAD, DrPH(c)
Founder & Director, RESAN
ORCID: 0009-0009-2931-8964

## License
MIT License - see LICENSE file

## Status
Under active development with UNICEF Climate Ventures 2026 support.
Code, models, and notebooks to be published upon award.
