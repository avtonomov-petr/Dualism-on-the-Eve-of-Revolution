# Dualism on the Eve of Revolution: Provincial Income Inequality, Industrial Land Rents, and Social Transformation in Late Imperial Russia, 1859–1914

[![License: MIT](https://shields.io)](LICENSE)

This repository contains the reproducible Python/Jupyter pipeline, high-resolution figures, open-access Global Price and Income History Group (GPIHG) datasets, and LaTeX manuscript sources for the study:

> **Avtonomov, P. (2026f).** *Dualism on the Eve of Revolution: Provincial Income Inequality, Industrial Land Rents, and Social Transformation in Late Imperial Russia, 1859–1914.*

This work concludes a six-part empirical audit of Imperial Russia's external market integration and domestic socio-economic structures alongside [doi:10.5281/zenodo.24436177](https://doi.org), [doi:10.5281/zenodo.24461586](https://doi.org), [doi:10.5281/zenodo.24498028](https://doi.org), [doi:10.5281/zenodo.24508139](https://doi.org), and [doi:10.5281/zenodo.24530102](https://doi.org).

## Key Empirical Findings

* **Extreme Capital-City Dualism (`1904`, $N = 50$ Provinces):** Singular value decomposition across eight distributional indicators reveals a dominant structural axis ($\mathrm{Var}_1 = 72.3\%$, $\mathrm{PR}_{\mathrm{feat}}(v_1) = 0.841$) hyper-localized in the two imperial capitals ($\mathrm{PR}_{\mathrm{prov}}(u_1) = 0.056$). `Sankt-Peterburg` ($39.22\%$, $\mathrm{Gini} = 0.611$, Top 1% income share `34.50%`) and `Moskva` ($33.15\%$, $\mathrm{Gini} = 0.591$, Top 1% share `38.46%`) capture `72.37%` of provincial Mode 1 energy (`60.3%` on non-redundant $K = 4$ indicators and `59.1%` on $K = 3$).
* **Three-Tier Regional Anatomy:** Orthogonal Mode 2 ($\mathrm{Var}_2 = 17.3\%$) isolates median living standards ($v_{2,\mathrm{Median}} = +0.787$), separating the capitals from high-median northern forest provinces (`Olonets`, $\mathrm{Gini} = 0.169$, median household income `875.2` rubles/year) and the low-income agrarian peasant heartland (`Vyatka`, `Ufa`, `Voronezh`, `Vologda`, `Tver`, $\mathrm{Gini} = 0.24\text{--}0.28$).
* **Post-Emancipation Industrial Land Boom & Urbanization (`1859–1914`):** Annual brick-factory land lease rates in Nizhny Novgorod surged `14.6x` in gold rubles between `1859–1879` (`0.0546` rub/sq. sazhen) and `1897–1914` (`0.7997` rub/sq. sazhen) while leased pasture contracted (`18,401` to `12,770` sq. sazhens) and average leaseholders fell from `6.3` to `1.8`. Concurrently, European Russia's urban estate population expanded over fivefold from `4.30 million` (`7.3%`) in 1858 to `22.72 million` (`17.6%`) in 1913.

## Repository Contents

* `reproduce_late_empire.ipynb` / `reproduce_late_empire.py` — End-to-end reproducible Python pipeline generating all summary diagnostics, indicator-collinearity checks, and `300 dpi` figures.
* `Figure_1_LateEmpire.png` — Provincial Mode 1 concentration, two-mode structural map (`N = 50`), top 1% capture vs. Gini, and mean vs. median skewness (`1904`).
* `Figure_2_LateEmpire.png` — Nizhny Novgorod industrial land lease boom (`1859–1914`) and long-run estate transformation in European Russia (`1678–1913`).
* `Dualism_on_the_Eve_of_Revolution.pdf` / `main.tex` — Compiled preprint and LaTeX manuscript source.
* `1904_Medium-ineq_distrib_14dec'11.xlsx`, `Nizhny Novgorod land lease prices 1859-1914.xlsx`, `T._1._Russia's_Classes_1678-1913.xls` — Open-access GPIHG source datasets.

## License

Code is released under the MIT License; manuscript text and figures are licensed under [CC BY 4.0](https://creativecommons.org).
