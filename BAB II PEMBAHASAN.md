## BAB II
## PEMBAHASAN
## 2.1  Analisis Netralitas Sistem AI
<p align="justify">&nbsp;&nbsp;&nbsp;&nbsp; Sistem rekrutmen berbasis AI yang dikembangkan Amazon pada awalnya dirancang untuk meningkatkan efisiensi dalam proses seleksi kandidat. Namun dalam praktiknya, sistem ini menunjukkan bahwa teknologi tidak selalu bersifat netral. Ketidaknetralan tersebut muncul karena AI dilatih menggunakan data historis yang didominasi oleh pelamar laki-laki, sehingga sistem secara tidak langsung menganggap bahwa kandidat laki-laki lebih sesuai dengan kebutuhan perusahaan.</p>
<p align="justify">&nbsp;&nbsp;&nbsp;&nbsp; Akibatnya, AI tidak benar-benar menilai kandidat berdasarkan kemampuan individu, melainkan berdasarkan pola yang dipelajari dari data masa lalu. Hal ini terlihat dari bagaimana sistem memberikan penalti terhadap CV yang mengandung kata “women’s” serta menurunkan nilai kandidat dari institusi pendidikan perempuan. Kondisi ini menunjukkan bahwa AI tidak memiliki pemahaman konteks sosial, melainkan hanya mereplikasi pola yang ada dalam data.</p>

## 2.2  Analisis Bias Data Historis
<p align="justify">&nbsp;&nbsp;&nbsp;&nbsp; Salah satu penyebab utama bias dalam sistem AI adalah penggunaan data historis yang tidak seimbang. Dalam kasus Amazon, data pelatihan didominasi oleh laki-laki, sehingga tidak mencerminkan keberagaman kandidat secara keseluruhan. AI kemudian menjadikan pola tersebut sebagai standar dalam menentukan kandidat ideal.</p>
<p align="justify">&nbsp;&nbsp;&nbsp;&nbsp; Proses pembelajaran mesin membuat sistem mengidentifikasi pola-pola yang dianggap berkorelasi dengan keberhasilan di masa lalu, tanpa mempertimbangkan apakah pola tersebut adil atau tidak. Akibatnya, bias yang sudah ada dalam data akan terus direproduksi. Selain itu, tidak adanya audit bias sebelum sistem digunakan semakin memperparah kondisi ini, karena kesalahan tidak terdeteksi sejak awal. </p>

## 2.3  Analisis Ketimpangan Seleksi

## 2.4  Analisis Transparansi AI
| Aspek                    | Kondisi pada Sistem AI Amazon                                      | Dampak yang Terjadi                                      |
|--------------------------|--------------------------------------------------------------------|----------------------------------------------------------|
| Model AI (Black Box)     | Tidak dapat dijelaskan secara jelas bagaimana keputusan dibuat     | Sulit mengetahui alasan penolakan kandidat              
| Akses Informasi          | Kandidat tidak mengetahui proses penilaian CV                      | Menimbulkan ketidakpercayaan terhadap sistem
| Deteksi Bias             | Tidak dilakukan audit awal secara menyeluruh                       | Bias gender tidak terdeteksi sejak awal
| Akuntabilitas            | Tidak ada mekanisme pertanggungjawaban yang jelas                  | Sulit menentukan pihak yang bertanggung jawab
| Evaluasi Sistem          | Fokus pada akurasi, bukan transparansi                             | Ketidakadilan tidak segera diperbaiki

<p align="justify">&nbsp;&nbsp;&nbsp;&nbsp; Berdasarkan tabel di atas, dapat dilihat bahwa tingkat transparansi dalam sistem AI rekrutmen Amazon masih sangat rendah. Sistem yang bersifat black box menyebabkan proses pengambilan keputusan tidak dapat dipahami secara jelas, baik oleh pengembang maupun pengguna. Hal ini berdampak pada sulitnya mendeteksi bias yang terjadi serta tidak adanya kejelasan mengenai alasan suatu kandidat diterima atau ditolak. </p>

<p align="justify">&nbsp;&nbsp;&nbsp;&nbsp; Kurangnya transparansi juga berpengaruh terhadap akuntabilitas sistem, di mana tidak terdapat pihak yang secara jelas bertanggung jawab atas keputusan yang dihasilkan oleh AI. Kondisi ini menunjukkan bahwa transparansi merupakan aspek penting dalam pengembangan AI, terutama dalam sistem yang digunakan untuk pengambilan keputusan yang berdampak besar seperti rekrutmen tenaga kerja.</p>

## 2.5  Analisis Dampak Gender

## 2.6  Analisis Tanggung Jawab Pengembang
<p align="justify">&nbsp;&nbsp;&nbsp;&nbsp; Dalam pengembangan sistem AI, pengembang memiliki tanggung jawab besar untuk memastikan bahwa teknologi yang dibuat tidak merugikan masyarakat. Namun, dalam kasus ini terlihat bahwa tanggung jawab tersebut belum sepenuhnya dijalankan dengan baik.</p>

<p align="justify">&nbsp;&nbsp;&nbsp;&nbsp; Kurangnya pengujian terhadap potensi bias menunjukkan bahwa aspek keadilan belum menjadi prioritas utama dalam proses pengembangan. Selain itu, minimnya transparansi dalam sistem juga menandakan bahwa mekanisme pertanggungjawaban belum dirancang secara optimal. Hal ini menjadi pelajaran penting bahwa pengembangan teknologi tidak hanya berfokus pada kinerja sistem, tetapi juga harus disertai dengan tanggung jawab profesional dan etika.</p>

## 2.7  Solusi
<p align="justify">&nbsp;&nbsp;&nbsp;&nbsp; Untuk mengatasi permasalahan bias dalam sistem rekrutmen berbasis AI, langkah utama yang perlu dilakukan adalah memastikan bahwa data yang digunakan dalam proses pelatihan bersifat representatif dan tidak memihak kelompok tertentu. Data harus mencerminkan keberagaman kandidat, baik dari segi gender, latar belakang pendidikan, maupun pengalaman kerja, sehingga sistem tidak hanya belajar dari pola masa lalu yang sudah bias.</p>

<p align="justify">&nbsp;&nbsp;&nbsp;&nbsp; Selain itu, perusahaan perlu melakukan audit algoritma secara berkala untuk mendeteksi potensi bias sejak dini. Proses evaluasi ini tidak hanya berfokus pada tingkat akurasi, tetapi juga harus memperhatikan aspek keadilan (fairness). Di samping itu, peningkatan transparansi sistem menjadi penting agar proses pengambilan keputusan dapat dipahami dan dipertanggungjawabkan. Penerapan konsep <i>human-in-the-loop</i> juga diperlukan, di mana keputusan akhir tetap melibatkan manusia sebagai pengawas. Dengan kombinasi antara teknologi dan pertimbangan manusia, diharapkan sistem dapat menghasilkan keputusan yang lebih adil, akurat, serta meminimalkan risiko diskriminasi dalam proses rekrutmen.</p>
