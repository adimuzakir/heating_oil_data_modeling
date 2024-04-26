# Estimasi Kebutuhan Minyak Pemanas 
## Deskripsi Proyek
Proyek ini bertujuan untuk mengestimasi jumlah minyak pemanas (heating oil) yang perlu disediakan untuk memenuhi permintaan pelanggan baru. Dengan estimasi ini, perusahaan penjualan regional dapat merencanakan persediaan yang tepat dan menghindari kelebihan atau kekurangan stok minyak pemanas. 
## Tujuan Proyek
1. Mengestimasi kebutuhan minyak pemanas untuk pelanggan baru dan pelanggan yang sudah ada.
2. Mengidentifikasi faktor-faktor yang mempengaruhi penggunaan minyak pemanas.
3. Mengembangkan model prediktif untuk memperkirakan kebutuhan minyak pemanas.
4. Menilai akurasi model yang digunakan untuk estimasi.
5. Memberikan rekomendasi untuk jumlah minyak pemanas yang perlu disediakan.
## Langkah-Langkah Proyek
1. Pemahaman Data
    - Mengimpor data pelanggan dari file CSV dan memeriksa struktur serta atributnya.
    - Mengidentifikasi variabel independen (Insulation, Temperature, dll.) dan variabel dependen (kebutuhan minyak pemanas).
    - Mengidentifikasi nilai yang hilang dan memperbaiki inkonsistensi dalam data.
2. Analisis Eksploratif
    - Membuat visualisasi korelasi untuk mengidentifikasi hubungan antara variabel independen dan kebutuhan minyak pemanas.
    - Menentukan variabel mana yang memiliki pengaruh signifikan terhadap penggunaan minyak pemanas.
3. Pemodelan Data
    - Memisahkan data menjadi set pelatihan dan set pengujian (70% pelatihan, 30% pengujian).
    - Menerapkan dua algoritma pembelajaran mesin untuk estimasi: Linear Regression dan ANN (Artificial Neural Network).
    - Mengukur kinerja model dengan metrik seperti R² dan Mean Absolute Percentage Error (MAPE).
4. Model Terbaik dan Implementasi
    - Memilih model terbaik berdasarkan MAPE, yang menunjukkan tingkat kesalahan prediksi.
    - Menggunakan model terbaik untuk mengestimasi kebutuhan minyak pemanas bagi pelanggan baru.
    - Menyimpan hasil prediksi dalam file CSV untuk analisis lebih lanjut.
## Hasil dan Temuan
- **Model Terbaik**: Linear Regression yang menunjukkan tingkat kesalahan yang lebih rendah dibandingkan model ANN.
- **Faktor-Faktor yang Mempengaruhi Penggunaan Minyak Pemanas**: Insulation memiliki korelasi positif, sedangkan Temperature memiliki korelasi negatif dengan kebutuhan minyak pemanas. Jumlah penghuni rumah (Num_Occupants) memiliki korelasi yang lemah.
- **Estimasi untuk Pelanggan Baru**: Total kebutuhan minyak pemanas yang diprediksi untuk 42.650 pelanggan baru adalah sekitar 8.377.333 liter.
- **Kebutuhan Pelanggan yang Sudah Ada**: Untuk 1.218 pelanggan yang sudah ada, kebutuhan minyak pemanas adalah sekitar 240.462 liter.
## Kesimpulan
Proyek ini membantu perusahaan penjualan regional untuk mengestimasi kebutuhan minyak pemanas bagi pelanggan baru dan pelanggan yang sudah ada. Dengan informasi ini, perusahaan dapat memastikan persediaan minyak pemanas yang cukup dan menghindari kelebihan atau kekurangan stok. Hasil analisis menunjukkan bahwa Linear Regression adalah model terbaik untuk estimasi, dengan tingkat kesalahan yang lebih rendah. Faktor-faktor seperti Insulation dan Temperature memiliki pengaruh signifikan terhadap kebutuhan minyak pemanas, memberikan wawasan yang berguna untuk perencanaan dan pengambilan keputusan di masa mendatang.
