# Data Science Notebook Portfolio

Applied notebooks focused on the kind of data science work that turns vague
business, product, and research questions into defensible analysis.

## Overview

This repository collects practical notebooks across forecasting, causal
reasoning, synthetic data generation, and generative AI evaluation. Each
notebook is written as a walkthrough: define the problem, prepare the data,
build features or models, evaluate the result, and explain what the output
means.

The emphasis is not only on producing charts or model outputs. The goal is to
show how data work supports decisions: which features matter, when a
relationship is causal versus correlational, how to evaluate generated data,
and how prompt behavior changes across task types.

## Core Methods

- Python notebooks for exploration, modeling, and explanation
- Data preparation, feature engineering, and missing-value handling
- Causal reasoning, experiment framing, and model interpretation
- Forecasting with calendar and event-driven features
- Synthetic tabular data generation and distribution comparison
- Generative AI prompt design and lightweight evaluation

## Example Projects

| Notebook | What it demonstrates |
| --- | --- |
| [Forecasting: Calendar and Event Features](notebooks/forecasting_calendar_event_features.ipynb) | Builds causally informed calendar and event features for forecasting. Uses synthetic daily sales data to handle missing dates, encode holidays and events, train a simple model, and interpret feature impact. |
| [Mapping Causality: Socioeconomic Status and Health](notebooks/mapping_causality_socioeconomic_status_health.ipynb) | Frames socioeconomic status and health outcomes as a causal analysis problem. Covers causal feature selection, simulated SES-health data, missing values, categorical encoding, and naive versus causally informed modeling. |
| [The Rise of Synthetic Data](notebooks/synthetic_data_when_real_data_isnt_enough.ipynb) | Explores synthetic data for privacy-sensitive domains. Creates a healthcare-style dataset, trains a CTGAN model, and compares real and synthetic data for fidelity, utility, and privacy-oriented use cases. |
| [Worked Example: Website Traffic Forecasting](notebooks/worked_example_website_traffic_forecasting.ipynb) | Applies calendar and event feature engineering to daily website traffic. Shows how campaign indicators and weekend effects explain traffic spikes and improve forecasting context. |
| [Worked Examples in Generative AI Prompt Engineering and Evaluation](notebooks/generative_ai_prompt_engineering_evaluation_examples.ipynb) | Compares prompt strategies across factual QA and arithmetic reasoning tasks. Evaluates model behavior with simple metrics and shows why dataset type changes the usefulness of prompting techniques. |

## What This Shows

These notebooks are meant to show applied data science judgment:

- Move from a broad question to a structured analytical workflow
- Choose features based on domain logic, not just correlation
- Explain model outputs in plain language
- Compare approaches and identify where a model is useful or limited
- Treat notebooks as communication artifacts, not just scratch work

## How to Use

Open the notebooks in GitHub, Jupyter, or VS Code. Each notebook is
self-contained and includes narrative explanation, runnable code examples, and
discussion sections.
