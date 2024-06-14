> ## 1.1. BACKGROUND

> Setelah beberapa tahun beroperasi, sebuah perusahaan asuransi kendaraan mengalami stagnasi dalam pendapatan tahunan. Untuk mengatasi masalah ini, perusahaan memutuskan untuk memanfaatkan data yang telah dikumpulkan guna merancang perencanaan keuangan yang optimal di masa depan. Dengan pendekatan analitis, perusahaan berupaya memahami lebih dalam tentang pelanggannya dan memprediksi nilai Customer Lifetime Value (CLV) mereka. Dengan strategi ini, perusahaan berharap dapat meningkatkan pendapatan dengan mengoptimalkan biaya kampanye  pada pelanggan yang tepat berdasarkan prediksi CLV.

> ## 1.2. STAKEHOLDER

> Analisis ini secara khusus ditujukan kepada `Tim Marketing perusahaan`, yang bertanggung jawab untuk merancang strategi kampanye untuk meningkatkan retensi pelanggan dan efisiensi biaya. Tim ini akan menggunakan hasil analisis untuk mengidentifikasi segmen pelanggan yang paling bernilai dan mengalokasikan biaya kampanye dengan lebih efektif. 

> ## 1.3. PROBLEM STATEMENT

> **Pertanyaan Bisnis Utama:** <br>
> Bagaimana cara perusahaan meningkatkan pendapatan dengan menghemat biaya kampanye menggunakan nilai prediksi CLV?
>
> **Pertanyaan Bisnis Turunan:** <br>
> 1. Bagaimana model machine learning yang tepat untuk dapat memprediksi nilai CLV pelanggan yang dapat digunakan untuk menghemat biaya kampanye?
> 2. Bagaimana segmentasi pelanggan yang tepat untuk dijadikan target kampanye berdasarkan nilai CLV dalam menghemat biaya kampanye?
            
> ## 1.4. GOALS

> Tujuan dilakukannya analisa ini yaitu untuk meningkatkan pendapatan perusahaan dengan menentukan strategi yang optimal dalam mengelola biaya kampanye lebih efisien, berdasarkan hasil prediksi nilai *Customer Lifetime Value*

> ## 1.6. CUSTOMER LIFETIME VALUE

> #### OVERVIEW
> Customer Lifetime Value adalah total pendapatan atau keuntungan yang dihasilkan oleh seorang pelanggan selama seluruh hubungan mereka dengan suatu bisnis. Dalam kasus ini, CLV adalah metrik untuk mengukur jumlah total uang yang telah dihabiskan (atau diharapkan akan dihabiskan) oleh seorang pelanggan asuransi kendaraan pada produk dan layanan, sepanjang masa sebagai pelanggan. Semakin tinggi CLV, semakin berharga seorang pembeli bagi bisnis Anda, karena mereka akan menghasilkan lebih banyak pendapatan dan lebih mungkin untuk tetap loyal.
>
> > ## 1.5. ANALYTICAL APPROACH

> Pendekatan analitik yang akan digunakan melibatkan analisis data untuk mengidentifikasi pola-pola dalam data yang ada dengan memanfaatkan model regresi menggunakan machine learning untuk membantu perusahaan asuransi kendaraan dalam menentukan strategi perencanaan keuangan yang optimal.

> ### Evaluation Metrics
> Analisa ini akan mengevaluasi model menggunakan RMSE, MAE, dan MAPE. Semakin kecil nilai metrik-metrik ini, semakin akurat model dalam memprediksi nilai *Customer Lifetime Value* (CLV) berdasarkan fitur yang digunakan.
    
> #### MAE (Mean Absolute Error)
> MAE (Mean Absolute Error) mengukur rata-rata kesalahan absolut antara prediksi dan nilai aktual. Metrik ini tidak sensitif terhadap outlier dan cocok untuk memprediksi nilai CLV (Customer Lifetime Value) karena memberikan bobot yang sama pada setiap perbedaan. Selain itu, metrik ini cenderung lebih mudah diinterpretasikan karena cara kerjanya yang lebih sederhana dan mudah dipahami oleh klien yang tidak memiliki latar belakang statistik.

> Rumus MAE adalah sebagai berikut:
> $$MAE =  \frac{\sum\nolimits_{i=1}^{n} |Y_i - \widehat{Y_i}|}{n}$$
> $$Mean Absolute Error$$
> - ∑ adalah sigma (penjumlahan dari suatu urutan atau fungsi)<br>
> - ŷi adalah nilai prediksi data ke i<br>
> - yi adalah nilai aktual data ke i<br>
> - n adalah jumlah data<br>
