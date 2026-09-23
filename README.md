# Bank Marketing Data Validation

> **Status:** Work in progress

This project examines data quality and machine-learning data integrity using
two complementary testing frameworks:

- **Great Expectations** for explicit schema, type, range and allowed-value rules.
- **Deepchecks** for statistical and machine-learning-oriented integrity checks.

## Dataset

The project uses `bank-additional-full.csv` from the
[UCI Bank Marketing dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing).

The classification target, `y`, records whether a customer subscribed to a
term deposit following a marketing campaign.

Dataset citation:

Moro, S., Rita, P. and Cortez, P. (2014). *Bank Marketing*.  
UCI Machine Learning Repository. https://doi.org/10.24432/C5K306

## Repository structure

```text
notebooks/
├── great_expectations_validation.ipynb
└── deepchecks_data_integrity.ipynb

requirements/
├── great_expectations.txt
└── deepchecks.txt
