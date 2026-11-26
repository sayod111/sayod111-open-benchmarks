---
language:
- en
pretty_name: Public trust and mail policy observations
configs:
- config_name: default
  data_files:
  - split: sample
    path: sample.csv
---

# Public trust and mail policy observations

Inspect public trust-center and email-policy indicators alongside their observation dates. This fixed sample contains 12 rows. The sample is for schema evaluation and does not establish population coverage.

## Fields

`domain`, `weak_dmarc`, `missing_trust_center`, `observed_date`.

## Interpretation

A blank field represents an unavailable observation. Retain the original units and dates. CSV and JSONL contain the same sample. They are two encodings, not separate observations.

## Access and provenance

[Sample catalog and procurement DDQ](https://sayod111.com/data-room) · [Source CSV](https://sayod111.com/samples/cyber.csv). Check source terms and the signed licence for redistribution.
