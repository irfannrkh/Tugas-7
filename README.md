# Tugas-7
Program ini dibuat untuk membantu memvalidasi berat barang yang akan dikirim. User diminta untuk memasukkan berat barang dalam satuan kilogram. Program akan memeriksa apakah berat tersebut valid (lebih dari 0 dan tidak melebihi batas maksimal pengiriman). Jika berat tidak valid, maka program akan menampilkan pesan error menggunakan teknik exception handling.

Tujuan dari program ini adalah untuk melatih penggunaan try–catch, throw, dan throws di Java dalam menangani input yang tidak valid dari user. Dengan exception handling, program akan tetap berjalan dengan aman tanpa crash walaupun user memasukkan input yang salah atau tidak sesuai.

Tipe Exception yang Digunakan
1. NumberFormatException
Terjadi saat user memasukkan input selain angka (misalnya huruf atau karakter khusus).

2. OverweightException (Custom Exception)
Dibuat khusus untuk memeriksa apakah berat barang:

- Melebihi batas maksimal (50 kg), atau

- Kurang dari atau sama dengan nol (≤ 0)

3.  Exception (Umum)
Menangani error tidak terduga lainnya yang mungkin terjadi saat program berjalan.
