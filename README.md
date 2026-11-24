# Randomized Property Testing for LLM-Generated Programs

Prototype that decides, with few random queries, whether a program
(e.g. written by an LLM) correctly sorts a list.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/apeksha9098/randomized-property-testing/blob/main/randomized_property_testing_colab.ipynb)

## What it does
- Checks sortedness plus a randomized permutation fingerprint (no reference solution needed)
- Compares four testers: oracle-uniform, property-uniform, property-structured, Hypothesis
- Compares empirical detection with the theoretical bound 1 - (1-p)^k

## How to run
1. Click the "Open in Colab" badge
2. Runtime -> Run all (about 1-3 minutes)

## Requirements
hypothesis, numpy, pandas, matplotlib
