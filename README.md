# HFrEF GDMT dynamics: time-varying Cox model dashboard

Interactive results browser and hazard-ratio explorer accompanying the study
*Dynamics of guideline-directed medical therapy dosing and cardiorenal function in newly
diagnosed heart failure with reduced ejection fraction: a time-varying Cox analysis of 648 patients*.

**Live page:** see the GitHub Pages link in the repository sidebar.

The page is a single self-contained HTML file (`index.html`). It displays aggregate results
only: model coefficients and their covariance matrix, monthly treatment prevalence,
treatment-episode percentages, penalized-spline dose-response curves, Kaplan-Meier and
landmark concordance. It contains no patient-level record.

- Archived version, R Shiny source code and aggregate model data: https://doi.org/10.5281/zenodo.24198035
- Data source: National Taiwan University Hospital integrated Medical Database (NTUH-iMD);
  patient-level data cannot be shared under the governing data-use approval.
- The risk explorer reports a hazard ratio against a reference profile at one instant. It is
  for teaching and exploration and is not a prognostic calculator.

Corresponding author: Wan-Tseng Hsu, Graduate Institute of Clinical Pharmacy, School of Pharmacy,
College of Medicine, National Taiwan University.

Licence: CC BY 4.0.
