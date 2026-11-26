---
language:
- en
pretty_name: UK and EU tender notices
configs:
- config_name: default
  data_files:
  - split: sample
    path: sample.csv
---

# UK and EU tender notices

Compare notice values within a single currency and publication period. This fixed sample contains 12 rows. The sample is for schema evaluation and does not establish population coverage.

## Fields

`country_code`, `currency_code`, `estimated_value_num`, `published_date`.

## Interpretation

A blank field represents an unavailable observation. Retain the original units and dates. CSV and JSONL contain the same sample. They are two encodings, not separate observations.

## Access and provenance

[Sample catalog and procurement DDQ](https://sayod111.com/data-room) · [Source CSV](https://sayod111.com/samples/tenders.csv). Check source terms and the signed licence for redistribution.
