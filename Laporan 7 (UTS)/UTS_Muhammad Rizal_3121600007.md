|<p></p><p></p><p></p><p></p><p></p><p>![logo pens color edge](https://raw.githubusercontent.com/rizal15D/Tugas-Pratikum-Konsep-Jaringan-/main/Laporan%207%20(UTS)/asset/01.png)**                                                                         </p>|<p>**Ujian Tengah Semester**</p><p>**Semester Ganjil Tahun Ajaran 2022/2023**</p><p>**PROGRAM STUDI D4 TEKNIK INFORMATIKA** </p><p>**DEPARTEMEN TEKNIK INFORMATIKA DAN KOMPUTER**</p><p>**POLITEKNIK ELEKTRONIKA NEGERI SURABAYA**</p><p>**Kampus PENS Raya ITS Keputih Sukolilo, Surabaya 60111**</p>|
| - | -: |
|**Mata Kuliah**|: Prakt. Konsep Jaringan|**Dosen**|: Ferry Astika Saputra |
|**Kelas**|: 2 D4 TI A|**Sifat**|: Terbuka|
|**Durasi Waktu/Jam  Pelaksanaan** |:  70 Menit, 13:40 – 14:50|**Hari/Tgl**|:  Selasa, 4 Oktober 2022|
|**Nama :** Muhammad Rizal||**NIM :** 3121600007||

Diketahui desain sebuah jaringan 2 lantai digambarkan dalam Gambar 1.  Sedangkan konfigurasi detil terdapat pada Tabel 1. Tugas anda adalah mengkonfigurasi seluruh perangkat sehingga seluruh PC yang ada dapat saling terhubung. Buatlah simualsinya dengan menggunakan packet tracer. 

![](https://raw.githubusercontent.com/rizal15D/Tugas-Pratikum-Konsep-Jaringan-/main/Laporan%207%20(UTS)/asset/02.png)

*Gambar 1. Topologi jaringan 2 lantai.*

*Table 1. Detil konfigurasi setiap perangkat.*

![](https://raw.githubusercontent.com/rizal15D/Tugas-Pratikum-Konsep-Jaringan-/main/Laporan%207%20(UTS)/asset/03.png)

Setelah anda berhasil mengkonfigurasi seluruh perangkat dan terhubung satu sama lain, maka salin konfigurasi yang ada dan beri penjelasan singkat dari konfigurasi yang telah anda lakukan ! 

![](https://raw.githubusercontent.com/rizal15D/Tugas-Pratikum-Konsep-Jaringan-/main/Laporan%207%20(UTS)/asset/04.png)

**Konfigurasi Router0**



|<p>Salinan file konfigurasi (ambil yang menurut anda penting) :</p><p>![](https://raw.githubusercontent.com/rizal15D/Tugas-Pratikum-Konsep-Jaringan-/main/Laporan%207%20(UTS)/asset/05.png)</p><p>IPv4 Router0 = 192.168.1.1</p><p></p>|
| - |
|<p>Penjelasan :</p><p>Router0 fastethernet 0/0 terhubung Switch0 dengan menggunakan kabel copper cross-over.</p><p>IPnya pada router 192.168.1.1 ,</p><p></p><p></p><p></p><p></p><p></p>|

**Konfigurasi Switch0**

|<p>Salinan file konfigurasi (ambil yang menurut anda penting) :</p><p>![\](https://raw.githubusercontent.com/rizal15D/Tugas-Pratikum-Konsep-Jaringan-/main/Laporan%207%20(UTS)/asset/06.png)</p>|
| - |
|<p>Penjelasan :</p><p>Switch0 = Trunk</p><p>Switch menggunakan trunk sehingga dapat akses menyeluruh</p><p></p><p></p><p></p><p></p><p></p>|

**Konfigurasi Switch1**

|<p>Salinan file konfigurasi (ambil yang menurut anda penting) :</p><p>![](https://raw.githubusercontent.com/rizal15D/Tugas-Pratikum-Konsep-Jaringan-/main/Laporan%207%20(UTS)/asset/07.png)</p>|
| - |
|<p>Penjelasan :</p><p>Antar switch adalah trunk</p><p></p><p></p><p></p><p></p><p></p><p></p>|

