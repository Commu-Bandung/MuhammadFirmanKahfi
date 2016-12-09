<h2 align="center">BAB III <br> ANALISIS DAN PERANCANGAN </h2>
<strong>3.1 Analisis</strong>
<br>
Tahap analisis adalah tahap pemahaman terhadap suatu aplikasi yang telah dibuat. Dalam tahap ini bertujuan untuk mengetahui sistem dari aplikasi tersebut, proses-proses yang terlibat dalam aplikasi serta hubungan antar proses. Analisis juga sebagai penguraian atau penjelasan dari sebuah aplikasi yang utuh kedalam bagian-bagian komponennya dengan maksud untuk mengidentifikasi dan mengevaluasi masalah-masalah, kesempatan-kesempatan, hambatan-hambatan yang terjadi serta kebutuhan yang diharapkan sehingga terdapat usulan untuk perbaikan.
Analisis adalah langkah awal untuk pengembangan aplikasi, karena perancangan dan pengembangan implementasi aplikasi tidak akan berjalan dengan baik tanpa adanya analisa terhadap aplikasi yang akan digunakan. Analisis juga dapat didefinisikan sebagai penguraian dari suatu sistem informasi yang utuh kedalam bagian-bagian komponennya dengan tujuan serta maksud untuk mengidentifikasi dan mengevaluasi masalah-masalah, kesempatan-kesempatan, hambatan-hambatan yang terjadi serta kebutuhan- kebutuhan yang diharapkan sehingga dapat diusulkan recovery atau perbaikan.
Langkah-langkah yang harus dilakukan dalam tahap analisis sistem, yaitu :
<br>
1.	Pengenalan atau identifikasi masalah, langkah ini merupakan langkah awal yang harus dilakukan, yaitu dengan mengidentifikasi permasalahan yang ada sehingga sasaran yang ingin dicapai dapat terlaksana.
<br>
2.	Memahami kerja dari sistem yang ada, langkah ini dilakukan dengan mempelajari secara rinci bagaimana jalannya sistem yang sudah ada.
<br>
3.	Menganalisis hasil penelitian, hal yang perlu diperhatikan dalam tahapan ini adalah menganalisis kebutuhan informasi pemakai sistem berdasarkan data yang diperoleh atas dasar hasil penelitian.
<br>
4.	Membuat laporan penelitian, merupakan tahap akhir yang disusun dalam suatu rangkuman dari langkah-langkah sebelumnya.

<strong>3.1.1	Analisis Sistem Yang Sedang Berjalan </strong> 
<br>
    &nbsp;&nbsp;&nbsp;3.1.1.1	Analisis Prosedur/Flowmap yang Berjalan
<p align="center">
  <img src="../../img/laporan/Proses_berjalan.PNG">
</p>

<h4 align="center">Proses yang sedang berjalan</h4>

<p align="center">
  <img src="../../img/laporan/Sub_login.PNG">
</p>


<h4 align="center">Sub Login</h4>
&nbsp;&nbsp;&nbsp;

3.1.1.2 Analisis Dokumen yang digunakan

