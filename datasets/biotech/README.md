---
language:
- en
pretty_name: Biotech funding and regulatory events
configs:
- config_name: default
  data_files:
  - split: sample
    path: sample.csv
---

# Biotech funding and regulatory events

Inspect funding events by source agency and event date. This fixed sample contains 12 rows. The sample is for schema evaluation and does not establish population coverage.

## Fields

`source_agency`, `event_date`, `funding_or_award_usd`, `signal_score`.

## Interpretation

A blank field represents an unavailable observation. Retain the original units and dates. CSV and JSONL contain the same sample. They are two encodings, not separate observations.

## Access and provenance

[Sample catalog and procurement DDQ](https://sayod111.com/data-room) · [Source CSV](https://sayod111.com/samples/biotech.csv). Check source terms and the signed licence for redistribution.
