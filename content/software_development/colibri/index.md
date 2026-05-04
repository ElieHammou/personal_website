---
title: Colibri
summary: An adaptable, open-source platform for flexible PDF fitting with any given parametrisation.
tags:
  - Particle Physics
  - PDFs
  - QCD
  - Bayesian Inference
  - Machine Learning

date: "2025-10-06"

# Optional external URL for project (replaces project detail page).
external_link: "https://github.com/HEP-PBSP/colibri"

url_code: "https://github.com/HEP-PBSP/colibri"
url_docs: "https://hep-pbsp.github.io/colibri/"

# View.
#   1 = List
#   2 = Compact
#   3 = Card
#   4 = Citation
view: 2
---

Colibri is a [reportengine](https://github.com/NNPDF/reportengine) application designed to perform Parton Distribution Function (PDF) fits using arbitrary parametrisations. It provides a flexible and adaptable open-source platform for PDF fitting.

**Key Features:**
- Perform PDF fits using flexible parametrisations
- Support for JAX-based computations (CPU by default)
- Optional GPU (CUDA) support for accelerated JAX operations
- Command-line scripts for common workflows (`colibri`, `evolve_fit`, etc.)
- Integration with external PDF model repositories

Colibri is part of the [PBSP](https://www.pbsp.org.uk/) project and is built to work with the NNPDF framework.

**Installation:**
```bash
# Via conda
conda env create -f environment.yml

# Or via pip
pip install git+https://github.com/HEP-PBSP/colibri.git
```

**Citation guidelines:** Please cite NNPDF (Eur. Phys. J. C 81 (2021) 958) and reportengine when using this code.

**Languages:** Python (97.5%), TeX (1.9%)

**License:** GPL-3.0
