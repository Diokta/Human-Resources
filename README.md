# Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Edutech

## Business Understanding

Jaya Jaya Maju adalah perusahaan multinasional yang telah berdiri sejak tahun 2000 dan memiliki lebih dari 1000 karyawan yang tersebar di seluruh penjuru negeri. Meskipun telah tumbuh menjadi perusahaan berskala besar, Jaya Jaya Maju masih menghadapi tantangan dalam pengelolaan karyawan. Hal ini berdampak pada tingginya attrition rate atau tingkat keluar karyawan yang telah melebihi angka 10%.

Untuk menangani kondisi ini, manajer dari departemen Human Resource (HR) ingin mengidentifikasi berbagai faktor yang memengaruhi tingginya attrition rate tersebut. Selain itu, HR juga memerlukan sebuah business dashboard yang dapat digunakan untuk memantau faktor-faktor tersebut secara lebih mudah dan terstruktur. Analisis ini bertujuan untuk memberikan wawasan yang akurat terkait kondisi tenaga kerja di perusahaan dan mendukung pengambilan keputusan berbasis data.

### Permasalahan Bisnis

Berdasarkan kondisi yang terjadi di perusahaan **Jaya Jaya Maju**, berikut adalah permasalahan bisnis yang akan diselesaikan:

1. **Tingginya tingkat attrition (>10%)**
   - Jumlah karyawan yang keluar cukup signifikan dan dapat berdampak pada efisiensi serta stabilitas operasional perusahaan.

2. **Belum diketahui secara pasti faktor-faktor utama yang memengaruhi attrition**
   - Faktor seperti departemen, jabatan, usia, gender, masa kerja, pendapatan, lembur, dan promosi belum dianalisis secara menyeluruh untuk menentukan pengaruhnya terhadap attrition.

3. **Ketiadaan sistem pemantauan attrition yang terintegrasi**
   - Perusahaan belum memiliki dashboard atau alat visualisasi yang dapat digunakan untuk memantau dan menganalisis data attrition secara rutin.

4. **Kurangnya dukungan data dalam pengambilan keputusan manajer HR**
   - Keputusan strategis HR terkait retensi karyawan masih belum sepenuhnya berbasis pada analisis data yang kuat.

5. **Minimnya visualisasi attrition berdasarkan dimensi penting**
   - Tidak tersedianya gambaran visual yang menjelaskan distribusi attrition menurut kategori seperti departemen, job role, usia, gender, dan lainnya, yang menyulitkan dalam identifikasi pola risiko.


### Cakupan Proyek

Proyek ini memiliki cakupan sebagai berikut:

1. **Analisis Data Karyawan**
   - Mengolah dan menganalisis data historis karyawan untuk mengidentifikasi pola dan tren attrition.
   - Fokus pada variabel-variabel yang relevan seperti departemen, jabatan, usia, gender, pendapatan, lembur, promosi terakhir, masa kerja, dan work-life balance.

2. **Identifikasi Faktor-Faktor yang Mempengaruhi Attrition**
   - Menentukan faktor-faktor utama yang berkorelasi dengan tingginya attrition rate di perusahaan.

3. **Pembuatan Visualisasi Interaktif**
   - Membuat berbagai grafik dan visualisasi (bar chart, heatmap, boxplot, line chart, dll.) untuk menampilkan distribusi dan pola attrition berdasarkan dimensi yang berbeda.

4. **Pengembangan Business Dashboard**
   - Menyusun sebuah dashboard interaktif yang dapat digunakan oleh manajer HR untuk memantau faktor-faktor attrition secara real-time.


### Persiapan

