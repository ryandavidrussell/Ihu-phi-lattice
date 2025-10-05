# Ihu-phi-lattice
Implosive Harmonic Unification (IHU) – φ-Lattice Framework Geometric factorization of the electroweak-to-vacuum coupling ratio using a quasi-icosahedral φ-lattice. Includes theory, LaTeX manuscript, numerical simulations, and reproducibility capsule for statistical validation.
# Implosive Harmonic Unification (IHU) – φ-Lattice Framework

phi-lattice-IHU/
│
├── README.md
├── LICENSE
├── ihu_paper.pdf
├── latex/
│   ├── main.tex
│   ├── sections/
│   │   ├── intro.tex
│   │   ├── cosmology.tex
│   │   └── ...
│   └── references.bib
├── figures/
│   ├── bao_residuals.png
│   ├── gw_ringdown.pdf
│   └── ...
├── code/
│   ├── phi_fit_pipeline.py
│   ├── bao_analysis.ipynb
│   └── ...
└── data/
    └── phi_band_fit_summary.csv

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.xxxxxxx.svg)](https://doi.org/10.5281/zenodo.xxxxxxx)

## Overview
This repository hosts the working papers, LaTeX source, figures, and reproducibility capsules for the **Implosive Harmonic Unification (IHU)** framework.  
The IHU proposes a φ-lattice vacuum structure that geometrically factors the electroweak-to-vacuum coupling ratio, with applications across cosmology, black hole physics, and the Standard Model.

Key features:
- 📄 LaTeX manuscripts (PRD/Nature/ArXiv-style)
- 📊 Python pipelines for φ-phase-locking and DSI analysis
- 📂 Data snapshots (BAO, GW ringdowns, fusion tails, etc.)
- 🔬 Statistical validation with reproducibility notebooks

## Repository Structure

## Getting Started
Clone the repo:
```bash
git clone https://github.com/ryandavidrussell/ihu-phi-lattice.git
cd latex
pdflatex main.tex
python code/phi_fit_pipeline.py
@article{Russell2025IHU,
  author       = {Ryan D. Russell},
  title        = {Implosive Harmonic Unification (IHU) – φ-Lattice Framework},
  year         = {2025},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.xxxxxxx}
}---

### 2. Upload Your Actual Files
At minimum:
- `ihu_paper.pdf` (compiled draft, so people see it instantly)  
- `latex/main.tex` + `.bib`  
- `figures/bao_residuals.png`, `gw_ringdown.pdf`  
- `code/phi_fit_pipeline.py` or a notebook (even simple placeholder is fine)  
- `data/phi_band_fit_summary.csv`  

---

### 3. Create a **Release v1.0**
Once those files are up:
1. Go to “Releases” → “Create a new release”.  
2. Tag as `v1.0`.  
3. Title: “First public preprint release”.  
4. Upload `ihu_paper.pdf` as an attached binary.  
5. Publish.  
6. Zenodo will automatically archive it and give you a DOI (once you’ve linked GitHub ↔ Zenodo).  

---

### 4. Link Zenodo Badge
Once Zenodo mints the DOI, copy its Markdown badge and paste it at the top of your README (like in my snippet above). That looks super professional.

---

Do you want me to **write you a starter `README.md` file** you can literally copy-paste into your repo right now, before you even connect to Zenodo? That way you’ll already look polished to anyone who stumbles across it.


