🌾 Crop Type Prediction Using Machine Learning

This project explores predicting crop types based on soil and environmental features using various machine learning models. It also evaluates the predictive power of individual features and identifies the best predictive feature for classification.

🔹 Project Overview

The dataset contains crop yield and soil/environmental features such as Nitrogen (N) 🌱, Phosphorus (P) 💧, Potassium (K) ⚡, and pH 🧪.

Multiple classifiers are tested, including:

Logistic Regression 📈

Decision Tree 🌳

Random Forest 🌲

The project evaluates each feature individually and measures model performance using:

Accuracy ✅

Weighted F1 Score 🎯 (harmonic mean of precision and recall, adjusted for class imbalance)

🔹 Key Features

Automated selection of the best model-feature combination 🏆 based on evaluation metrics.

Handles single and multiple feature columns correctly (avoiding 1D array errors in scikit-learn).

Handles imbalanced classes ⚖️ using weighted metrics or balanced accuracy.

Outputs both feature-wise performance 📊 and the overall best predictive feature 🌟.