Sumber data: [Employee Data](https://github.com/dicodingacademy/dicoding_dataset/tree/main/employee)

Setup environment:

Seluruh dependensi (library dan versi yang digunakan) untuk menjalankan proyek ini telah ditentukan dalam file `requirements.txt`.

File ini memastikan bahwa lingkungan pengembangan yang digunakan tetap konsisten, sehingga analisis data dan pembuatan dashboard dapat dijalankan tanpa konflik versi pustaka.

Untuk menginstal seluruh dependensi dari file `requirement.txt` jalankan perintah :

```
pip install -r requirements.txt

```

## [Business Dashboard](https://public.tableau.com/shared/6KTDZDFJ3?:display_count=n&:origin=viz_share_link)

Dashboard ini dikembangkan untuk membantu manajer HR dalam memantau, menganalisis, dan memahami faktor-faktor yang memengaruhi tingginya attrition rate (tingkat keluar karyawan) di perusahaan **Jaya Jaya Maju**. Dashboard terbagi menjadi beberapa tab utama, masing-masing menyajikan insight dari aspek yang berbeda.

### 1. Overview

Berisi informasi ringkasan kunci terkait kondisi tenaga kerja:

- **Total Karyawan:** 1.058 orang  
- **Total Karyawan yang Keluar:** 179 orang  
- **Attrition Rate:** 16.92%  
- **Rata-rata Lama Bekerja:** 7.065 tahun  
- **Departemen dengan Attrition Tertinggi:** Research & Development (107 karyawan keluar)

Tab ini memberikan gambaran cepat dan menyeluruh tentang kondisi attrition di perusahaan.

### 2. Demografi dan Peran Karyawan

Menyajikan analisis attrition berdasarkan atribut personal dan peran kerja:

- **Attrition Rate by Department**: Sales memiliki proporsi attrition tertinggi.
- **Attrition Rate by Job Role**: Posisi Sales Representative dan Laboratory Technician menonjol sebagai jabatan dengan attrition tinggi.
- **Attrition Rate by Marital Status**: Karyawan berstatus *Single* memiliki kemungkinan keluar yang lebih tinggi.
- **Attrition Berdasarkan Usia dan Gender**: Karyawan usia <25 tahun, khususnya perempuan, merupakan kelompok paling rentan.

Insight dari tab ini membantu identifikasi kelompok rentan dari sisi demografi dan struktur organisasi.

---

### 3. Kepuasan dan Lingkungan Kerja

Menampilkan hubungan antara lingkungan kerja, pelatihan, dan attrition:

- **Attrition Rate by Job Satisfaction**: Kepuasan kerja rendah berkorelasi dengan attrition tinggi.
- **Attrition Rate by Environment Satisfaction**: Semakin tidak puas terhadap lingkungan kerja, semakin tinggi kemungkinan keluar.
- **Attrition Rate by WorkLifeBalance**: Skor keseimbangan kerja-hidup rendah memiliki attrition tertinggi (WLB = 1).
- **Attrition vs PerformanceRating**: Tidak menunjukkan perbedaan signifikan.
- **Attrition Rate by TrainingTimesLastYear**: Karyawan yang tidak mendapat pelatihan memiliki attrition lebih tinggi.

Tab ini menunjukkan pentingnya pengelolaan lingkungan kerja dan pengembangan karyawan terhadap retensi.

---

### 4. Kompensasi dan Lembur

Menganalisis keterkaitan antara kompensasi, beban kerja, dan attrition:

- **Attrition Rate by Income**: Karyawan dengan gaji <3K mengalami attrition tertinggi.
- **Attrition Rate by OverTime**: Karyawan yang lembur memiliki tingkat keluar jauh lebih tinggi dibandingkan yang tidak lembur.
- **Attrition Rate by Distance From Home**: Semakin jauh tempat tinggal, semakin tinggi kecenderungan keluar.
- **Attrition by Gender across Job Level**: Perempuan di level 1 (entry-level) menunjukkan attrition tertinggi.

Insight ini penting untuk merancang strategi kompensasi, pengaturan beban kerja, dan kebijakan fleksibilitas kerja.

Dashboard yang telah dibuat dapat dilihat [DI SINI](https://public.tableau.com/shared/6KTDZDFJ3?:display_count=n&:origin=viz_share_link)

## Conclusion

Proyek analisis attrition karyawan di perusahaan **Jaya Jaya Maju** telah berhasil dilaksanakan dengan tujuan utama untuk mengidentifikasi faktor-faktor penyebab tingginya tingkat keluar karyawan (*attrition*) dan menyediakan alat bantu pemantauan berupa **business dashboard** interaktif.

### Temuan Utama

Berdasarkan analisis yang dilakukan terhadap data karyawan, diperoleh beberapa temuan signifikan:

- **Tingkat attrition perusahaan sebesar 16.92%** dari total 1.058 karyawan.
- Karyawan yang paling berisiko keluar adalah:
  - **Usia muda (<25 tahun)**, khususnya **perempuan**.
  - **Status lajang (Single)**.
  - **Pendapatan bulanan rendah (<3K)**.
  - **Sering lembur (OverTime = Yes)**.
  - **Tinggal jauh dari kantor**.
  - **Jabatan tertentu** seperti *Sales Representative* dan *Laboratory Technician*.
  - **Departemen Sales dan Research & Development (R&D)**.
  - **Skor kepuasan kerja dan work-life balance yang rendah**.
  - **Minim pelatihan dan promosi** dalam beberapa tahun terakhir.

### Hasil Pengembangan Dashboard

Dashboard interaktif yang dibangun mencakup beberapa tab analisis utama:
- **Overview**: Ringkasan data utama seperti total karyawan, attrition rate, dan rata-rata lama bekerja.
- **Demografi dan Peran Karyawan**: Analisis berdasarkan usia, gender, status pernikahan, jabatan, dan departemen.
- **Kepuasan dan Lingkungan Kerja**: Analisis faktor kepuasan kerja, lingkungan kerja, work-life balance, dan pelatihan.
- **Kompensasi dan Lembur**: Analisis berdasarkan pendapatan, lembur, jarak dari rumah, dan job level.

Dashboard ini membantu manajemen HR:
- Memantau dan memahami tren attrition secara real-time.
- Mengidentifikasi area dan kelompok berisiko tinggi.
- Mendukung pengambilan keputusan berbasis data.

### Kesimpulan Utama

Proyek ini berhasil memberikan **wawasan berbasis data** yang komprehensif terhadap faktor-faktor penyebab attrition di Jaya Jaya Maju. Dengan adanya dashboard, perusahaan kini memiliki alat visual yang dapat digunakan untuk:

- **Memantau pola attrition secara rutin**
- **Merancang strategi retensi yang lebih efektif**
- **Mengurangi tingkat keluar karyawan secara terarah**


### Rekomendasi Action Items

Berikut adalah langkah-langkah strategis yang disarankan untuk mengatasi tingginya tingkat attrition di perusahaan:

### 1. Tingkatkan Retensi pada Karyawan Muda
- Buat program onboarding dan mentoring khusus untuk karyawan usia <25 tahun.
- Sediakan jalur karier dan peluang pengembangan yang jelas sejak awal masa kerja.
- Lakukan survei kepuasan awal untuk karyawan baru (0–6 bulan) secara berkala.

### 2. Evaluasi dan Sesuaikan Struktur Kompensasi
- Tinjau kembali skema gaji, terutama untuk karyawan dengan penghasilan <3K.
- Lakukan benchmarking eksternal untuk memastikan daya saing kompensasi.
- Pertimbangkan insentif berbasis kinerja atau loyalitas jangka pendek.

### 3. Tingkatkan Work-Life Balance
- Kurangi beban lembur yang berlebihan.
- Evaluasi beban kerja pada posisi dengan attrition tinggi.
- Terapkan kebijakan fleksibilitas kerja (remote/hybrid atau jam kerja yang lebih fleksibel) jika memungkinkan.

### 4. Perbaiki Sistem Promosi dan Pengembangan Karier
- Tinjau kembali karyawan yang belum mendapat promosi dalam 5+ tahun.
- Buat program promosi internal berbasis pencapaian dan masa kerja.
- Pastikan proses promosi bersifat transparan dan terkomunikasikan dengan baik.

### 5. Perluas dan Perkuat Program Pelatihan
- Pastikan semua karyawan mendapatkan akses pelatihan minimal 1 kali per tahun.
- Kembangkan program pengembangan kompetensi berdasarkan kebutuhan tiap departemen.

### 6. Atasi Tantangan Jarak Tempuh Kerja
- Identifikasi karyawan dengan jarak rumah >20 km dan tawarkan opsi penyesuaian jam kerja atau relokasi tim.
- Evaluasi kemungkinan subsidi transportasi atau dukungan operasional lainnya.

### 7. Gunakan Dashboard Secara Aktif
- Jadikan dashboard attrition sebagai alat monitoring mingguan/bulanan di level HR dan manajer departemen.
- Lakukan evaluasi periodik terhadap kelompok dengan risiko tinggi.

### 8. Fokus pada Jabatan dan Departemen Berisiko Tinggi
- Identifikasi akar penyebab attrition tinggi di jabatan *Sales Representative* dan *Laboratory Technician*.
- Lakukan FGD (Focus Group Discussion) atau exit interview untuk menggali insight lebih dalam.
