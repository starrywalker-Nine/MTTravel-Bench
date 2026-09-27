# MTTravel-Bench

**MTTravel-Bench** is a benchmark for evaluating dynamic narrative reasoning in large language models (LLMs). It operationalizes functional aspects of mental-time-travel-inspired reasoning as the ability to connect past narrative states, present action constraints, and future factual outcomes.

> **Repository status:** This repository is currently being prepared for public release. The complete version supporting the associated manuscript, including derived benchmark materials and reproducibility resources where permitted, will be released upon publication.

## Overview

MTTravel-Bench converts narrative materials into decision-node-centered causal-temporal trajectories represented as directed acyclic graphs (DAGs). The benchmark includes complementary tasks designed to characterize different aspects of model behavior:

- **Task 1: Candidate-action structural profiling.** Given a decision node and candidate actions, a model predicts structured attributes related to spatiotemporal reconstruction (STR), self-projection (SP), self-state/trajectory consistency (SC), and auxiliary utility (U).
- **Task 2: Fact-conditioned consequence prediction.** Given the factual action in the original narrative, a model predicts goal progress, risk changes, constraint violations, secondary consequences, and fine-grained outcome labels.

The benchmark is designed to assess functional computational performance. It does not imply that evaluated models possess subjective memory, consciousness, or human-like mental time travel.

## Associated Manuscript

**MTTravel-Bench: A Dynamic Narrative Benchmark for Evaluating Mental-Time-Travel Option Reasoning and Factual Foresight in Large Language Models**

Manuscript status: under preparation / submitted for peer review.

Citation information and a persistent archival identifier will be added when available.

## Release Plan

The public release is planned to include, where permitted:

- Derived MTTravel-Bench decision-node-centered trajectory representations
- Benchmark annotations and task-specific labels
- Dataset splits and evaluation materials
- Code for benchmark construction, data processing, evaluation, and analysis
- Documentation for setup and reproduction of the reported analyses

A versioned release corresponding to the associated publication will be created upon publication. Where feasible, that release will also be archived through a persistent research-data repository.

## Source Materials and Licensing

MTTravel-Bench is derived from multiple narrative sources, including TellMeWhy, NTSB aviation accident reports, and FairytaleQA. Original source materials remain subject to the access terms, licenses, and redistribution conditions of their respective providers.

This repository will share only materials that may be legally redistributed. Users are responsible for obtaining any required original source materials directly from their corresponding providers and for complying with all applicable terms of use.

## Current Availability

The full benchmark package is not yet available. This repository serves as the official project location for the forthcoming public release and future updates.

For questions concerning the benchmark or the planned release, please open an issue in this repository or contact the corresponding author listed in the associated manuscript.

## License

A license for the public release will be specified before the release of benchmark materials and code. Third-party source materials are not covered by any license subsequently added to this repository.
