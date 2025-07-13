# Wine-Quality-Predictor
# 🍷 Wine Quality Predictor

This project uses machine learning to predict the quality of red wine based on its physicochemical properties. Built in a Jupyter Notebook, it includes an interactive UI built with Gradio, allowing users to try the model in real-time by entering custom wine feature values.

🔍 Overview

The model is trained on a Wine Quality dataset, which contains chemical analysis results for red wines, along with quality ratings assigned by human tasters.

📊 Features Used:
- Fixed Acidity  
- Volatile Acidity  
- Citric Acid  
- Residual Sugar  
- Chlorides  
- Free Sulfur Dioxide  
- Total Sulfur Dioxide  
- Density  
- pH  
- Sulphates  
- Alcohol

🧠 Model
- Machine Learning Library: `scikit-learn`
- Algorithm: Random Forest Classifier
- Evaluation: Accuracy score

🖥️ How It Works

Once trained, the model is wrapped in a Gradio interface, where users can enter chemical values and receive an instant wine quality prediction of either Good or Bad.

📁 Project Files

| File                         | Description                         |
|------------------------------|-------------------------------------|
| `WineQualityPredictor.ipynb` | Jupyter notebook with full workflow |
| `wine_model.pkl`             | Trained ML model                    |
| `winequality-red.csv`        | Wine Quality data                   |
| `README.md`                  | Project description (this file)     |



