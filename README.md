# Scalar–Yukawa Gravity
 markdown  [![DOI](https://zenodo.org/badge/1021972899.svg)](https://doi.org/10.5281/zenodo.16088734)  
 
Reproducible code, data, and manuscript for our **entropic master-equation → Yukawa-screened scalar-field** model of modified gravity.

---

## Project layout
```text
notebooks/        – Jupyter workflows (posterior, lensing, MEMS)
data/             – down-sampled κ-maps, MEMS CSVs, rotation curves
scripts/          – fetch_raw_assets.py (downloads large FITS + 2 GB MEMS stream)
figures/          – 300 dpi PNGs ready for publication
manuscript/       – LaTeX source, BibTeX, compiled PDF
environment.yml   – conda environment lockfile
```

---

## Quick start
```bash
git clone https://github.com/NeoAmorfic/Scalar-Yukawa-Gravity.git
cd Scalar-Yukawa-Gravity
conda env create -f environment.yml
conda activate syg
jupyter lab
```

---

## Reproduce all figures
1. Open `notebooks/00_master_pipeline.ipynb` in Jupyter Lab.  
2. Select **Kernel ▸ Restart & Run All**.  
3. Regenerated PNGs appear in `figures/` (≈ 6 min on a 4-core laptop).

---

## Citation
If this repository or the accompanying paper helps your research, please cite:

```bibtex
@article{NeoAmorfic2025,
  title   = {Scalar–Yukawa Gravity: An Entropic Route to Screening},
  author  = {Your Name and Collaborators},
  journal = {Phys. Rev. D},
  year    = {2025},
  volume  = {XXX},
  pages   = {XXXXXX},
  bibtex  doi     = {10.5281/zenodo.16088734}  
}
```

---

## License
Code and data are released under the **MIT License** (see `LICENSE`).

---

*Maintained by NeoAmorfic — pull requests welcome!*
