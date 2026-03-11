## Article Overview

1.  **Article 1:** *Two‑Layer Gravity Model: From Atomic Calibration to Galaxy Rotation Curves and Cosmology*
    – Introduces the model, calibrates microscopic parameters ($\Gamma_0,\ell_0,alpha$) using diatomic molecules, fits galactic rotation curves (SPARC data), performs MCMC cosmological analysis, and summarises all parameters in Appendix A.

2.  **Article 2:** *Finsler Geometry and the Screening Mechanism: Unifying Micro and Macro Scales*
    – Provides the theoretical Lagrangian (scalar + vector fields) and shows how the phenomenological screening relation emerges; discusses a geometric interpretation via the Finsler–Randerts metric.

3.  **Article 3:** *Proton Mass and Fundamental Constants of Gravity: An Empirical Observation*
    – Reports the empirical dimensionless parameter $K = m_p \Gamma_0/(alpha^2 c^2 \ell_0) = 4.52	imes10^{-4}$ linking the proton mass to the atomic calibration constants.

4.  **Article 4:** *Testable Predictions of the Two‑Layer Gravity Model*
    – Gives quantitative predictions for the Pioneer anomaly, wide binary stars, the cosmic dipole, early JWST galaxies, dwarf galaxies, and laboratory tests at micrometre scales.

## How to Use

-   **Read the articles:** All preprints are in the `papers/` folder (Russian and English versions). The combined file `twolayer_gravity_model_collection_ru_en.pdf` contains all four articles in both languages.
-   **Reproduce the calculations:** Python scripts in `scripts/` are provided. They require standard scientific libraries (`numpy`, `scipy`, `pandas`, `matplotlib`, `emcee`, `getdist`, `astropy`). See comments inside each script for details.
-   **Data:** Input data files are in `data/`. The main calibration data is `molecular_calibration.csv` (14 molecules). Galaxy fitting results are in `galaxy_fits_12.csv`. MCMC posterior samples are in `mcmc_samples.npy` (if included).
-   **Figures:** All figures from the articles are in `figs/`; they can be regenerated using the plotting scripts.

## Citation

If you use this work in your research, please cite the Zenodo record (DOI will be assigned upon the first release). The concept DOI for the project is:

https://doi.org/10.5281/zenodo.18922993

*(Replace the DOI with the actual one after upload.)*

You may also cite individual articles as preprints (see the reference sections within each article).

## License

-   **Code:** The Python scripts in `scripts/` are licensed under the [MIT License](LICENSE).
-   **Data and articles:** The data files and PDF preprints are licensed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

## Links

-   **GitHub repository:** [https://github.com/yourusername/two-layer-gravity-model](https://github.com/yourusername/two-layer-gravity-model)
-   **Zenodo archive:** [https://doi.org/10.5281/zenodo.XXXXXXX](https://doi.org/10.5281/zenodo.XXXXXXX)

## Contact

Nikolai N. Dubina  
(Add contact information if desired)
# two-layer-gravity-model
