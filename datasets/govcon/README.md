---
language:
- en
pretty_name: US federal award expirations
configs:
- config_name: default
  data_files:
  - split: sample
    path: sample.csv
---

# US federal award expirations

Group obligations by NAICS and contract end date when reviewing upcoming procurement windows. This fixed sample contains 12 rows. The sample is for schema evaluation and does not establish population coverage.

## Fields

`naics_code`, `place_state`, `obligated_usd`, `current_end_date`.

## Interpretation

A blank field represents an unavailable observation. Retain the original units and dates. CSV and JSONL contain the same sample. They are two encodings, not separate observations.

## Access and provenance

[Sample catalog and procurement DDQ](https://sayod111.com/data-room) · [Source CSV](https://sayod111.com/samples/govcon.csv). Check source terms and the signed licence for redistribution.
