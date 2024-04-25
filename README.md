# Capstone_2

# NYC TLC TRIP RECORD 

### **Latar Belakang**


New York City (NYC) memiliki salah satu sistem transportasi yang paling kompleks dan padat di dunia, dengan jutaan perjalanan yang dilakukan setiap hari melalui berbagai mode transportasi, termasuk taksi. The NYC Taxi and Limousine Commission (NYC TLC) merupakan lembaga pemerintah Kota New York yang memberi lisensi dan mengatur industri taksi medali dan kendaraan sewaan, termasuk perusahaan berbasis aplikasi seperti Uber dan Lyft. Lanskap peraturan TLC mencakup taksi medali (kuning), taksi hijau atau Boro taxi, mobil hitam (termasuk layanan tradisional dan berbasis aplikasi), mobil livery berbasis komunitas, van komuter, kendaraan paratransit (ambulet), dan beberapa limosin mewah. (Wikipedia)

Data ini, yang dikumpulkan oleh NYC Taxi and Limousine Commission (TLC), memberikan gambaran mendalam tentang kegiatan perjalanan taksi di kota tersebut, mencakup aspek-aspek penting seperti lokasi penjemputan dan pengantaran, biaya, jarak, dan durasi perjalanan.

Dalam industri transportasi seperti layanan taksi, biaya tambahan sering dikenakan untuk mengatasi biaya operasional tertentu atau untuk merespons kondisi pasar, seperti jam sibuk atau malam hari. Dalam konteks data ini, biaya tambahan ini bisa sangat bervariasi dan memiliki dampak signifikan terhadap biaya total yang harus dibayar oleh penumpang. Memahami kapan dan bagaimana biaya tambahan ini dikenakan penting untuk semua stakeholder, termasuk perusahaan taksi, regulator, dan tentu saja pelanggan

**Masalah**

Pengenaan biaya tambahan lain-lain mungkin tidak selalu jelas atau konsisten, menyebabkan ketidakpuasan pelanggan dan potensial penurunan dalam penggunaan layanan taksi. Pelanggan mungkin merasa keberatan jika biaya tambahan terasa tidak adil atau tidak terduga. Untuk perusahaan taksi, penting untuk mengoptimalkan strategi penetapan harga ini agar tetap kompetitif sekaligus memastikan keberlanjutan operasional.

Pertanyaan Masalah:
1. Bagaimana korelasi antara biaya tambahan individu dan total biaya perjalanan?

2. Apakah ada tren waktu tertentu seperti waktu dalam hari atau hari dalam seminggu ketika biaya tambahan lebih sering atau lebih besar dikenakan?

3. Bagaimana perbandingan antara biaya tambahan yang dikenakan di berbagai wilayah penjemputan dan pengantaran?

4. Bagaimana pengaruh dari fitur-fitur lainnya terhadap biaya tambahan lainnya?

**Goals**

1. Menganalisis pengaruh masing-masing biaya tambahan terhadap total biaya yang dibayar penumpang. Hal ini akan membantu menilai seberapa signifikan setiap biaya tambahan dalam kontribusi terhadap total biaya.

2. Mengidentifikasi pola dalam penerapan biaya tambahan berdasarkan waktu penjemputan, yang bisa membantu dalam mengoptimalkan strategi penetapan harga dan mungkin mengurangi kejutan biaya untuk penumpang.

3. Mengidentifikasi apakah ada variasi geografis dalam penerapan biaya tambahan, yang mungkin mencerminkan perbedaan dalam kebijakan lokal atau biaya infrastruktur

4. Mengidentifikasi apakah fitur-fitur lain dapat memengaruhi biaya tambahan

### **Kesimpulan**

1. Biaya tambahan memainkan peran krusial dalam menentukan struktur tarif keseluruhan dan secara langsung mempengaruhi jumlah yang harus dibayar oleh pelanggan. Biaya-biaya ini seringkali merupakan refleksi dari biaya operasional langsung (seperti tol dan biaya kemacetan) serta nilai tambahan yang diberikan kepada pelanggan

2. Biaya tambahan yang berfluktuasi berdasarkan waktu menunjukkan responsivitas sistem tarif terhadap dinamika permintaan dan kondisi operasional. Jam sibuk dan akhir pekan, yang secara tradisional merupakan waktu puncak untuk layanan taksi, memerlukan penyesuaian tarif untuk mengelola permintaan yang tinggi dan kondisi lalu lintas yang padat

3. Lokasi penjemputan dan pengantaran memiliki dampak yang kuat terhadap biaya tambahan yang dikenakan, mengindikasikan bahwa faktor geografis dan kebijakan lokal sangat mempengaruhi struktur tarif taksi. Perbedaan ini menuntut pendekatan yang disesuaikan untuk penetapan tarif di berbagai wilayah untuk memastikan keadilan dan keberlanjutan operasional

4. Berdasarkan kolom tertentu:
    - Tarif khusus seperti JFK dan Newark memiliki biaya tambahan yang lebih tinggi, terutama tolls_amount dan congestion_surcharge, yang mencerminkan biaya tambahan akibat lokasi atau kebutuhan spesifik rute
    - Ada hubungan positif antara jarak perjalanan dan biaya seperti tolls_amount. Perjalanan yang lebih jauh cenderung menarik biaya tambahan yang lebih tinggi, terutama biaya tol
    - Pembayaran dengan kartu kredit sering kali memiliki biaya tambahan yang lebih tinggi dibandingkan dengan pembayaran tunai. Transaksi kartu kredit lebih mudah untuk dikenakan biaya tambahan karena kemudahan pelacakan dan pemrosesan
  
   [Link Tableau](https://public.tableau.com/views/NYCTLC_17140629468140/Total?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)
