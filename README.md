# Cord blood proteomics identifies biomarkers of early-onset neonatal sepsis
Leena B. Mithal, Mark E. Becker, Ted Ling-Hu, Young Ah Goo, Sebastian Otero, Aspen Kremer, Surya Pandey, Nicola Lancki, Yawei Li, Yuan Luo, William Grobman, Denise Scholtens, Karen K. Mestan, Patrick C. Seed, and Judd F. Hultquist.

# Organization #
This repository stores code & data used in the above manuscript, alongside code outputs.
* `code/`
  * `eos_allfigs_plustables.ipynb` contains all analyses.
* `data/`

  Contains both raw data and derived data (model parameters, demographic summaries). 
  * `leena_proteins_mean2023_nu037fix.csv`: Wide-format batch-adjusted protein abundance per sample, with rows as samples and columns as proteins.
  * `cord_mesoscaledata_12_9_22.csv`: Biomarker protein concentration quantitated by immunoassay.
  * `ps_metadata_cut.csv`: Sample metadata (gestational age, sex, PROM, etc.).
  * `table1_summary.csv`, `table1_pvals_pairwise.csv`: Demographic information and statistics shown in Table 1.
  * `summary_onefeature.csv`, `summary_multifeature.csv`: Logistic model metrics shown in Table 3.
* `extendeddata`

  Contains data underlying each plotted point in each graph to fulfill journal data availability guidelines.

* `graphs`

  Contains all figures generated from the analysis notebook.
* Top-level files
  * `.pkl` files: final trained random forest model objects.
  * `env_sepsis_250522.yml`: Conda environment file specifying dependencies and package versions for reproducibility.
