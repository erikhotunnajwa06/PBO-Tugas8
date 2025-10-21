# Deskripsi Tugas
Menambahkan fitur upload file CSV untuk melakukan import data secara otomatis ke dalam aplikasi CRUD berbasis Java. Penambahan fitur upload CSV memungkinkan pengguna mengimpor data dari file eksternal (seperti data barang) ke dalam tabel database aplikasi tanpa perlu memasukkan data secara manual. 
# Langkah Implementasi 
1. Menyiapkan File CSV

Buat file berisi data yang ingin diimpor (misalnya data sembako) dengan kolom:
kode_barang, nama_barang, quantity, harga_barang.
Simpan dengan format .csv.

2. Menambahkan Tombol Upload pada JFrame

Tambahkan komponen JButton pada tampilan GUI dan beri label Upload.

3. Menambahkan Source Code untuk Button Upload

Gunakan JFileChooser untuk memilih file CSV, kemudian baca dan parsing data menggunakan kelas BufferedReader.

4. Menjalankan Aplikasi

Jalankan program, klik Upload, pilih file CSV, lalu klik Open untuk mengimpor data ke tabel CRUD.

5. Hasil
Setelah menjalankan aplikasi dan memilih file CSV, data akan otomatis tampil pada tabel GUI dan tersimpan dalam database.
# Kesimpulan
Melalui tugas ini, fitur upload file CSV berhasil ditambahkan pada project CRUD berbasis Java, sehingga pengguna dapat melakukan impor data dengan lebih cepat dan efisien. Fitur ini menunjukkan penerapan konsep PBO dalam integrasi antarmuka dan logika program yang modular. Dengan adanya penambahan ini, aplikasi CRUD menjadi lebih fungsional dan mudah digunakan, terutama dalam konteks pengolahan data dalam jumlah besar. Penerapan fitur ini juga memperkuat pemahaman terhadap konsep event handling, file I/O, dan desain antarmuka berbasis objek dalam Java.
