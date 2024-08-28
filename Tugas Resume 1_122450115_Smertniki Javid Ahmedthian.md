Nama:Smertniki Javid Ahmedthian
NIM:122450115
Kelas:RA

Making data visualization more efficient and effective: a survey

Abstrak
Visualisasi data sangat penting dalam dunia bisnis berbasis data saat ini, yang telah digunakan secara luas untuk membantu pengambilan keputusan
yang berkaitan erat dengan pendapatan utama banyak perusahaan industri. Namun, karena tingginya permintaan pemrosesan data
volume, kecepatan, dan kebenaran data, ada kebutuhan yang muncul untuk ahli basis data untuk membantu agar efisien dan
visualisasi data yang efektif. Menanggapi permintaan ini, artikel ini mensurvei teknik-teknik yang membuat visualisasi data menjadi lebih
efisien dan efektif. (1) Spesifikasi visualisasi mendefinisikan bagaimana pengguna dapat menentukan kebutuhan mereka untuk menghasilkan
visualisasi. (2) Pendekatan yang efisien untuk visualisasi data memproses data dan spesifikasi visualisasi yang diberikan, yang
kemudian menghasilkan visualisasi dengan target utama untuk menjadi efisien dan terukur dengan kecepatan interaktif. (3) Visualisasi data
rekomendasi untuk melengkapi spesifikasi yang tidak lengkap secara otomatis, atau untuk menemukan visualisasi yang lebih menarik berdasarkan
visualisasi referensi.

1.Pengantar
Visualisasi data, yang mengubah data abstrak menjadi bentuk fisik(misalnya, panjang, posisi, bentuk, warna, dan
dan sebagainya), adalah cara yang ampuh untuk menyajikan cerita yang menarik dari
yang menarik dari data kepada manusia yang lebih berorientasi pada visual.Visualisasi data sangat cocok untuk memberikan gambaran yang baik
gambaran umum yang baik tentang data yang sangat besar, dan membuatnya lebih mudah untuk ditafsirkan
hasil analisis data kepada para ilmuwan data.

Pipeline visualisasi data:
 1. Import data mengambil data yang diperlukan dari sumber data yang dibutuhkan
 sumber data yang dibutuhkan.
 2. Data Preparation adalah mempersiapkan data yang diimpor untuk
 visualisasi, misalnya dengan menormalkan nilai, mengoreksi
 entri yang salah, dan menginterpolasi nilai yang hilang.
 3. Data Manipulation adalah memilih data yang akan divisualisasikan
 (alias penyaringan dari komunitas visualisasi) dan
 mungkin dengan operasi umum lainnya seperti penggabungan
 dan pengelompokan.
 4. Mapping adalah memetakan data yang diperoleh dari proses di atas
 proses di atas ke primitif geometris (misalnya, titik dan garis),
 bersama dengan atributnya (misalnya, warna, posisi, dan
 ukuran).
 5. Rendering adalah mengubah data geometris menjadi representasi visual

Berdasarkan pipeline tersebut, telah diidentifikasi tiga hal yang membuat visualisasi data menjadi lebih efisien dan efektif
(1) Spesifikasi Visualisasi 
Spesifikasi visualisasi menyediakan berbagai cara agar pengguna dapat menentukan apa yang mereka inginkan.
(2) Pendekatan yang Efisien untuk Visualisasi Data
Untuk melibatkan pengguna secara efektif dalam iteratif proses pembuatan visualisasi data haruslah efisien dan terukur, terutama untuk dua komponen,
"Data Manipulation” dan ”Mapping”.
(3).Rekomendasi Visualisasi Data 
Tentukan dengan tepat visualisasi yang tepat itu sulit, bahkan untuk para ahli, hanya karena 
pemahaman tentang data apa yang akan divisualisasikan, cerita apa  yang harus diceritakan, dan bagaimana memvisualisasikannya adalah latihan coba-coba.Oleh karena itu, penting bahwa visualisasi sistem visualisasi dapat memandu pengguna secara cerdas dengan memberikan rekomendasi-rekomendasi. Beberapa sistem memungkinkan pengguna untuk memberikan spesifikasi yang ambigu, dan sistem akan secara otomatis menyelesaikan visualisasi, atau memberikan rekomendasi-rekomendasi.

