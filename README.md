# 🧪 Computational Drug Discovery (CDD)

## 🔬 Overview
Computational Drug Discovery (CDD) leverages machine learning, cheminformatics, and bioinformatics to identify potential drug candidates efficiently. This project, inspired by **Data Professor**, builds predictive models for drug-target interactions, molecular property prediction, and virtual screening to accelerate drug discovery.

## 🚀 Features
- 🏺 **Molecular Property Prediction**: Predict chemical properties like solubility, lipophilicity, and bioavailability.
- 🎯 **Drug-Target Interaction Prediction**: Use ML models to predict interactions between drug-like molecules and biological targets.
- 🔍 **Virtual Screening**: Screen chemical libraries to identify promising drug candidates.
- 🤖 **Deep Learning Models**: Implement neural networks for QSAR (Quantitative Structure-Activity Relationship) modeling.
- 🧐 **Explainability**: Integrate SHAP or similar techniques to interpret model predictions.

## 🛠 Tech Stack
- **Programming Language**: 🐍 Python
- **Libraries & Frameworks**: RDKit, DeepChem, PyTorch/TensorFlow, Scikit-learn, Pandas, NumPy
- **Data Sources**: 📚 ChEMBL, PubChem, DrugBank
- **Visualization**: 📊 Matplotlib, Seaborn

## 📥 Installation
```bash
# Clone the repository
git clone https://github.com/poisonkissedsk/CDD_AIDM.git
cd CDD_AIDM

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
