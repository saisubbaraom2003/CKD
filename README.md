# Kidney Disease Prediction Model

This project builds a machine learning model to predict kidney disease based on various clinical features. It uses supervised learning techniques to classify whether a patient is likely to have chronic kidney disease (CKD) or not.

## 🧪 Features

The dataset contains the following features:

- **Numerical Features**: 
  - `age`, `bp` (blood pressure), `sg` (specific gravity), `al` (albumin), `su` (sugar), `bgr` (blood glucose random), `bu` (blood urea), `sc` (serum creatinine), `sod` (sodium), `pot` (potassium), `hemo` (hemoglobin), `pcv` (packed cell volume), `wc` (white blood cell count), `rc` (red blood cell count).
- **Categorical Features**: 
  - `rbc` (red blood cells), `pc` (pus cell), `pcc` (pus cell clumps), `ba` (bacteria), `htn` (hypertension), `dm` (diabetes mellitus), `cad` (coronary artery disease), `appet` (appetite), `pe` (pedal edema), `ane` (anemia).
- **Target**: 
  - `classification` (CKD or not CKD)

## 🚀 How to Run

1.  **Clone the repository:**

    ```bash
    git clone [https://github.com/your-username/CKD.git](https://github.com/your-username/CKD.git)
    cd CKD
    ```

2.  **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the model training:**

    ```bash
    python src/train.py
    ```

4.  **Evaluate the model:**

    ```bash
    python src/evaluate.py
    ```

5.  **(Optional) Launch the app (if you have one):**

    ```bash
    streamlit run app/app.py
    ```

## 📊 Model Evaluation

The model performance is evaluated using metrics like:

-   Accuracy
-   Precision
-   Recall
-   F1-Score
-   ROC-AUC

## 🛠️ Tech Stack

-   Python 3.x
-   Pandas
-   NumPy
-   Scikit-learn
-   Matplotlib
-   Seaborn
-   Streamlit / Flask (optional for deployment)

## 📈 Future Work

-   Hyperparameter tuning
-   Cross-validation
-   Deployment to cloud platforms (AWS, GCP, etc.)
-   Model explainability using SHAP/LIME

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is licensed under the MIT License.

## Contact
For any queries, contact me sai.subbu.in@gmail.com

---
**Author:** Sai Subba Rao Mahendrakar  
**Date:** 26 February 2025  