2.Spesifikasi visualisasi
 2.1 Spesifikasi visualisasi data
Secara umum, bahasa visualisasi data terdiri dari tiga bagian: data, tanda (atau isyarat visual), dan pemetaan di antara mereka.

Data 
Catatan: data yang perlu divisualisasikan - Transformasi: operasi-operasi - seperti group, bin,
filter, dan sortir-digunakan untuk mengubah catatan data yang ditentukan
Tanda (atau isyarat visual) - Jenis: representasi visual untuk catatan data, seperti
Ukuran: lebar, tinggi visualisasi - Legenda: informasi legenda - Lain-lain: properti lain, seperti lebar
 dan warna batang. - Pemetaan: memetakan data ke tanda yang sesuai.

Tanda (atau isyarat visual) 
-Jenis: representasi visual untuk catatan data, seperti
-Ukuran: lebar, tinggi visualisasi 
-Legenda: informasi legenda - Lain-lain: properti lain, seperti lebar

Mapping: memetakan data ke tanda yang sesuai.

2.2 Kategorisasi bahasa visualisasi data
Strategi yang umum digunakan untuk mengkategorikan visualisasi databahasa didasarkan pada ekspresifitasnya.Tampaknya, semakin rendah level suatu bahasa, semakin ekspresif bahasa tersebut. Bahasa tingkat yang lebih tinggi merangkum beberapa detail tingkat rendah dengan menyediakan default yang masuk akal dan menambahkan lebih banyak batasan
dan warna batang.
2.3 Pengoperasian visual berbasis GUI
Dibandingkan dengan menggunakan bahasa visualisasi deklaratif untuk menentukan visualisasi seperti yang telah dibahas,cara yang lebih ramah pengguna untuk memberikan spesifikasi adalah dengan mengikuti “prinsip manipulasi langsung”, sebuah konsep yang banyak digunakan dalam aspek interaksi manusia-komputer.

Visualisasi Data Interaktif
Alasan di balik visualisasi data interaktif adalah bahwa dalam banyak kasus, visualisasi data adalah proses eksplorasi, di mana pengguna perlu terus menyempurnakan spesifikasi (misalnya, menambah/menghapus/mengubah atribut, mengubah jenis bagan) dari visualisasi yang sedang dieksplorasi hingga mendapatkan visualisasi yang diinginkan dalam proses eksplorasi.

 2.4 Spesifikasi yang kurang spesifik
Visualisasi tidak ada artinya jika tidak dapat memberikan wawasan dari data. Namun, dalam banyak kasus, pengguna tidak benar-benar
mengetahui semua aspek dari data tersebut, karena data tersebut mungkin besar dan data dapat sering diperbarui.

3.Pendekatan yang efisien dan visualisasi data
3.1 Visualisasi data yang tepat
Banyak sistem visualisasi data,membaca data dari basis data, yang dapat dimanipulasi oleh pernyataan SQL dan kemudian menggunakan alat visualisasi untuk membuat visualisasi.Penerjemahan Query Cara alami untuk menggunakan kembali banyak sistem (DBMS) adalah dengan menerjemahkan kueri visualisasi ke
kueri yang diterima oleh sistem tersebut. Sebagai contoh, DeepEye, Polaris, SeeDB mendapatkan data dengan mengeluarkan SQL query ke database.Dengan membuat pemetaan antara primitif bahasa visualisasi dan bahasa SQL, kita dapat mengubah bahasa visualisasi target menjadi kueri SQL.

