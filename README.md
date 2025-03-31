# Home-Credit-Indonesia---Default-Prediction-Credit-Scoring

![Salinan dari Sales Report Presentation](https://github.com/user-attachments/assets/e071b5a0-90f6-4755-86e9-e28b1f1d65d7)

Dalam industri financial, setiap keputusan pemberian kredit adalah taruhan antara keuntungan dan risiko. Salah prediksi bisa berarti dua hal:
1. False Positive (Memberikan pinjaman kepada yang seharusnya ditolak): Bank menanggung kerugian miliaran rupiah akibat kredit macet.
2. False Negative (Menolak nasabah yang sebenarnya layak): Bank kehilangan pelanggan potensial dan pendapatan jangka panjang.**

Padahal, data nasabah kini semakin kompleks:

- Tren fintech mengubah perilaku peminjam.
- Variabel non-tradisional (seperti jejak digital atau transaksi e-commerce) sulit diinterpretasi model klasik.
- Regulasi ketat menuntut keputusan yang adil dan terjelaskan (explainable AI).

Tantangan:
- Model canggih seperti LGBM akurat tetapi black-box (sulit dijelaskan ke regulator).
- Logistic Regression transparan tetapi kurang tangkap pola kompleks.

Solusi yang diusulkan:
Membangun hybrid scoring system yang menggabungkan kekuatan kedua model:

70% bobot pada LGBM untuk akurasi prediksi.
30% bobot pada Logistic Regression untuk interpretabilitas.

Dengan pendekatan ini, perusahaan pendanaan seperti HCI dapat:
- Minimalkan kerugian dengan mengurangi false positive.
- Jaga kepuasan nasabah dengan mengurangi false negative.
- Penuhi regulasi karena tetap mempertahankan logika yang bisa dijelaskan.


![Salinan dari Sales Report Presentation (1)](https://github.com/user-attachments/assets/ac064d6c-1cb2-4567-a225-cbb73bd188ab)


![Salinan dari Sales Report Presentation (2)](https://github.com/user-attachments/assets/e3ce4477-b9c2-4955-a4c2-2e7d7efe5bbe)



