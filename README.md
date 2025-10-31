# Diabetes-Prediction-using-SVM
Early prediction of diabetes can significantly reduce long-term health risks.
This project builds a Machine Learning-based diabetes prediction system using the PIMA Indian Diabetes Dataset and Support Vector Machine (SVM) algorithm.

The model analyzes medical parameters and predicts whether a person is likely to have diabetes.

PROJECT HIGHLIGHTS
| Feature             | Description                                   |
| ------------------- | --------------------------------------------- |
| 📊 Dataset          | PIMA Diabetes Dataset                         |
| 🧠 Model            | Support Vector Machine (SVM)                  |
| ⚙️ Preprocessing    | Scaling, Cleaning, EDA                        |
| ✅ Accuracy Achieved | **~76%**                                      |
| 🎛 UI               | Interactive inputs using `ipywidgets`         |
| 📈 Visuals          | Heatmap, Correlation Charts, Confusion Matrix |

Key features in dataset:
Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age.

🔧 Tech Stack: 
Python
Jupyter Notebook
Scikit-Learn
Pandas / NumPy
Matplotlib / Seaborn
ipywidgets (Interactive UI)


<img width="790" height="672" alt="image" src="https://github.com/user-attachments/assets/d5b24236-6990-487b-a3c7-30782101603a" />

<img width="538" height="374" alt="image" src="https://github.com/user-attachments/assets/5734a989-388a-46ef-a1f4-ef984e9ba4ce" />

<img width="362" height="310" alt="image" src="https://github.com/user-attachments/assets/e831191a-afc3-4638-8f8f-7265ed714325" />

<img width="416" height="452" alt="image" src="https://github.com/user-attachments/assets/61817f61-ae4e-4933-847e-39a51dee24fa" />

<img width="396" height="427" alt="image" src="https://github.com/user-attachments/assets/1f09e7ae-8bc0-403d-8ae7-ab5552c2eea6" />


Key Insights From the Diabetes Prediction Model: 

1. Glucose as the Primary Predictor
Glucose levels showed the strongest correlation with diabetes outcome in the dataset. Individuals with higher glucose values are significantly more likely to be classified as diabetic by the model. This confirms glucose as the most influential clinical parameter in predicting diabetes risk.

2. Age and BMI Influence Diabetes Risk
Age and BMI demonstrated moderate correlation with diabetes, indicating increased risk in older and overweight individuals. The scatter and heatmap analysis support this trend, with diabetic cases clustering in higher-age and higher-BMI ranges. These factors serve as important secondary contributors to the model's predictions.

3. Insulin and Skin Thickness Offer Supportive Predictive Value
Insulin and skin thickness displayed weaker but noticeable influence on the outcome. These features provide additional insight when combined with stronger indicators such as glucose and BMI. While useful, they do not independently drive prediction as strongly as primary variables.

Model Performance and Reliability:
The SVM model achieves an accuracy of approximately 79–80%, aligning with typical performance benchmarks for the PIMA dataset. It performs reliably for early-stage prediction and learning applications. However, certain diabetic cases may be misclassified, reflecting the complexity of medical prediction tasks.

Confusion Matrix Interpretation:
|                 | Predicted Negative | Predicted Positive |
| --------------- | ------------------ | ------------------ |
| Actual Negative | ✅ 85 Correct       | ❌ 12 Misclassified |
| Actual Positive | ❌ 19 Missed        | ✅ 38 Correct       |

Model identifies non-diabetic patients very well
Misses some diabetic cases (common in medical ML)
📌 Conclusion: Model is slightly conservative — err on safe side for screening.

Overall Learning Outcome:
The project demonstrates successful implementation of an SVM classifier, data preprocessing pipeline, and evaluation methods for a real-world health dataset. Results confirm that machine-learning-based screening can provide meaningful early-risk identification. The study also highlights the importance of data quality, feature engineering, and model tuning in medical prediction systems.
