# Neuroscience Python Portfolio
PhD neuroscientist (NTU LKCMedicine, 2026) transitioning into AI for biomedicine.
Domain expertise: prefrontal circuits, working memory, schizophrenia models, in vivo calcium imaging.

## Main Project: MAM vs Control Mouse Classifier
**Question:** Can population-level neural activity patterns distinguish schizophrenia model (MAM) mice from controls?

**Data:** In vivo calcium imaging (GCaMP) from medial frontal cortex. N = ~10 mice (MAM + control groups).

**Methods:** Feature extraction from dF/F traces → Logistic Regression + Random Forest classifiers → Leave-One-Out cross-validation (chosen for small N).

**Result:** LOO classification accuracy of 0.78, above chance (0.5), suggesting population activity patterns carry group-discriminating information.

**Tools:** Python, h5py, NumPy, pandas, scikit-learn, matplotlib, seaborn.

[View notebook](link to your portfolio_main.ipynb)

## Other Projects
- Week 3: Mouse working memory performance visualisation (pandas + seaborn)
- Week 6: Neural population decoder — simulated WM vs distractor conditions
