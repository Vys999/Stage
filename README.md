Optimizing Algorithms for Neural Decoding

This repository contains the code used for my Bachelor's internship at the Donders Centre for Neuroscience.

Repository structure:
Raw data:
Contains the 10 datasets used for the analyses.

Binary Decoding Accuracies.ipynb:
Main analysis pipeline for binary decoding.
In which the full pipeline is used to get the logreg and neural net accuracy.
The notebook can be used for both opposite and neighbouring cue pairs by selecting the cue labels.

Multiclass Decoding Accuracies.ipynb
Main analysis pipeline for multiclass decoding.
In which the full pipeline is used to get the logreg and neural net accuracy.
This notebook can only be used for the multiclass case.

Binary_general.ipynb
General development notebook for the binary decoding analysis (for opposite and neighbouring cases).
The PCA variance figure used in the thesis was generated from this notebook.
Contains:
preprocessing
PCA variance analysis
logistic regression experiments
comparison between Leave-One-Out and Train/Test Split
exploratory analyses

Multiclass_general.ipynb
General development notebook for multiclass decoding.
Contains the same things as in binary_general but for the multiclass case.

Save_files.ipynb
Small script that was used to store decoding results so they can later be combined into the final analysis.

Total plots with all data.ipynb
Final analysis notebook.
Loads the saved decoding results from all datasets and cue conditions and computes:

mean decoding accuracy
standard error of the mean (SEM)
final figures shown in the thesis


Reference for the used data:

M. F. Panichello, D. Jonikaitis, Y. J. Oh, S. Zhu, E. B. Trepka, and T. Moore, “Intermittent rate
coding and cue-specific ensembles support working memory,” Nature, 2024.

