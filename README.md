# 🧪 Inhibitory Effects of Cysteine on Aspergillus Spore Germination

This project investigates the germination behavior of *Aspergillus* spores under exposure to cysteine and its analogues using live-cell imaging with oCelloScope. The analysis quantifies morphological changes over time and classifies spores into distinct developmental stages: **resting**, **swelling**, and **germ tube formation**.

The experiment includes comparative analysis across multiple species and treatment conditions including cysteine, N-acetyl cysteine, S-methyl cysteine, proline, pre-treatments, and controls.

---

## 🔬 Species Analyzed

Each species has its own dedicated RMarkdown report and interactive visualization published on RPubs:

| Species | RPubs Report |
|--------|--------------|
| *Aspergillus niger* | [View on RPubs](https://rpubs.com/maryams/1304392) |
| *Aspergillus oryzae* | [View on RPubs](https://rpubs.com/maryams/1304391) |
| *Aspergillus nidulans* | [View on RPubs](https://rpubs.com/maryams/1304399) |
| *Aspergillus clavatus* | [View on RPubs](https://rpubs.com/maryams/1304394) |

---

## 📊 Experimental Design

Spores were exposed to the following treatments:

- **Cysteine & analogues**:
  - Cysteine (`Cys`)
  - N-acetyl cysteine (`Acy-Cys`)
  - S-methyl cysteine (`Met-Cys`)

- **Controls**:
  - No treatment (`C`)
  - Heat-killed spores (`C-K`)

- **Proline & pre-treatment**:
  - Proline (`pro`)
  - Pre-proline exposure followed by cysteine (`pre-pro X h + Cys`)

Spore state classification was based on **area and circularity** thresholds:
- Resting: minimal change
- Swelling: area increase without shape change
- Germinating: significant change in both area and circularity

---

## 📦 Tools & Libraries

- R / RStudio
- `ggplot2`
- `dplyr`, `tidyr`, `zoo`, `stringr`
- `germinationmetrics` for germination indices
- `knitr` + `rmarkdown` for report generation

---

**Maryam Ijadpanahsaravi**  
📧 Contact: *[m.ijadpanahsaravi@uu.nl]*  



