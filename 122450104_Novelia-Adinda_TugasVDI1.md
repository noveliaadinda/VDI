## Novelia Adinda // 122450104 // RB

### Tugas Resume Artikel

### Judul Artikel : Making data visualization more efficient and effective: a survey

#### Pendahuluan

Data visualization adalah cara untuk mengubah data yang abstrak menjadi
representasi visual agar memudahkan manusia memahaminya. Visualisasi
data sangat tepat untuk menjabarkan secara garis besar tentang data yang
besar serta memudahkannya dalam merepresentasikan hasil analisis data
tersebut. Visualisasi data juga berkembang dengan pesat karen kontribusi
dari banyak komunitas, seperti komunitas grafis komputer yang membuat
teknologi visualisasi yang menarik, komunitas visualisai yang
menyediakan alat, komunitas basis data yang meningkatkan pengalaman
pengguna dalam berinteraksi secara real-time dan banyak komunitas
lainnya. Visualisasi data juga banyak digunakan dalam berbagai aplikasi
terkait basis data seperti salah satunya Google Sheets.

Visualisasi data Pipeline mempunyai beberapa alur sebagai berikut :

1\. Data Import, untuk mengambil data dari sumber yang diinginkan

2\. Data Preparation, untuk mempersiapkan data yang akan
divisualisasikan seperti menormalisasikan serta lainnnya.

3\. Data Manipulation, memfilter data dan melakukan beberapa operasi
umum seperti join dan lainnya.

4\. Mapping, untuk melakukan pemetaan data ulang yang bersumber dari
proses sebelumnya.

5\. Rendering, untuk mengubah data geometri menjadi representasi visual.

Selain itu, Terdapat beberapa Poin penting dalam Visualisasi data ini,
yaitu

-   Spesifikasi Visualisasi : Memungkinkan user untuk menentukan hasil
    yang diinginkan dan menghubungkannnya dengan visualisasi kepada
    komunitas.

-   Pendekatan efisiensi dalam evaluasi data: Melibatkan user dalam
    Pipeline yang iteratif, proses pembuatan visualisasi data yang harus
    efisien dan terukur terutama pada dua komponen utamanya yaitu “Data
    Manipulation” dan “Mapping”.

-   Rekomendasi Visualisasi Data : Sistem visualisasi penting agar dapat
    memberikan panduan yang efektif dengan beberapa rekomendasi.

#### Spesifikasi Visualiasi

A. Spesifikasi dari visualisasi data

Secara umum, dalam visualisasi data memiliki 3 bagian yaitu Data, Tanda,
serta Mapping atau Pemetaan. Dengan operasi visual berbasis GUI yang
biasanya dijabarkan sebagai DVL atau Data Visualization Languages.

B. Kategorisasi dari DVL

Strategi yang umum untuk mengkategorikan DVL dari pengekspresiannya dan
kemudahan dalam penggunaannya, serta membedakan bahasa tingkat rendah
seperti Prefuse dan Flare memerukan pengguna untuk menentukan elemen
visualisasi dalam mapping secara jelas dan bahasa tingkat tinggi seperti
ggplot2 dan VegaLite yang menyederhanakan proses spesifikasi visualisasi
yang menyatukan berbagai detail sehingga memudahkan pengguna. Intinya
bahasa tingkat tinggi lebih memprioritaskan Aksesibilitas user dengan
mengorbankan beberapa ekspresivitas dibandingkan dengan opsi tingkat
rendah yang menawarkan fleksibilitas dan konrtol yang lebih besar.

C. Operasi Visual berbasis GUI Operasi Visual ini mengikuti prinsip yang
bertujuan memberikan user cara yang ramah untuk menentukan visualisasi
dengan alat berbasis GUI seperti Tabelau, Qlik dan lainnya. Meskipun
operasi visual yang berbasis GUI ini menyederhanakan proses spesifikasi
untuk user yang lebih luas, tetapi kurang fleksibel dalam visualisasi
yang lebih rumit.

D. Spesifikasi yang tidak jelas

Banyak Visualisasi yang gagal memberikan wawasan jika user tidak
mengerti tentang data yang disajikan terutama pada data yang besar dan
dinamis. Oleh karena itu, kebutuhan sistem yang mendukung spesifikasi
yang tak terperinci ada, dimana user memberikan input parsial dan sistem
akan merepresentasikannya dengan banyak cara.

Terdapat Tiga jenis petunjuk yang digunakan :

-   Petunjuk berbasis Referensi

-   Petunjuk berbasis Kata Kunci (keyword)

-   Petunjuk berbasis Kesamaan/Jarak

#### Pendekatan Efisiensi untuk Visualisasi Data

Terkadang menyediakan suatu visualisasi yang eksak tidak selalu
menguntungkan karena data yang besar yang fokusnya terhadap masalah
iteratif dalam visualisasi data, Aproksimasi Visualisasi tentunya ideal
dalam menyelesaikan hal ini.

Terdapat Tiga Kategori utama dalam visualisasi, yaitu :

1\. Visualisasi data yang Tepat Pembuatan

