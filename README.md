# ea-debt-llm

**Purpose**

This repository accompanies the research paper “Large Language Models for Analyzing Enterprise Architecture Debt in Unstructured Documentation”. It provides supplementary material that cannot be included in the main manuscript due to space constraints.

**Abstract**

Enterprise Architecture Debt (EA Debt) arises from suboptimal design decisions and misaligned components that can degrade an organization's IT landscape over time. Early indicators, Enterprise Architecture Smells (EA Smells), are currently mainly detected manually or only from structured artifacts, leaving much unstructured documentation under-analyzed. This study proposes an approach using a large language model (LLM) to identify and quantify EA Debt in unstructured architectural documentation. Following a design science research approach, we design and evaluate an LLM-based prototype for automated EA Smell detection. The artifact ingests unstructured documents (e.g., process descriptions, strategy papers), applies fine-tuned detection models, and outputs identified smells with severity assessments. We evaluate the prototype through a case study using synthetic yet realistic business documents, benchmarking against a custom GPT-based model. Results show that LLMs can detect multiple predefined EA Smells in unstructured text, with the benchmark model achieving higher precision and processing speed, and the fine-tuned on-premise model offering data protection advantages. The findings highlight opportunities for integrating LLM-based smell detection into EA governance practice.

**Repository Structure**

Appendices/ – Additional material referenced in the paper
- Appendix A: Feasability Assessment
- Appendix B: EA Smell Overview
- Appendix C: Scenarios for Case Study
- Appendix D: Fine Tuning Script
- Appendix E: Links to Raw Data

Case Study/ – Synthetic enterprise documents for the fictional company NextTech Group, used for evaluation
- 30 business layer documents
- Script to load model

Training Data/ – Datasets used for fine-tuning and evaluation experiments.
- Used training data for each EA Smell in scope

README.md – Project description (this file).

**How to Use**

The materials are intended to support transparency and reproducibility of the study. Interested researchers may:

- Review the synthetic case study documents as input examples for EA smell detection.
- Consult the training data and scripts to understand the fine-tuning and evaluation setup.
- Adapt the provided resources for related research on LLM-based analysis of enterprise documentation.

**Citation**

If you make use of this repository, please cite the corresponding paper:
[To be updated with final citation details once the paper is published]
