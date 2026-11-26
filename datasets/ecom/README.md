---
language:
- en
pretty_name: Storefront technology observations
configs:
- config_name: default
  data_files:
  - split: sample
    path: sample.csv
---

# Storefront technology observations

Compare observed marketing technology indicators across the sample domains. This fixed sample contains 12 rows. The sample is for schema evaluation and does not establish population coverage.

## Fields

`domain`, `signal_score`, `missing_klaviyo`, `observed_date`.

## Interpretation

A blank field represents an unavailable observation. Retain the original units and dates. CSV and JSONL contain the same sample. They are two encodings, not separate observations.

## Access and provenance

[Sample catalog and procurement DDQ](https://sayod111.com/data-room) · [Source CSV](https://sayod111.com/samples/ecom.csv). Check source terms and the signed licence for redistribution.