Dalam proses pembuatan Aplikasi Pencarian Sponsorship dan Partnership pada antara Organisasi/Komunitas Kampus dengan Perusahaan  (Sub Modul Pengelolaan Sponsor dari Perusahaan dan Partnership , ada beberapa dokumen dari Perusahaan yang terlibat dan digunakan, antara lain : 
<br>
1.	Dokumen Data Perusahaan
<br>
2.	Dokumen Data Penerima Dana Sponsorship.
<br>
3.	Dokumen Data Kerjasama dengan Organisasi/Komunitas Kampus

&nbsp;&nbsp;&nbsp;3.1.2	Analisis Sistem  yang akan dibangun
<br>
&nbsp;&nbsp;&nbsp;Analisis Prosedur/Flow Map yang dibangun
<br>

<p align="center">
  <img src="../../img/laporan/Proses_dibangun.PNG">
</p>
<h4 align="center">Bisnis prosses yang akan dibangun</h4>

&nbsp;&nbsp;&nbsp;3.1.2.2 Analisis Kebutuhan Aplikasi
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Aplikasi Pencarian Sponsorship dan Partnership pada antara Organisasi/Komunitas Kampus dengan Perusahaan  (Sub Modul Pengelolaan Sponsor dari Perusahaan dan Partnership ini dibuat untuk memudahkan para perusahaan dalam melakukan pencarian penerima dana dan partnership. Sistem yang dibuat ini dapat memberikan :
<br>
		1.Pengelolaan Data Perusahaan
        <br>
		2.Pengelolaan Data Dana
        <br>
		2.Pengelolaan Data Partnership

3.1.2.3	Analisis Kebutuhan Perangkat Lunak dan Perangkat Keras
<br>
3.1.2.3.1	Analisis Kebutuhan Perangkat Lunak
Spesifikasi perangkat lunak yang dibutuhkan adalah sebagai berikut :
<br>
Tabel 3.1 Spesifikasi Perangkat Lunak
<br>

No.|	Jenis	 |	Keterangan
------------ | ------------- | ------------- |
1	| Sistem Operasi	|	Microsoft Windows 10 Pro 64bit
2	| Bahasa Pemrograman 	|  Framework Laravel PHP,Java,Javascript,Angular JS, Node JS, Express JS 
3	| Database 	| 	MySQL,Firebase,Google Cloud Platform
4	| Perangkat Lunak	| 	Visual Studio Code, Atom , Android Studio IDE

3.1.3	Analisis Kebutuhan Perangkat Keras
Pembuatan Sistem Informasi ini menggunakan perangkat keras sebagai berikut:
<br>
Tabel 3.2 Spesifikasi Perangkat Keras
<br>

No| Jenis| Keterangan
------------ | ------------- | ------------- |
1 | Processor| Intel® core™i3 
2 | Memory | 4 GB
3 | Monitor | LCD 14,1 Inchi
4 | Mouse dan keyboard | Standard

3.2	Perancangan
<br>
3.2.1	Use Case Diagram
Diagram Use Case dari aplikasi  ini adalah sebagai berikut :

<p align="center">
  <img src="../../img/laporan/usecase.PNG">
</p>
<h4 align="center">Use Case Diagram</h4>

Tabel 3.3. Definisi Aktor
<br>
No|	Aktor| Keterangan
------------ | ------------- | ------------- |
1 |	Anggota Perusahaan |	Anggota dari Perusahaan yang akan memberikan dana sebagai Member mempunyai hak akses untuk mereview proposal dan memberikan bantuan pendanaan dan bantuan Opsional.
2 |	Admin |	Mempunyai hak akses untuk memvalidasi syarat pendaftaran baik Perusahaan maupun Organisasi dan Distribusi Proposal
3 |	Organisasi |	Pengguna dari Organisasi yang mempunyai hak akses Mengirim Proposal dan Menerima Bantuan dari Perusahaan.

Tabel 3.4. Definisi Use Case
<br>
No|	Aktor| Keterangan
------------ | ------------- | ------------- |
1 |	UC-01 Registrasi | Mendaftarkan Perusahaan beserta persyaratannya
2	| UC-02 Login |	Proses Login
3	| UC-03 Kelola Proposal |	Menerima Proposal yang dikirim dari Organisasi
4	| UC-04 Review Proposal |	Mereview Proposal yang telah masuk ke perusahaan
5 |	UC-05 Beri Bantuan |	Memberikan Bantuan berupa dana setelah mereview proposal
6 |	UC-06 Beri Opsional |	Memberikan bantuan selain dana yaitu kerjasama atau penjualan produk dari perusahaan
7 |	UC-07 Validasi Persyaratan |	Memeriksa persyaratan pendaftaran dan validasi baik dari perusahaan maupun organisasai
8 |	UC-08 Distribusi Proposal |	Mengirim Proposal Proposal yang sudah divalidasi oleh admin ke perusahaan yang dituju
9 |	UC-09 Kirim Proposal |	Anggota dari Organisasi mengajukan proposal.
10 |	UC-10 Terima Bantuan |	Organisasi yang akan mengadakan suatu acara akan menerima bantuan dari Perusahaan jika proposal sudah diterima.



