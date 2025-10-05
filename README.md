“GlycoPred: A Supervised Learning Framework for Predicting Glycometabolic Proteins Using Proteomic Sequence Features.”

The framework integrates machine learning (ML) and deep learning (DL) approaches to identify and classify glycometabolism-associated proteins based on sequence-derived descriptors. The codebase supports feature extraction, model development, and performance evaluation, enabling researchers to reproduce and extend the results presented in the manuscript.

Authors:
Hamza Shahab Awan¹
Abid Sohail*1
Corresponding Author: Fahad Alturise (Email:hamzashahabawan@gmail.com)

Affiliations:
Department of Computer Science, COMSATS University Islamabad, Lahore Campus, Pakistan

Repository Structure

This repository consists of three main Python scripts:

1. Feature Extraction
Implements positional and statistical moment-based feature encoding, including raw, central, and Hahn moments, along with PRIM, RPRIM, AAPIV, and RAAPIV descriptors. These features capture spatial, compositional, and positional dependencies of amino acids in glycometabolic protein sequences.

2. Model Development
model_training.py builds and evaluates multiple ML and DL models, including SVM, Random Forest, Extra Trees, CNN, and LSTM architectures. Each model is trained using the extracted features to classify proteins as glycometabolic or non-glycometabolic, based on their proteomic signatures.

3. Evaluation and Explainability
Implements cross-validation, independent testing, and interpretable AI methods such as feature importance analysis and confusion matrix visualization to validate model robustness and interpretability.

Availability
The dataset used in this study comprises curated glycometabolic protein sequences derived from UniProt/Swiss-Prot and NCBI repositories.
Access to the dataset is available upon reasonable request.
Please contact Hamza Shahab Awan (Email: hamzashahabawan@gmail.com / sp24-pcs-006@cuilahore.edu.pk) or the corresponding author for data access.

