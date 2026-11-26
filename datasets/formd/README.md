---
language:
- en
pretty_name: US SEC Form D offerings
configs:
- config_name: default
  data_files:
  - split: sample
    path: sample.csv
---

# US SEC Form D offerings

Compare reported offering sizes across filing dates, distinguishing amendments from original filings. This fixed sample contains 12 rows. The sample is for schema evaluation and does not establish population coverage.

## Fields

`filed_date`, `form_type`, `is_amendment`, `total_offering_usd`.

## Interpretation

A blank field represents an unavailable observation. Retain the original units and dates. CSV and JSONL contain the same sample. They are two encodings, not separate observations.

## Access and provenance

[Sample catalog and procurement DDQ](https://sayod111.com/data-room) · [Source CSV](https://sayod111.com/samples/formd.csv). Check source terms and the signed licence for redistribution.
