# Home-Credit-Indonesia---Default-Prediction-Credit-Scoring
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
