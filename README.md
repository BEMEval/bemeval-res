# 🏠 BEMEval-Res

**Benchmark for Evaluating LLM Performance in Residential Building Energy Modeling**

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Python](https://img.shields.io/badge/python-3.10+-blue.svg)]()
[![Dataset](https://img.shields.io/badge/dataset-TOML%20%7C%20XML-lightgrey.svg)]()
[![BEMEval](https://img.shields.io/badge/project-BEMEval-orange.svg)]()

---

### 📘 Overview
**BEMEval-Res** is the residential benchmark of the open-source **BEMEval** framework — a standardized dataset and evaluation suite for evaluating large language models (LLMs) performance on **building energy modeling (BEM)** tasks.

The benchmark focuses on translating *unstructured building descriptions* into *structured/machine-readable energy modeling schemas*, enabling consistent and reproducible evaluation of AI models in the BEM domain.

---

### 🧩 Key Features
- **Multiple Schemas** – Includes both **industry** and **research** schemas:
  - [HPXML](https://hpxml.nrel.gov/) – consensus residential schema for home energy modeling
  - **EPC-Schema** – customized normative schema based on ISO/CEN 13790 energy performance methods
- **Representative Building Cases** – curated building descriptions from:
  - HERS L100 test case
  - NIST NZERTF (single-family)
  - NREL iUnit (apartment/multifamily)
- **Evaluation Metrics**
  - Key–Value Overlap Rate (KVOR)


---

