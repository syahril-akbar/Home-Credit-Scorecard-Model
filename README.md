# Home Credit Scorecard Model 🏦

**Final Task - Rakamin Academy Data Scientist Internship Program**

## 📌 Project Overview
Project ini bertujuan untuk membangun model prediksi risiko kredit (*Credit Scoring*) yang dapat memprediksi probabilitas kegagalan bayar (*Probability of Default*) nasabah. Model ini membantu Home Credit dalam membuat keputusan peminjaman yang lebih akurat, aman, dan inklusif bagi populasi *unbanked*.

## 🎯 Business Objective
- **Meminimalkan NPL (Non-Performing Loan):** Menolak aplikasi yang berisiko tinggi.
- **Optimasi Profit:** Memberikan penawaran kompetitif bagi nasabah berisiko rendah.
- **Inklusi Keuangan:** Menilai nasabah tanpa riwayat kredit menggunakan data alternatif.

## 🛠️ Methodology
1.  **Preprocessing:** Handling missing values, Encoding (Label/One-Hot), Feature Scaling.
2.  **Feature Engineering:** Membuat fitur turunan seperti `CREDIT_INCOME_RATIO`, `ANNUITY_INCOME_RATIO`, dll.
3.  **Modeling:** Membandingkan Logistic Regression, XGBoost, dan LightGBM.
4.  **Evaluation:** Menggunakan metrik AUC, Precision, Recall, dan F1-Score.

## 📊 Key Findings & Results
Model terbaik yang dipilih adalah **LightGBM** dengan performa:
- **AUC Score:** 0.7660
- **Recall (Sensitivitas):** ~68%
- **F1-Score:** 0.277

**Insight Bisnis:**
- Nasabah usia muda (20-30 tahun) memiliki risiko gagal bayar lebih tinggi.
- Stabilitas pekerjaan (lama bekerja) lebih berpengaruh daripada sekadar besaran gaji.
- Rasio cicilan terhadap gaji (*Affordability*) adalah prediktor kunci.

## 📂 Repository Structure
- `Home_Credit_Scorecard_Model.ipynb`: Main notebook berisi analisis end-to-end (Preprocessing, Feature Engineering, Modeling, Evaluation).
- `README.md`: Dokumentasi dan ringkasan proyek.

---
*Created by Syahril Akbar*
