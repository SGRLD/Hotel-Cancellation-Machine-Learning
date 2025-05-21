Proyek ini merupakan bagian dari capstone machine learning yang berfokus pada perbandingan, evaluasi, dan optimasi berbagai model klasifikasi menggunakan metrik utama ROC AUC. 
Tujuan utama dari proyek ini adalah membangun model yang mampu membedakan dua kelas secara efektif, dengan fokus pada meminimalkan False Negative.


Tujuan Proyek:
Melakukan loading dan preprocessing dataset klasifikasi dunia nyata.

Melakukan benchmarking terhadap beberapa model machine learning:
  
  Logistic Regression
  K-Nearest Neighbors (KNN)
  Decision Tree
  Random Forest
  XGBoost
  LightGBM

Mengevaluasi performa model menggunakan:
  
  ROC AUC Score
  Confusion Matrix
  Precision, Recall, F1-Score

Melakukan tuning hyperparameter (GridSearchCV) pada model terbaik.

Menyimpan model terbaik menggunakan Pickle untuk keperluan deployment.


Temuan Utama
Performa terbaik diperoleh dari XGBoost setelah tuning hyperparameter.
Nilai ROC AUC meningkat hingga ~0.89, dengan penurunan False Negative yang signifikan.
Analisis confusion matrix menunjukkan sensitivitas terhadap kelas positif meningkat (True Positive naik, False Negative turun).


Tools & Library yang Digunakan
Python
Scikit-learn
XGBoost

LightGBM

Pandas, NumPy, Matplotlib

Jupyter Notebook
