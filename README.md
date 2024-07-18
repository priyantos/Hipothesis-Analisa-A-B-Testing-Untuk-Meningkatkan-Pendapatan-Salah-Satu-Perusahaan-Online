# Hipothesis-Analisa-A-B-Testing-Untuk-Meningkatkan-Pendapatan-Salah-Satu-Perusahaan-Online
**Pendahuluan <a id='intro'></a>**

Dalam project ini, saya bersama dengan tim pemasaran akan menyusun daftar hipotesis untuk membantu meningkatkan pendapatan salah satu Perusahaan Online. Tugas utama saya dalam Project adalah melakukan pemilahan dan prioritisasi terhadap hipotesis-hipotesis tersebut. Dengan menganalisa secara terstruktur, saya akan mengeksplorasi data, merumuskan hipotesis, dan menganalisa A/B Testing dan mengambil kesimpulan berdasarkan temuan saya. Proyek ini bertujuan untuk meningkatkan pendapatan dari salah satu perusahaan online.

**Tujuan:**

Project ini bertujuan untuk secara singkat meningkatkan pendapatan perusahaan online dengan melakukan pemilahan, prioritisasi, dan pengujian hipotesis melalui A/B testing serta membantu tim pemasaran guna meningkatkan pendapatan dari salah satu perusahaan online. Saya berharap melalui hasil analisis ini dapat mengidentifikasi strategi pemasaran yang efektif dan optimal untuk meningkatkan kinerja perusahaan online secara keseluruhan. 

Berikut rincian yang akan kita lewati:

**Tahapan yang Dilakukan**

**Langkah 1: Insialisasi**

- Memanggil data library yang dibutuhkan

  - *List library yang digunakan*
  
     * import pandas as pd
     * import matplotlib.pyplot as plt
     * import seaborn as sns
     * import numpy as np
     * from datetime import datetime, timedelta
     * from scipy import stats
     * from scipy.stats import levene, shapiro, ttest_ind, mannwhitneyu
     

**Langkah 2: Memuat Dataset**

* `/datasets/hypotheses_us.csv`
* `/datasets/orders_us.csv`
* `/datasets/visits_us.csv`

**Langkah 3: Melakukan Tahapan Hipothesis**

**3.1.** Memprioritaskan Hipotesis File `hypotheses_us.csv` memuat sembilan hipotesis untuk meningkatkan pendapatan perusahaan online dengan Reach, Impact, Confidence, dan Effort yang sudah ditentukan untuk masing-masing hipotesis. dengan tugas yang akan saya lakukan adalah:

  **3.1.1.** Menerapkan framework ICE untuk memprioritaskan hipotesis. Urutkan hipotesis tersebut dalam urutan prioritas menurun.
  
  **3.1.2.** Menerapkan framework RICE untuk memprioritaskan hipotesis. Urutkan hipotesis tersebut dalam urutan prioritas menurun.
  
  **3.1.3.** Menunjukkan perubahan prioritas hipotesis saat RICE diterapkan untuk menggantikan ICE. Berikan penjelasan terkait perubahan tersebut.
  
&nbsp;

**3.2.** Analisis A/B Testing Melakukan A/B testing dan mendapatkan hasil seperti yang dideskripsikan dalam file  `orders_us.csv`dan `visitors_us.csv`. Berikut sub bab yang akan dilakukan:

  **3.2.1.**  Gambarkan pendapatan kumulatif berdasarkan kelompok. Buat kesimpulan dan asumsinya.
  
  **3.2.2.**  Gambarkan ukuran pesanan rata-rata kumulatif berdasarkan kelompok. Buat kesimpulan dan asumsinya.
    
  **3.2.3.**  Gambarkan perbedaan relatif untuk ukuran pesanan rata-rata kumulatif kelompok B yang dibandingkan dengan kelompok A. Buat kesimpulan dan asumsinya.
  
  **3.2.4.**  Gambarkan konversi kumulatif berdasarkan kelompok. Buat kesimpulan dan asumsinya.
  
  **3.2.5.**  Gambarkan perbedaan relatif untuk tingkat konversi kumulatif kelompok B yang dibandingkan dengan kelompok A. Buat kesimpulan dan asumsinya.
  
  **3.2.6.**  Hitung tingkat konversi setiap kelompok sebagai rasio pesanan terhadap jumlah kunjungan setiap hari. Buat grafik tingkat konversi harian dari kedua kelompok dan jelaskan perbedaannya. Buat kesimpulan dan asumsinya.
    
  **3.2.7.**  Buat diagram tebar (scatter chart) untuk jumlah pesanan per pengguna. Buat kesimpulan dan asumsinya.
    
  **3.2.8.**  Hitung persentil ke-95 dan ke-99 untuk jumlah pesanan per pengguna. Tentukan titik ketika suatu titik data berubah menjadi anomali.
    
  **3.2.9.**  Buat diagram tebar (scatter chart) untuk harga pesanan. Buat kesimpulan dan asumsinya.
    
  **3.2.10.** Hitung persentil ke-95 dan ke-99 untuk harga pesanan. Tentukan titik ketika suatu titik data berubah menjadi anomali.
    
  **3.2.11.** Temukan signifikansi statistik perbedaan konversi antar kelompok menggunakan data mentah. Buat kesimpulan dan asumsinya.
    
  **3.2.12.** Temukan signifikansi statistik perbedaan ukuran pesanan rata-rata antar kelompok menggunakan data mentah. Buat kesimpulan dan asumsinya.
    
  **3.2.13.** Temukan signifikansi statistik perbedaan konversi antar kelompok menggunakan data yang telah difilter. Buat kesimpulan dan asumsinya.
    
  **3.2.14.** Temukan signifikansi statistik perbedaan ukuran pesanan rata-rata antar kelompok menggunakan data yang telah difilter. Buat kesimpulan dan asumsinya.
    
  **3.2.15.** Buatlah keputusan berdasarkan hasil pengujian. Keputusan yang memungkinkan adalah: 1. Menghentikan pengujian, serta mempertimbangkan salah satu kelompok sebagai pemimpin. 2. Menghentikan pengujian, serta menyimpulkan bahwa tidak ada perbedaan antara kedua kelompok. 3. Melanjutkan pengujian.
    
**Langkah 4: Kesimpulan Umum**
