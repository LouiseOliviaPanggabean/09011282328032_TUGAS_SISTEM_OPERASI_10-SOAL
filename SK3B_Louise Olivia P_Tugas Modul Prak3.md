NAMA : LOUISE OLIVIA PANGGABEAN <BR/>
NIM : 09011282328032 <BR/>
KELAS : SK3B 

# Laporan Praktikum Modul 3 SISTEM FILE
## BAB I PENDAHULUAN
### 1.1 LATAR BELAKANG
<p> Pada sistem operasi Linux, terdapat komponen yang sangat penting yaitu sistem file. Sistem file merupakan komponen fundamental dalam sistem operasi Linux yang berfungsi untuk mengorganisasi dan mengelola data dalam suatu penyimpanan sekunder.Sistem file pada Linux menyerupai pepohonan (tree), yaitu dimulai dari root, kemudian direktori dan sub direktori. Sistem file pada Linux diatur secara hirarkhikal, yaitu dimulai dari root dengan symbol “/”. Dengan demikian, struktur direktori merupakan konsep dasar dalam sistem file yang memungkinkan pengguna untuk mengatur file dan direktori secara hierarkis. Praktikum ini bertujuan untuk memberikan pemahaman yang lebih mendalam mengenai struktur direktori, cara membuat, menghapus, dan mengelola direktori, serta pentingnya struktur direktori yang baik dalam menjaga keteraturan file sistem.</p>

### 1.2 TUJUAN
-  Mengenal organisasi File di Linux
-  Menciptakan dan manipulasi direktori
-  Mempelajari ijin akses (permission) dari file dan direktori
-  Mengenal konsep Owner dan Group
-  Mengerti konsep Link dan symbolic link

### 1.3 ALAT DAN BAHAN
- Laptop
- Sistem operasi Linux
- Command Line/Terminal

### 1.4 DASAR TEORI
<p>Sistem file adalah struktur data yang digunakan oleh sistem operasi untuk mengatur dan mengelola data dalam suatu penyimpanan sekunder, seperti hard disk atau SSD. Sistem file bertanggung jawab untuk menyimpan, mengakses, dan memodifikasi data secara efisien dan aman. Salah satu komponen sistem file pada sistem operasi Linux adalah direktory. Untuk mengatur sistem file kita dapat menggunakan terminal. Hal yang dilakukan dalam sistem file yaitu membuat dan mengubah nama file/direktori, melakukan akses kontrol, mengubah jenis file, dan masih banyak lagi. Dengan demikian peran dari sistem file adalah untuk menyimpan dan mengelola data, mengelola akses ke data, menjamin integritas data dengan menggunakan fitur - fitur yang ada.  </p>

## BAB II PEMBAHASAN PRAKTIKUM FITUR SISTEM FILE PADA LINUX
### 2.1 Lihat peralatan I/O, character device, yang ada pada system komputer.
  **Melihat Peralatan I/O Secara Keseluruhan :** <p/>
  <img src="https://github.com/user-attachments/assets/46afcf56-d131-420c-bc42-1572f907f07e" width=500/><p/>
  **Melihat Hanya Character Device :** <p/>
   <img src="https://github.com/user-attachments/assets/5d139ce2-4819-45f4-bfc6-85e46431db0a" width=500/><p/>
### 2.2 Buatlah sub direktori januari, februari dan maret sekaligus pada direktori latihan5.<p/>
   <img src="https://github.com/user-attachments/assets/971d76e4-d012-4b67-b4f0-82f675297450" width=500/><p/>
### 2.3 Buatlah file dataku yang berisi nama, nim dan alamat anda pada sub direktori januari dan copy-kan file tersebut ke sub direktori februari dan maret.
  **Perintah untuk membuat file :** <p/>
   <img src="https://github.com/user-attachments/assets/b2c746d8-f988-4973-a768-192c2592aaa6" width=500/><p/>
   **Hasil :** <p/>
   <img src="https://github.com/user-attachments/assets/5694a7e8-2d1c-42e5-948b-8fdc14287ac7" width=500/><p/>
   **Perintah untuk copy file :** <p/>
   <img src="https://github.com/user-attachments/assets/bb2246f3-1545-4eb4-8381-97749adef027" width=500/><p/>
   **Hasil febuari :** <p/>
   <img src="https://github.com/user-attachments/assets/09100506-791c-403d-b737-099be3e3206d" width=500/><p/>
   **Hasil maret :** <p/>
   <img src="https://github.com/user-attachments/assets/fdd3372e-2ef4-47d4-957e-1e0abc710c4a" width=500/><p/>
### 2.4 Ubahlah ijin akses file dataku pada sub direktori januari sehingga group dan others dapat melakukan write.
   <img src="https://github.com/user-attachments/assets/69cfc219-56c0-484d-aba3-c1bccffd3ccd" width=500/><p/>
   
### 2.5 Ubahlah ijin akses file dataku pada sub direktori pebruari sehingga user dapat melakukan baik write, read maupun execute, tetapi group dan others hanya bisa read dan execute.
   <img src="https://github.com/user-attachments/assets/9f5635d3-0ae8-416b-b8b6-0edbf5742dd2" width=500/><p/>
### 2.6 Ubahlah ijin akses file dataku pada sub direktori maret sehingga semua dapat melakukan write, read dan execute.
   <img src="https://github.com/user-attachments/assets/fa619afb-021b-4c8c-8662-1be7475fbedf" width=500/><p/>
### 2.7 Hapuslah direktori maret.
   <img src="https://github.com/user-attachments/assets/b6d40e90-d1fc-4576-a8ce-75bb8b593fce" width=500/><p/>
### 2.8 Ubahkan kepemilikan sub direktori februari sehingga user dan group hanya dapatmelakukan read, dan cobalah untuk membuat direktori baru haha pada sub direktori februari.
   <img src="https://github.com/user-attachments/assets/8bff55cf-d189-45d5-8ded-74f7b67f129a" width=500/><p/>
### 2.9 Modifikasi umask dari file dataku pada sub direktori januari menjadi 027 dan berapakan nilai default-nya. 
   <img src="https://github.com/user-attachments/assets/7f341ce4-36ea-4c5d-b9b9-20d46a41252d" width=500/><p/>
### 2.10 Buatlah link dari file dataku ke file dataku.ini dan file dataku.juga dan dengan perintahlist perhatikan berapa link yang terjadi ?
   <img src="https://github.com/user-attachments/assets/3cc34b95-da60-40ef-b4d4-9534a8b165b8" width=500/><p/>
## BAB III PENUTUP
### 3.1 KESIMPULAN
Sistem file pada operasi Linux merupakan struktur data yang digunakan oleh sistem operasi untuk mengatur dan mengelola data dalam suatu penyimpanan sekunder. Yang dimana siste file bertugas dalam menyimpan dan mengelola data, mengelola akses ke data, menjamin integritas data dengan menggunakan fitur - fitur yang ada. Sistem file pada Linux menyerupai pepohonan (tree), yaitu dimulai dari root, kemudian direktori dan sub direktori. Struktur direktori merupakan konsep dasar dalam sistem file yang memungkinkan pengguna untuk mengatur file dan direktori secara hierarkis. Sehingga dalam praktikum ini, saya memperoleh pemahaman dalam mempelajari cara membuat, menghapus, dan mengelola direktori, serta pentingnya hierarki direktori dalam menjaga keteraturan file sistem. 
