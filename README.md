# SCREENSHOT KODE PROGRAM IONIC CRUD MAHASISWA

## Tampilan Awal
<img src="https://github.com/user-attachments/assets/255df3f3-b69c-4774-b4be-a97415bdb582" width="180" height="360"/><br>

## Menambah (Create) Data Mahasiswa
<img src="https://github.com/user-attachments/assets/4df5935b-fd53-4cef-a111-178da6f8a8f7" width="180" height="360"/>
<img src="https://github.com/user-attachments/assets/88413136-802c-4ad4-8fa6-8d8ff6eae367" width="180" height="360"/><br>
<p>Gambar sebelah kiri menunjukkan tampilan awal ketika Memencet tombol tambah Mahasiswa. Disitu akan menampilkan form input yang menyuruh pengguna memasukkan Nama dari mahasiswa dan jurusannya. Setelah diisi data maka pencet tombol Tambah Mahasiswa untuk menambah ke database.</p>
<p>Button tambah mahasiswa akan memanggil fungsi tambahMahasiswa() ketika di pencet.</p>


## Melihat (Read) Data Mahasiswa
<img src="https://github.com/user-attachments/assets/601c3e60-0e4e-4bf5-87c9-c5e7ace5a407" width="180" height="360"/><br>
<p>Gambar diatas menunjukkan tampilan seluruh data yang diambil dari database dengan fungsi getMahasiswa()</p>

## Mengubah (Update) Data Mahasiswa
<img src="https://github.com/user-attachments/assets/d8b94886-c740-419b-a292-31fb29fb2d2e" width="180" height="360"/>
<img src="https://github.com/user-attachments/assets/3bfacefc-7aa1-4f9e-9eea-d5f365b471ec" width="180" height="360"/>
<img src="https://github.com/user-attachments/assets/5d5e75b1-ee2a-4901-a889-3e44512e6347" width="180" height="360"/><br>
<p>Gambar kiri menunjukkan ketika memencet tombol edit dari halaman list mahasiswa.</p>
<p>Gambar tengah menunjukkan perubahan data yang ingin diupdate.</p>
<p>Gambar kanan menunjukkan ketika sudah berhasil update.</p>
<p>Proses Update diawali ketika memencet tombol edit, maka akan mengambil id dari data dan membuka halaman modalEdit. Selanjutnya tombol Edit Mahasiswa akan menjalankan fungsi editMahasiswa() ketika di pencet dan data pada databasae akan berubah.</p>

## Menghapus (Delete) Data Mahasiswa
<img src="https://github.com/user-attachments/assets/4de4cb25-647d-4286-8ed1-8cedb331edf3" width="180" height="360"/>
<p>Gambar menunjukkan ketika pencet tombol hapus, akan menampilkan alert apakah benar ingin menghapus data tersebut?</p>
<p>Proses hapus data ketika pencet tombol hapus, akan memanggil fungsi confirmHapus() yang akan mengambil id item dari ketika alert terbuka. Setelah alert muncul ada dua opsi, Tidak untuk role cancel dan Ya untuk role confirm. Ketika role confirm maka akan dijalankan fungsi hapusMahasiswa(). Setelah alert tertutup selectedId akan kembali menjadi null agar bisa memunculkan alert lagi.</p>

https://github.com/user-attachments/assets/03c7f4be-70e2-4cc2-a70a-5acdb6bc5e1b

