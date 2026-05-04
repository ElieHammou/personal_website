---
title: wmin-model
summary: A Colibri app implementing the POD parametrisation for PDF fitting.
tags:
  - Particle Physics
  - PDFs
  - POD
  - Bayesian Inference
  - Machine Learning

date: "2025-07-24"

# Optional external URL for project (replaces project detail page).
external_link: "https://github.com/HEP-PBSP/wmin-model"

url_code: "https://github.com/HEP-PBSP/wmin-model"
url_pdf: "https://arxiv.org/pdf/2507.16913"

# View.
#   1 = List
#   2 = Compact
#   3 = Card
#   4 = Citation
view: 2
---

wmin-model is a [Colibri](https://github.com/HEP-PBSP/colibri) PDF-model that implements the Proper Orthogonal Decomposition (POD) parametrisation presented in [arXiv:2507.16913](https://arxiv.org/pdf/2507.16913).

**Primary Workflows:**
1. **PDF Fits with POD Parametrisation:** Perform parton distribution function (PDF) fits on [NNPDF data](https://github.com/NNPDF/nnpdf) using the Colibri Bayesian workflow and the linear POD parametrisation.
2. **POD-Basis Construction:** Generate a Proper Orthogonal Decomposition (POD) basis.

wmin-model implements the NNPOD methodology, providing a linear PDF model optimized for Bayesian inference in high-energy physics.

**Installation:**
```bash
git clone https://github.com/HEP-PBSP/wmin-model.git
cd wmin-model
conda env create -f environment.yml
```

**Citation:**
```
@article{Costantini:2025wxp,
    author = "Costantini, Mark N. and Mantani, Luca and Moore, James M. and Ubiali, Maria",
    title = "{A linear PDF model for Bayesian inference}",
    eprint = "2507.16913",
    archivePrefix = "arXiv",
    primaryClass = "hep-ph",
    month = "7",
    year = "2025"
}
```

**Languages:** Python (100%)

**License:** GPL-3.0
