# Credit Card Fraud Detection with Deep Learning and Optuna

## 📝 Description

This project demonstrates how to use Deep Learning and hyperparameter optimization with Optuna to detect fraudulent credit card transactions. By leveraging a credit card transaction dataset, the project builds and optimizes a robust model to achieve superior performance in fraud detection.

## 🔬 Methodology

The project workflow includes:

1. **Data Preparation:** Preprocessing the dataset, including:
   - Removing outliers.
   - Scaling features for better model performance.
2. **Data Balancing:** Addressing the class imbalance using **SMOTE** (Synthetic Minority Over-sampling Technique) to generate synthetic data for the minority class.
3. **Model Building:** Creating a Deep Neural Network (DNN) with:
   - Dense (fully connected) layers.
   - ReLU activation functions.
   - Built using the TensorFlow-Keras library.
4. **Hyperparameter Optimization:** Utilizing **Optuna** for automated and efficient optimization of:
   - Learning rate.
   - Hidden layer units.
   - Batch size.
5. **Model Evaluation:** Assessing performance with metrics like:
   - Precision
   - Recall
   - F1-score
   - AUC (Area Under the Curve).

## 📊 Results

### Comparison with Previous Work
This project builds upon a prior study ([Original Notebook](https://www.kaggle.com/code/janiobachmann/credit-fraud-dealing-with-imbalanced-datasets/notebook)) and demonstrates significant improvements in performance:

| Metric       | Previous Work (%) | This Project (%) | Improvement (%) |
|--------------|--------------------|------------------|-----------------|
| **Accuracy** | 99.92             | 99.94           | +0.02           |
| **Precision**| 84.42             | 85.71           | +1.29           |
| **Recall**   | 66.33             | 79.59           | +13.26          |
| **F1 Score** | 74.29             | 82.54           | +8.25           |

### Key Achievements
- **Accuracy:** Slight improvement, maintaining an almost perfect detection rate.
- **Precision:** Enhanced, meaning fewer false positives in identifying fraudulent transactions.
- **Recall:** Substantially improved, detecting a significantly higher proportion of fraudulent cases.
- **F1 Score:** Overall balance between precision and recall improved by 8.25%.

These results highlight the effectiveness of hyperparameter tuning with **Optuna**, leading to a more robust and reliable fraud detection model.

---

## 📖 Usage

1. **Download Dataset:** Obtain the [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud).
2. **Run Notebook:** Open and run the Jupyter Notebook `credit-fraud-dealing-with-imbalanced-datasets.ipynb`.

---

## 📚 References

- [Credit Card Fraud Dataset on Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- [Original Notebook](https://www.kaggle.com/code/janiobachmann/credit-fraud-dealing-with-imbalanced-datasets/notebook)

---

## 👤 Author

- [Your Name](https://github.com/AmadorZP)

---

## 📜 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
