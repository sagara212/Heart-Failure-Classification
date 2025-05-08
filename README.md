---

# ❤️‍🩺 **Heart Failure Prediction using Tree Ensemble**

Proyek ini bertujuan untuk membangun model Machine Learning berbasis **Tree Ensemble** untuk memprediksi kemungkinan penyakit jantung berdasarkan data klinis pasien. Model ini diharapkan dapat membantu deteksi dini penyakit jantung sehingga penanganan medis bisa dilakukan lebih cepat dan tepat.

---

## 📂 **Dataset**

* Dataset diperoleh dari Kaggle:
  🔗 [Heart Failure Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)

---

## 📚 **Konteks**

> Penyakit kardiovaskular (CVD) adalah penyebab utama kematian di seluruh dunia dengan estimasi 17.9 juta kematian setiap tahun. Sebanyak 4 dari 5 kematian CVD disebabkan oleh serangan jantung dan stroke.

Deteksi dini sangat penting, terutama bagi mereka yang memiliki faktor risiko seperti hipertensi, diabetes, dan kolesterol tinggi. Proyek ini bertujuan membangun model prediksi yang dapat digunakan sebagai alat bantu diagnosis.

---

## 🔢 **Fitur Dataset**

* **Age**: Usia pasien
* **Sex**: Jenis kelamin (M/F)
* **ChestPainType**: Jenis nyeri dada
* **RestingBP**: Tekanan darah saat istirahat
* **Cholesterol**: Kadar kolesterol
* **FastingBS**: Gula darah puasa (> 120 mg/dl = 1)
* **RestingECG**: Hasil EKG saat istirahat
* **MaxHR**: Denyut jantung maksimal
* **ExerciseAngina**: Angina akibat latihan
* **Oldpeak**: Depresi ST
* **ST\_Slope**: Kemiringan segmen ST
* **HeartDisease**: Label target (1 = positif penyakit jantung)

---

## 🧠 **Model & Metodologi**

Model yang digunakan termasuk:

* 🌳 **Decision Tree**
* 🌲 **Random Forest**
* ⚡ **XGBoost**

### ✅ **Hasil Terbaik: Random Forest**

📋 **Classification Report**:

| Metric    | Class 0 | Class 1 |
| --------- | ------- | ------- |
| Precision | 0.86    | 0.89    |
| Recall    | 0.86    | 0.89    |
| F1-score  | 0.86    | 0.89    |

🎯 **Akurasi keseluruhan**: **88%**
🔍 **Fitur paling berpengaruh**: Age, MaxHR, Cholesterol, ChestPainType, dll.

---

## 🛠️ **Tools & Library**

* **Python** (Jupyter Notebook)
* **Scikit-learn** – modeling & evaluasi
* **XGBoost**, **RandomForestClassifier**
* **Pandas**, **NumPy** – pengolahan data
* **Matplotlib**, **Seaborn** – visualisasi

---


## 🧩 **Insight Proyek**

✅ Model Tree Ensemble unggul dalam klasifikasi biner
✅ Bisa digunakan untuk prototipe aplikasi diagnosa dini
✅ Hasil visualisasi dan evaluasi mudah dipahami tenaga medis

---

🎉 **Terima kasih telah membaca! Jika proyek ini bermanfaat, jangan lupa beri ⭐ dan fork repo ini!**
🤝 *Open for collaboration, feedback, or deployment ideas!*

---
