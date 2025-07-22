# Research in Computational Onco-Pharmacogenomics & Computational Drug Discovery (CDD)

## Overview
Computational Drug Discovery (CDD) leverages machine learning, cheminformatics, and bioinformatics to identify potential drug candidates efficiently. This project, builds predictive models for drug-target interactions, molecular property prediction, and virtual screening to accelerate drug discovery.

## Features
- **Molecular Property Prediction**: Predict chemical properties like solubility, lipophilicity, and bioavailability.
-  **Drug-Target Interaction Prediction**: Use ML models to predict interactions between drug-like molecules and biological targets.
-  **Virtual Screening**: Screen chemical libraries to identify promising drug candidates.
-  **Deep Learning Models**: Implement neural networks for QSAR (Quantitative Structure-Activity Relationship) modeling.
-  **Explainability**: Integrate SHAP or similar techniques to interpret model predictions.

##  Tech Stack
- **Programming Language**:  Python
- **Libraries & Frameworks**: RDKit, DeepChem, PyTorch/TensorFlow, Scikit-learn, Pandas, NumPy
- **Data Sources**:  ChEMBL, PubChem
- **Visualization**:  Matplotlib, Seaborn

##  Installation

# Clone the repository
git clone gh repo clone poisonkissedsk/Computational-Drug-Discovery

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt



##  Usage
To train and evaluate the models, follow these steps:

###  Train a Drug-Target Interaction Model

python train_model.py --data data/dti_dataset.csv --model random_forest

###  To Predict Molecular Properties

python predict_properties.py --molecule data/molecule.sdf

###  To Perform Virtual Screening

python virtual_screening.py --library data/compound_library.csv


---

###  Dataset Preparation
1.  **Download** datasets from **ChEMBL, DrugBank, or PubChem**.
2.  **Preprocess** chemical structures using **RDKit**.
3.  **Convert** molecular fingerprints into feature vectors.
4.  **Normalize** and clean data for machine learning models.

##  Model Training & Evaluation
- Train different models: **Random Forest (RF), SVM, XGBoost, Deep Learning**.
- Evaluate performance using **cross-validation**.
- Optimize using **hyperparameter tuning** (Grid Search, Bayesian Optimization).
- Save trained models for inference.

##  Future Enhancements
-  Implement **Graph Neural Networks (GNNs)** for molecular representations.
-  Explore **Reinforcement Learning** for drug generation.
-  Integrate **AutoML** for model selection.
-  Develop a **web interface** for easy access.
