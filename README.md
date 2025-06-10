# Project Machine Learning: Prediksi DEALSIZE

Proyek ini menggunakan model klasifikasi (Random Forest, XGBoost, dll) untuk memprediksi kolom `DEALSIZE`.

## Cara Menjalankan Web App (Streamlit)

1. Web app ini dibangun dengan Streamlit.
2. Model telah dilatih dan disimpan dalam file `.pkl`.
3. Web app dapat diakses secara publik melalui Streamlit Cloud.

## Struktur File

- `app.py`: Streamlit UI untuk prediksi
- `model_rf.pkl`: Model Random Forest
- `scaler.pkl`: StandardScaler (jika digunakan)
- `requirements.txt`: Daftar dependensi

## Contoh Input

Input berupa nilai-nilai fitur numerik seperti:
- `feature1`: ...
- `feature2`: ...

Output: Prediksi kategori DEALSIZE.

---

> Deploy gratis via: [https://streamlit.io/cloud](https://streamlit.io/cloud)
