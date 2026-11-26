---
language:
- en
pretty_name: US motor carriers
configs:
- config_name: default
  data_files:
  - split: sample
    path: sample.csv
---

# US motor carriers

Compare power units and drivers by state and carrier operating category. This fixed sample contains 12 rows. The sample is for schema evaluation and does not establish population coverage.

## Fields

`phy_state`, `carrier_operation`, `power_units`, `total_drivers`.

## Interpretation

A blank field represents an unavailable observation. Retain the original units and dates. CSV and JSONL contain the same sample. They are two encodings, not separate observations.

## Access and provenance

[Sample catalog and procurement DDQ](https://sayod111.com/data-room) · [Source CSV](https://sayod111.com/samples/fmcsa.csv). Check source terms and the signed licence for redistribution.
