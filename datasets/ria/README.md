---
language:
- en
pretty_name: US investment advisers
configs:
- config_name: default
  data_files:
  - split: sample
    path: sample.csv
---

# US investment advisers

Compare reported assets across states and inspect the disclosure mismatch indicator. This fixed sample contains 12 rows. The sample is for schema evaluation and does not establish population coverage.

## Fields

`state_code`, `aum_usd`, `item11_mismatch`, `observed_date`.

## Interpretation

A blank field represents an unavailable observation. Retain the original units and dates. CSV and JSONL contain the same sample. They are two encodings, not separate observations.

## Access and provenance

[Sample catalog and procurement DDQ](https://sayod111.com/data-room) · [Source CSV](https://sayod111.com/samples/ria.csv). Check source terms and the signed licence for redistribution.
