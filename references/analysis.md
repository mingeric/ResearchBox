# Analysis: stateful exploration and reproducibility

Use for iterative Python, notebooks, data cleaning, statistics, modeling, and data figures.

## Choose the right execution mode

Use a live Jupyter kernel when exploration genuinely benefits from persistent variables, interactive DataFrame inspection, or stepwise debugging. Inspect live objects after consequential transformations. Use a script for a repeatable pipeline, batch work, or final generation. A notebook is not evidence of reproducibility until it runs cleanly from a fresh kernel.

## Analysis contract

Before modeling or plotting, write down input sources and versions, unit of observation, inclusion/exclusion rules, outcome(s), comparison, method, and expected artifact. Inspect schema, missingness, duplicate records, units, outliers, and class/sample balance first.

Preserve seeds, transformations, package/runtime versions, and generated outputs. For each conclusion, report the relevant sample size, estimator or test, comparison definition, uncertainty, and material limitation. Do not use precision, significance, or a complex model to conceal a weak design.

## Figures

A plot must answer one question. Check source data, aggregation, axes, units, scales, legends, ordering, color meaning, labels, and accessible contrast before interpreting it. Show uncertainty and individual observations when they change interpretation. Never imply causality, generality, or a group-level effect beyond the analysis design.
