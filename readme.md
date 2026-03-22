# Explainable AI

Summary of the material taught in the explainable ai course @FHGR in autumn 2025.

You can find the pdf [here](outFiles/main.pdf)

Course was based on [interpretable machine learning by Christoph Molnar](https://christophm.github.io/interpretable-ml-book/).
You can find the full book on the link online, or buy it there.

Some of the images were taken from that book.


## Contents

Here’s a short markdown list summarizing the main contents from the summary (main.pdf) and corresponding repo files of explainable-ai-summary:

- **Introduction to Explainable AI**
  - Interpretability taxonomy: intrinsic vs. post-hoc
  - Types of results (feature stats, model internals, counterfactuals, surrogates)
  - Global vs Local interpretability
  - Best practices for explanations

- **Linear Models**
  - Linear regression, confidence intervals, interpretation of coefficients
  - Lasso for sparsity and feature selection
  - Logistic regression for classification
  - Extensions: Generalized Linear Models (GLM), Generalized Additive Models (GAM)
  - Handling interactions & nonlinearities

- **Interpretable Models: Decision Trees & Rule Models**
  - Structure and training of decision trees (CART)
  - Splitting criteria, prediction methods, and feature importance
  - Rule-based models and RulerFit: combining linear and rule-based approaches

- **Model-Agnostic and Example-Based Explanations**
  - Explanations independent of model type
  - Example-based approaches: prototypes, counterfactuals, adversarials

- **Local Model-Agnostic Explanations**
  - ICE (Individual Conditional Expectation) plots
  - LIME (Local Interpretable Model-agnostic Explanations)
  - Shapley values and SHAP for feature attribution

- **Global Model-Agnostic Explanations**
  - PDP (Partial Dependence Plots) and ALE (Accumulated Local Effects)
  - Measuring feature importance (permutation approach)
  - Detecting feature interactions (H-statistic)
  - Surrogate models (interpreting black-box models using interpretable surrogates)
