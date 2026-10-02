# Edward Dack

Medical Sciences graduate (Pharmacology & Therapeutics) working on computational
drug discovery — currently MSc AI for Drug Discovery at Queen Mary University of London.

## Featured project

### [TYK2 in Ankylosing Spondylitis](https://github.com/edward-dack/tyk2-drug-discovery)
A reproducible pipeline assessing whether TYK2 is a credible target in ankylosing
spondylitis, built from ChEMBL and Open Targets data.

- Found that TYK2's high target-association score for AS rests on **clinical precedent
  for pan-JAK drugs, not AS genetics** — a caveat the headline score hides
- Identified that **37% of published TYK2 potency data** is patent-derived range values,
  which silently corrupt selectivity calculations if used naively
- Built QSAR models validated under scaffold-grouped splits (RMSE 0.73 vs 0.66
  experimental noise), showing where fingerprint models stop generalising
- Validated the candidate filters by recovering deucravacitinib, the only approved
  TYK2-selective drug, without special handling

*Python · RDKit · scikit-learn · pandas*

## Interests

- Computational drug discovery and cheminformatics
- Pharmacology and therapeutics
- Machine learning applied to biomedical data
- Translational research

## Education

**Queen Mary University of London** — MSc, Artificial Intelligence for Drug Discovery (2026–2027)

**University of Exeter** — BSc Medical Sciences (Pharmacology & Therapeutics), First Class Honours

---

More projects throughout my MSc.
