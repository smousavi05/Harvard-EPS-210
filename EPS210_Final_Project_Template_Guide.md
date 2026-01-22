# EPS-210 Final Project Report Guide
## AI for Earth and Planetary Science

---

## Template Links

### Recommended: NeurIPS Style (LaTeX/Overleaf)
- **Overleaf Template**: https://www.overleaf.com/latex/templates/neurips-2024/tpsbbrdqcmsh
- **Official NeurIPS Style Files**: https://neurips.cc/Conferences/2024/CallForPapers

### Alternative Options
- **AGU Style** (if submitting to AGU): https://www.agu.org/publish-with-agu/publish/author-resources/text-requirements
- **IEEE Conference**: https://www.ieee.org/conferences/publishing/templates.html

---

## Report Structure & Outline

### 1. Title & Authors
- Descriptive title that includes the ML method and Earth science application
- Example: *"Random Forest Classification of Lithologies from Well Log Data in the Permian Basin"*

### 2. Abstract (150–250 words)
- Problem statement (1–2 sentences)
- Approach/method (1–2 sentences)
- Key results (2–3 sentences)
- Significance (1 sentence)

### 3. Introduction (~1 page)
- Scientific context and motivation
- Why is this problem important for Earth science?
- Brief overview of prior work
- Clear statement of objectives
- Outline of the paper

### 4. Data (~0.5–1 page)
- Data source and acquisition
- Description of features and labels
- Data preprocessing steps
- Train/validation/test split rationale
- Include a table summarizing dataset statistics

### 5. Methods (~1–1.5 pages)
- Description of ML algorithm(s) used
- Why this method is appropriate for this problem
- Model architecture or hyperparameters
- Training procedure
- Evaluation metrics and why they were chosen

### 6. Results (~1.5–2 pages)
- Present results clearly with figures and tables
- Compare against baseline(s)
- Report performance metrics with uncertainty/variance
- Visualizations (confusion matrices, learning curves, feature importance, etc.)

### 7. Discussion (~1 page)
- Interpretation of results in Earth science context
- What did the model learn? (feature importance, patterns)
- Limitations of the approach
- Comparison with domain knowledge or physical models
- Potential improvements and future work

### 8. Conclusion (~0.5 page)
- Summary of main findings
- Broader implications
- Key takeaways

### 9. References
- Use consistent citation format (e.g., author-year)
- Include both ML and Earth science literature

### 10. Appendix (optional)
- Additional figures or tables
- Code snippets or pseudocode
- Extended methodology details

---

## Formatting Guidelines

| Element | Specification |
|---------|---------------|
| Page limit | 6–8 pages (excluding references) |
| Font | Times New Roman, 10pt |
| Spacing | Single-spaced |
| Margins | 1 inch (or as per NeurIPS template) |
| Columns | Two-column (NeurIPS style) |
| Figures | High resolution, clearly labeled axes |
| Tables | Readable, with captions above |
| Code | Link to GitHub repository |

---

## Tips for a Strong Report

1. **Tell a story**: Frame your work as answering a scientific question, not just applying an algorithm.

2. **Figures matter**: Invest time in clear, publication-quality figures. Include:
   - Map of study area (if applicable)
   - Example data samples
   - Model performance plots
   - Feature importance or model interpretation

3. **Compare methods**: Even a simple baseline (e.g., logistic regression) provides valuable context.

4. **Quantify uncertainty**: Report standard deviations from cross-validation or multiple runs.

5. **Connect to geoscience**: Discuss whether results make physical sense. Does feature importance align with domain knowledge?

6. **Reproducibility**: Include a link to your code repository and describe how to reproduce your results.

---

## Example Titles for Inspiration

- "Convolutional Neural Networks for Seismic Facies Classification"
- "Predicting Earthquake Aftershock Locations Using Gradient Boosting"
- "Unsupervised Clustering of Volcanic Tremor Signals"
- "LSTM Networks for Sea Surface Temperature Forecasting"
- "Transfer Learning for Mineral Identification from Hyperspectral Imagery"

---

## Submission Checklist

- [ ] PDF formatted according to template
- [ ] All figures are legible and properly captioned
- [ ] Abstract is self-contained and within word limit
- [ ] References are complete and properly formatted
- [ ] Code repository link included
- [ ] Spell-checked and proofread

---

*Last updated: January 2026*
