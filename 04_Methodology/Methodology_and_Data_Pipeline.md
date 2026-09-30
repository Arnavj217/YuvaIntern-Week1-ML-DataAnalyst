# Methodology Specification

## Pipeline
`Source discovery → raw acquisition → metadata capture → profiling → cleaning → validation → transformation → EDA → KPI analysis → visualization → findings → QA`

## Data layers
1. Raw — unchanged source files.
2. Staging — standardized names/types/units.
3. Curated — validated analytical tables.
4. Output — charts, tables, dashboards and findings.

## Cleaning rules
- Preserve source values before transformation.
- Standardize names with mapping tables.
- Parse dates explicitly.
- Treat missing and zero separately.
- Validate duplicates using natural keys.
- Validate units before aggregation.
- Investigate outliers before removal.
- Record every transformation.

## Analysis methods
Descriptive statistics; YoY growth; CAGR; rolling averages; coefficient of variation; seasonal comparisons; price/arrival analysis; geographic concentration; correlation screening; later-stage forecasting if sufficient data exist.

## Validation
For each major KPI confirm source definition, unit, time period, geography, sample-check against the original source, and compare overlapping sources where possible.