Visualisasi yang akurat dan cepat, biasanya menggunakan teknik untuk
mengoptimalkan interaksi antara sistem visualisasi dengan basis data.

2\. Aproksimasi Visualisasi Data

Pendekatan ini memberikan wawasan yang lebih cepat dengan memanfaatkan
teknik yang mencakup pemrosesan kuery aproksimasi (AQP), pengambilan
sampel secara bertahap, serta menggabungkan presepsi manusia agar
menawarkan visualisasi dengan cepat.

3\. Visualisasi Data secara Progresif

Metode ini meningkatkan pengalaman user secara bertahap untuk
menyempurnakan visualisasi dengan agregasi hierarkis. Metode ini juga
memungkinkan pengguna menjelajahi data dengan tingkat detail yang
berbeda lalu secara bertahap akan meningkatkan resolusi visualisasi
berdasarkan interaksi pengguna dan permintaan data. Secara keseluruhan,
pendekatan-pendekatan diatas bekerja sama untuk meningkatkan efisiensi
dan efektivitas dalam proses visualisasi data.

#### Rekomendasi Visualisasi

Sistem Rekomendasi Visual bertujuan untuk mempermudah proses pembuatan
visualisasi yang efektif, berikut pendekatan yang dilakukan :

-   Rekomendasi yang berbasis Spesifikasi

    Dimana sistem dapat menangani spesifikasi yang kosong atau parsial.
    Contohnya tools seperti Voyager dan DeepEye.

-   Rekomendasi yang berbasis Perilaku

    Sistem seperti HARVEST menganalisa perilaku user untuk menyimpulkan
    rekomendasi visualisasi tersebut sedemikian. Dengan memahami
    tindakan user, sistem ini dapat menyarankan output visual relevan
    yang pas untuk user gunakan.

-   Rekomendasi yang di Personaliasi

    Memanfaatkan riwayat perilaku pengguna, dengan sistem seperti
    VizDeck yang melatih model untuk memberikan saran visualisasi yang
    disesuaikan berdasarkan interaksi sebelumnya. Hal ini membantu
    meningkatkan pengalaman pengguna dengan menawarkan visualisasi yang
    selaras dengan prefensi individu user.

    Dengan demikian, Sistem visualisasi yang direkomendasi ini
    mengkombinasikan masukan dan perilaku user menganalisis untuk
    menyarankan visualisasi yang efektif.

#### Arah Penelitian Lainnya

Berdasarkan Inti dari Teknik Visualisasi, beberapa bidnag penelitian
yang belum dieksplorasi tetapi memiliki potensi yang signifikan :

-   Persiapan data untuk Visualisasi :

    Membersihkan dan menyiapkan data sebelum visualisasi adalah hal yang
    krusial, karena kualitas data yang buruk membuat presepsi yang tidak
    baik.

-   Tolak Ukur dalam Visualisasi Data :

    Menetapkan tolak ukur kinerja dan rekomendasi dalam sistem
    visualisasi yang serupa dengan pengenalan gambar yang akan membantu
    dalam menilai efisiensi dan efektivitas teknik visualisasi.

-   Visualisasi Data dalam penerapan database :

    Penerapan ini dapat memperoleh manfaat dari representasi visual yang
    akan meningkatkan pemahaman dan menyelesaikan masalah secara
    efektif.

    Peluang Penelitian

    Research Opportunities

    1.  Visualisasi Data untuk mencari Penemuan Data

        Mencari kebutuhan untuk penemuan kumpulan data yang menarik dari
        suatu data yang sangat besar. Tantangannya terletak dalam
        pemahaman tentang kumpulan data yang ditemukan dengan cepat
        tanpa menghabiskan waktu menjelajahi berbagai kumpulan data
        tersebut. Visualisasi data ini dapat memebrikan gambaran yang
        dapat membantu proses penemuan data ini.

    2.  Visualisasi Data untuk Debugging Data

        Kebutuhan untuk debugging data yang efektif, dimana kesalahan
        output dalam analisis data mungkin dapat berasal dari data itu
        sendiri dan bukan dari bug dalam pemrograman.

#### Kesimpulan

Pentingnya metode visualisasi data yang efisien menekankan perlunya
teknik visualisasi data yang diperkirakan dan progresif untuk mengelola
tantangan yang ditimbulkan oleh volume data yang besar selagi
memungkinkan interaksi yang ramah oleh user. Pentingny penyesuaian
rekomendasi visualisasi berdasarkan perilaku dan prefensi user
diutamakan, menunjukkan bahwa dengan sistem tersebut dapat meningkatkan
pengalaman pengguna secara signifikan. Dengan memanfaatkan berbagai
teknik termasuk metode berbasis pengambilan sample serta algoritma
machine learning, alat visualisasi dapat menawarkan keluaran yang lebih
efektif dan intuitif. Integrasi pengenalan niat user dan kemampuan
eksplorasi data dalam menandai kemajuan penting dalam menjadikan
visualisasi data yang lebih responsif terhadap kebutuhan user dari waktu
ke waktu. Kebutuhan berkelanjutan akan inovasi dalam Visualisasi Data
untuk memenuhi kebutuhan user yang berlimpah data.