Mengintegrasikan Sistem Visualisasi dengan DBMS
Meskipun menggunakan penerjemahan query adalah hal yang alami, ada beberapa keuntungan. Salah satu masalah utama adalah bahwa banyak fungsi yang diulang-ulang, sehingga menghasilkan teknik optimasi yang tidak terpadu dengan asumsi dan kinerja yang berbeda di server (yaitu sisi database) dan klien (yaitu sisi visualisasi),membuat para pengembang bingung untuk memilih teknik optimasi yang sesuai teknik optimasi yang sesuai.
Masalah utama lainnya adalah bahwa metode yang dipisahkan sulit untuk dipelihara, diperluas, dan dioptimalkan untuk visualisasi interaktif, yang membutuhkan terus menerus mengeluarkan kueri untuk memodifikasi visualisasi.
Secara intuitif, cara yang menjanjikan untuk memecahkan masalah di atas adalah dengan menggabungkan (atau mengintegrasikan) pengambilan data dan rendering secara erat untuk mempercepat proses pembuatan visualisasi.

Penyimpanan Kolom 
Dalam manajemen data, faktor kinerja utama adalah tata letak data, misalnya, tata letak berbasis baris dan berbasis kolom tata letak, yang mungkin memiliki perbedaan kinerja yang sangat besar untuk Aplikasi OLAP. Dalam hal visualisasi data, pengguna biasanya hanya tertarik pada beberapa kolom saja. Secara alami,column-store dapat mencapai kinerja yang lebih baik, dibandingkan
dengan penyimpanan baris, yang telah diadopsi di SeeDB,Profiler dan TDE.

Indeks
Indeks digunakan secara luas untuk meningkatkan kinerja pencarian dengan cara mengurangi jumlah record/baris dalam tabel yang perlu diperiksa. Secara alami, mereka memainkan peran penting dalam meningkatkan kinerja visualisasi data.Sebagai contoh FlashView membangun indeks berbasis pohon hirarkis untuk mendukung pilihan pengguna dengan kondisi pemfilteran yang terus menerus.

Komputasi Paralel
Komputasi paralel juga telah digunakan secara luas untuk pemrosesan kueri dalam sistem visualisasi data. Arsitektur mempertahankan thread aplikasi utama untuk menangkap permintaan interaksi pengguna dan beberapa thread visualisasi untuk setiap visualisasi untuk memproses visualisasi ini
thread ini. Selanjutnya, apakah thread utama dan thread visualisasi bersifat asinkron atau sinkron tergantung pada jenis permintaan interaksi pengguna.

Prediksi dan Prapemrosesan
Salah satu langkah penting dalam data visualisasi data adalah eksplorasi data-pengguna terus menelusuri visualisasi yang mereka minati untuk mendapatkan gambaran tentang apa yang harus divisualisasikan
ize.Seringkali, visualisasi yang dieksplorasi saat ini biasanya terinspirasi dari yang sebelumnya.Terbukti, memprediksi data berikut yang mungkin diminati pengguna, dan kemudian melakukan prefetching/caching data yang dapat digunakan pada langkah berikutnya selama eksplorasi saat ini dapat mempercepat proses eksplorasi, dan teknik ini telah digunakan di banyak sistem visualisasi. Kami mengkategorikan teknologi pengambilan awal dan prediksi menjadi dua jenis, berdasarkan:
1. Visualisasi yang sedang dieksplorasi atau
2. Data historical

3.2 Ketika volume data tumbuh secara eksponensial
Data tradisional tidak dapat memberikan hasil pemrosesan interaktif yang cepat. Untuk menjembatani kesenjangan antara volume data dan interaktivitas fyang mempercepat fase pemrosesan data dengan memanfaatkan pemrosesan kueri perkiraan (AQP) yang memberikan perkiraan hasil visualisasi.

AQP-based
Cara yang mudah untuk menghasilkan perkiraan visualisasi dalam waktu interaktif adalah dengan memanfaatkan teknik AQP.

Incremental Sampling
Menghubungkan teknik kueri data inkremental dengan visualisasi data. Ide utama dari perkiraan visualisasi dengan pengambilan sampel sampling adalah bahwa sistem menghasilkan perkiraan visualisasi berdasarkan alisasi berdasarkan sampel yang representatif dari kumpulan data tertentu.
Kemudian, sistem meningkatkan ukuran sampel dari waktu ke waktu untuk meningkatkan kualitas visualisasi secara bertahap. 
Pengguna biasanya bisa mendapatkan beberapa wawasan awal dari perkiraan visualisasi dan memutuskan untuk mengakhiri jika kualitas
visualisasi sudah cukup untuk memverifikasi wawasan ini.

