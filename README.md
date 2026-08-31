# Replication Package

This repository hosts the accompanying code to my thesis: **"Creditors’ Influence on Firm Investment Policy: An Empirical Analysis of Debt Covenant Violations"**.

## Abstract
I find that debt covenant violations trigger changes in firms’ investment policies. Investigating non-financial U.S. firms (1997–2009), my results confirm Nini et al. (2012): covenant violations consistently reduce growth in total assets, net PPE, and the CapEx-to-assets ratio within one year post-violation (with smaller effects for one-time violators). R&D expenditures scaled by total assets remain unaffected.

## What the Code Does
* Builds the baseline dataset from raw input files.
* Calculates all summary statistics and in-text numbers.
* Generates all figures and exports automated LaTeX tables.

*Written in R with RScript routines for direct LaTeX export.*

## Data Sources & Notes
The empirical sample combines 44 sub-datasets from three sources:
* **S&P Capital IQ:** 42 firm-level accounting datasets (1996–2009).
* **Compustat:** 1 accounting dataset.
* **Covenant Violations:** 1 dataset from Nini, Smith, and Sufi (2012, *RFS*), downloadable via [Amir Sufi's Website](https://amirsufi.net/data-and-appendices/CSTATVIOLATIONS_NSS_20090701.dta).

*Note: Proprietary data (Capital IQ, Compustat) cannot be shared publicly due to licensing restrictions, but is available upon request.*

