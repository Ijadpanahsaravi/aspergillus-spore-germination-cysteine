# 🧪 Inhibitory Effects of Cysteine on *Aspergillus* Spore Germination

This project investigates the germination behavior of *Aspergillus* spores under exposure to cysteine and its analogues using live-cell imaging (oCelloScope). The analysis quantifies morphological changes over time and classifies spores into distinct developmental stages: **resting**, **swelling**, and **germ tube formation**.

The experiments include two related studies:

---

## 🔬 1. Amino Acid Inhibition & Pre-Treatment

This part compares spore behavior in response to cysteine and its analogues (N-acetyl cysteine, S-methyl cysteine), and includes control, heat-killed, and proline-induced conditions with or without pre-treatment.

### RPubs Reports:

| Species | RPubs Report |
|--------|--------------|
| *Aspergillus niger* | [View on RPubs](https://rpubs.com/maryams/1304392) |
| *Aspergillus oryzae* | [View on RPubs](https://rpubs.com/maryams/1304391) |
| *Aspergillus nidulans* | [View on RPubs](https://rpubs.com/maryams/1304399) |
| *Aspergillus clavatus* | [View on RPubs](https://rpubs.com/maryams/1304394) |

---

## 🌡️ 2. Cysteine Dose-Response Study

This follow-up experiment investigates the effect of **increasing cysteine concentrations (0.1, 1, 10 mM)**, both alone and in combination with **proline (10 mM)**. The goal is to determine whether cysteine acts as a **dose-dependent inhibitor** of swelling and germination across species.

### RPubs Reports:

| Species | RPubs Report |
|--------|--------------|
| *Aspergillus niger* | [View on RPubs](https://rpubs.com/maryams/1304450) |
| *Aspergillus oryzae* | [View on RPubs](https://rpubs.com/maryams/1304453) |
| *Aspergillus clavatus* | [View on RPubs](https://rpubs.com/maryams/1304454) |

---

## 📊 Experimental Design Summary

### Treatments

- **Cysteine & analogues:**
  - Cysteine (`Cys`)
  - N-acetyl cysteine (`Acy-Cys`)
  - S-methyl cysteine (`Met-Cys`)

- **Dose-response (new data):**
  - Cys at 0.1, 1, and 10 mM
  - Proline (`Pro 10 mM`)
  - Proline + Cys combinations

- **Controls:**
  - No treatment (`C`)
  - Heat-killed spores (`C-K`)

- **Proline & pre-treatment:**
  - Proline pretreatment for 2–10 h followed by cysteine (e.g. `pre-pro 2 h`, `pre-pro 4 h`, etc.)

---
## 📁 Repository Structure

```text
aspergillus-germination-analysis/
├── analysis/               # Original amino acid & pre-treatment study
│   ├── niger.Rmd
│   ├── oryzae.Rmd
│   ├── clavatus.Rmd
│   └── nidulans.Rmd
├── dose_response/          # Cysteine dose-response experiment
│   ├── niger_dose_response.Rmd
│   ├── oryzae_dose_response.Rmd
│   └── clavatus_dose_response.Rmd
├── data/                   # CSV files (raw or cleaned)
├── plots/                  # (Optional) saved figures
└── README.md               # This file
---

## 📦 Tools & Libraries Used

- R / RStudio
- `ggplot2` — visualization
- `dplyr`, `tidyr`, `stringr`, `zoo` — data wrangling
- `germinationmetrics` — germination indices
- `knitr`, `rmarkdown` — report generation

---

## 👩‍🔬 Author

**Maryam Ijadpanahsaravi**  
PhD Researcher in Fungal Physiology and Biotechnology  
📧 *m.ijadpanahsaravi@uu.nl*  
