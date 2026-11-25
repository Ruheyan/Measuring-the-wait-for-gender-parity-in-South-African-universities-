# Measuring the Wait for Gender Parity in South African Universities

## Overview

This repository contains the data, code, and selected outputs associated with the research study Measuring the Wait for Gender Parity in South African Universities.

The study investigates changes in female academic staff representation across 26 South African universities between 2000 and 2023. Using survival analysis, we examine the time taken by universities to first reach or exceed selected representation thresholds and explore differences in the pace of institutional progress.

## Authors

Winnie Nakiyingi, AIMS Research and Innovation Centre, Rwanda

Justine Nasejje, University of the Witwatersrand, South Africa

Anna Kaduma Gumbie, University of the Witwatersrand, South Africa

Rukia Nuermaimaiti, Imperial College London, United Kingdom

Pierre-Philippe Dechant, University of Leeds, United Kingdom

## Data Source

The data were obtained from the [PowerHEDA dashboard](https://www.heda.co.za/PowerHEDA/dashboard.aspx). The initial data extraction was conducted on 11 August 2025, and the dataset was subsequently updated using reports downloaded on 26 November 2026.

The data were extracted from the Permanent Instr/Research Staff Headcount by Institution and Calendar Year report under the Staff Reports section.

The updated dataset contains 581 university-year observations, comprising annual headcounts of female and male permanent instructional and research staff across 26 South African universities from 2000 to 2023. As observation periods vary across institutions, the resulting dataset has an unbalanced panel structure.

Female, male and total staff headcounts were extracted separately to facilitate data validation. Female academic staff representation was calculated as the female headcount divided by the sum of female and male headcounts.

Vista University was excluded to restrict the analysis to the 26 universities operating in 2023. Observations with zero total staff headcounts were also excluded.

The updated dataset resolves previously missing male headcounts for 2006–2011. Three minor discrepancies between the reported total headcounts and the sum of female and male headcounts were identified and retained for transparency. No missing values were imputed.

## Repository Contents

- **Data:** Datasets used in the analysis.
- **Code:** Scripts used for data processing, statistical analysis, and visualisation.
- **Outputs:** Selected results, figures, and tables generated from the analysis.

## Statistical Analysis

The study employs a survival analysis framework to examine:

- Longitudinal changes in female academic staff representation.
- Time to first attainment of selected representation thresholds.
- Kaplan–Meier estimation of time-to-threshold distributions.
- Comparisons between historically disadvantaged institutions (HDIs) and non-HDIs.

Representation thresholds serve as reference points for monitoring institutional progress rather than definitive measures of gender equity.

## Sustainable Development Goals

The research is aligned with the following United Nations Sustainable Development Goals (SDGs):

- SDG 4: Quality Education
- SDG 5: Gender Equality
- SDG 10: Reduced Inequalities

## Reproducibility

The materials in this repository are provided to support research transparency and reproducibility. The repository will be updated as the associated manuscript progresses towards publication.

## Citation

The associated manuscript is currently in preparation. Full citation information will be provided upon publication.

## Acknowledgements

We acknowledge [PowerHEDA](https://www.heda.co.za/PowerHEDA/dashboard.aspx) as the original data source.