Berbasis Persepsi Manusia
Terkadang meningkatkan sampel ukuran sampel tidak selalu meningkatkan kualitas visualisasi.Alasan eksternalnya adalah bahwa jumlah piksel layar terbatas, dan alasan internalnya adalah bahwa kognitif keterbatasan persepsi manusia dalam mengidentifikasi detail kecil.Oleh karena itu, sistem visualisasi perkiraan memungkinkan untuk menghasilkan hasil perkiraan berdasarkan sampel yang representatif.
sampel tetapi dengan dampak minimal pada kualitas visualisasi.Pendekatan berbasis persepsi manusia menghentikan pengambilan sampel ketika tidak ada perbedaan yang jelas pada persepsi manusia antara perkiraan visualisasi saat ini dan visualisasi  yang akan didapat dengan pengambilan sampel lebih lanjut.

 3.3 Visualisasi data progresif 
Banyak penelitian dalam visualisasi menghasilkan hasil visualisasi yang progresif kepada pengguna.
Selain itu, visualisasi data progresif berbasis pengambilan sampel bertahap di atas, ada juga banyak penelitian yang menyediakan visualisasi progresif dengan agregasi hirarkis. 

4.Rekomendasi visualisasi 
Proses visualisasi data bersifat iteratif dan poin utama dari para praktisi adalah bahwa mereka harus terlibat dalam setiap langkah untuk membuat beberapa modifikasi. Secara alami, sangat diharapkan bahwa ada beberapa rekomendasi sosiliasi yang dapat membantu para pengguna dengan merekomendasikan visualisasi yang baik kepada mereka.

Sistem rekomendasi visualisasi dengan spesifikasi kosong, seperti Draco, Data2Vis, dan Rank-by-fitur sangat membantu pengguna untuk mengeksplorasi data dengan cepat saat pengguna tidak terlalu familiar dengan data dan visualisasi yang diinginkan. Sistem-sistem rekomendasi ini umumnya membutuhkan spesifikasi parsial, seperti kata kunci, sebagai masukan pengguna. Meskipun solusi berbasis aturan dapat mencocokkan pemahaman intuitif seseorang tentang visualisasi, tetapi tidak menghasilkan pemahaman yang lengkap tentang persepsi manusia. Solusi berbasis pembelajaran dapat mengumpulkan data pelatihan, meskipun hasilnya sulit untuk ditafsirkan. Namun, solusi berbasis pembelajaran ini dapat menangkap pengetahuan kognitif manusia tentang efektivitas visualisasi. Dengan lebih banyak data pelatihan, model pembelajaran akan menjadi lebih pintar.
Rekomendasi berbasis perilaku dapat merekomendasikan visualisasi berdasarkan tugas yang disimpulkan, tetapi terbatas padapola perilaku yang telah ditentukan sebelumnya, membuatnya tidak fleksibel untuk penggunaperilaku acak.
Rekomendasi yang dipersonalisasi berkinerja berbeda untuk pengguna yang berbeda, karena rekomendasi yang dipersonalisasi adalahdisesuaikan untuk pengguna yang berbeda dengan perilaku historis mereka.

5.Kesimpulan
Visualisasi data adalah bidang yang sedang berkembang pesat dengan penelitian dan sistem baru yang terus dikembangkan. Banyak peneliti dan praktisi dari berbagai bidang telah berkontribusi dalam mengembangkan visualisasi data yang luar biasa, dan ini juga didorong oleh berbagai domain dan aplikasi. Dalam artikel ini, penulis membahas visualisasi data terbaru dari perspektif manajemen data. Mereka mencakup karya-karya di bidang spesifikasi visualisasi, metode efisien untuk visualisasi data, dan rekomendasi visualisasi. Artikel juga mencatat bahwa kebanyakan sistem visualisasi data komersial saat ini lebih mudah digunakan dalam hal spesifikasi visualisasi data. Secara keseluruhan, visualisasi data terus berkembang dengan adanya penelitian dan sistem baru yang menjadikannya salah satu bidang yang menarik dan penting.
