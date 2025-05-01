# 🧪 Inhibitory Effects of Cysteine on *Aspergillus* Spore Germination

This project investigates the germination dynamics of *Aspergillus* spores under exposure to cysteine and its analogues using live-cell imaging (oCelloScope). The analysis quantifies morphological changes over time and classifies spores into distinct developmental stages: **resting**, **swelling**, and **germ tube formation**.

The experiments include three related studies:

---

## 🔬 1. Amino Acid Inhibition & Pre-Treatment

This study compares spore behavior in response to **cysteine and its analogues** (N-acetyl cysteine, S-methyl cysteine), and includes **control, heat-killed**, and **proline-induced** conditions, with or without **proline pre-treatment**.

### RPubs Reports:

| Species               | RPubs Report                                     |
|-----------------------|--------------------------------------------------|
| *Aspergillus niger*   | [View on RPubs](https://rpubs.com/maryams/1304392) |
| *Aspergillus oryzae*  | [View on RPubs](https://rpubs.com/maryams/1304391) |
| *Aspergillus nidulans*| [View on RPubs](https://rpubs.com/maryams/1304399) |
| *Aspergillus clavatus*| [View on RPubs](https://rpubs.com/maryams/1304394) |

---

## 🌡️ 2. Cysteine Dose-Response Study

This follow-up experiment investigates the effect of **increasing cysteine concentrations (0.1, 1, 10 mM)**, both alone and in combination with **proline (10 mM)**. The goal is to determine whether cysteine acts as a **dose-dependent inhibitor** of swelling and germination across species.

### RPubs Reports:

| Species               | RPubs Report                                     |
|-----------------------|--------------------------------------------------|
| *Aspergillus niger*   | [View on RPubs](https://rpubs.com/maryams/1304797)|
| *Aspergillus oryzae*  | [View on RPubs](https://rpubs.com/maryams/1304800)|
| *Aspergillus clavatus*| [View on RPubs](https://rpubs.com/maryams/1304795)|

---

## 🧪 3. Pre-Treatment vs Direct Exposure Study

This third analysis explores whether **cysteine acts as an inhibitor of growth** or simply fails to act as a germination trigger. It compares:

- Spores **pretreated** with proline or glucose for 2–12 hours, followed by cysteine or its analogues
- Spores **directly exposed** to proline and cysteine analogues (washed and unwashed)

### 🔍 Key Observations:

- **Direct exposure** to cysteine (washed/unwashed) does **not trigger germination**, suggesting it lacks inductive capacity.
- **Proline pre-treatment + cysteine** leads to **strong inhibition** of germination, especially after 6–8h of pre-treatment.
- In contrast, **Acetyl Cys and Met Cys do not inhibit** germination after pre-treatment.
- **Glucose pre-treatment** combined with cysteine allows **partial germination**, indicating **cysteine inhibition is stronger when spores are metabolically primed** by proline.
- This suggests that **cysteine functions as a true inhibitor of post-induction growth**, not just a non-trigger.

### RPubs Reports:

| Analysis Type            | RPubs Report                                      |
|--------------------------|---------------------------------------------------|
| Without Pre-treatment    | [View on RPubs](https://rpubs.com/maryams/1304767)|
| Proline Pre-Treatment    | [View on RPubs](https://rpubs.com/maryams/1304769)|
| Glucose Pre-Treatment    | [View on RPubs](https://rpubs.com/maryams/1304784)|

---

## 📊 Experimental Design Summary

### Treatments

- **Cysteine & analogues:**
  - Cysteine (`Cys`)
  - N-acetyl cysteine (`Acy-Cys`)
  - S-methyl cysteine (`Met-Cys`)

- **Dose-response:**
  - Cys at 0.1, 1, and 10 mM
  - Proline (`Pro 10 mM`)
  - Pro + Cys combinations

- **Controls:**
  - No treatment (`C`)
  - Heat-killed spores (`C-K`)

- **Pre-treatment series:**
  - Proline or glucose exposure (2–12 h), followed by Cys or analogues
  - Washed and unwashed conditions

---

## 📁 Repository Structure
```text
aspergillus-germination-analysis/
├── analysis/                        # Original amino acid & pre-treatment study
│   ├── niger.Rmd
│   ├── oryzae.Rmd
│   ├── clavatus.Rmd
│   └── nidulans.Rmd
├── dose_response/                   # Cysteine dose-response experiment
│   ├── niger_dose_response.Rmd
│   ├── oryzae_dose_response.Rmd
│   └── clavatus_dose_response.Rmd
├── pretreatment_comparison/         # Pre-treatment vs direct exposure study
│   ├── niger_without_pretreatment.Rmd
│   ├── niger_proline_pretreatment.Rmd
│   └── niger_glucose_pretreatment.Rmd
├── data/                            # Raw or cleaned CSV files

---

Maryam Ijadpanahsaravi
PhD Researcher in Fungal Physiology and Biotechnology
📧 m.ijadpanahsaravi@uu.nl
