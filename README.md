# DasarAlgoritmaDanPemrograman-BisDig
tugas 1 rekursi faktorial_py
Fungsi rekursif adalah fungsi yang memanggil dirinya sendiri.
Dalam menghitung faktorial, rekursi bekerja dengan memecah masalah menjadi sub-masalah yang lebih kecil (n! = n × (n-1)!).
Kasus dasar (base case) adalah ketika n = 0 atau 1, yang mengembalikan 
Input: Menerima bilangan bulat non-negatif
Proses: Rekursi dengan base case dan recursive case, Setiap panggilan rekursif mengurangi masalah hingga mencapai base case
Output: Menampilkan hasil perkalian berantai dari bilangan tersebut

tugas 2 sistem input nilai tertinggi_py
Input:
Kumpulan nilai dalam list
Harus divalidasi untuk memastikan data benar
Karakteristik Input:
Nilai berupa angka (bisa desimal)
Diinput secara berurutan untuk 5 siswa
Contoh input valid: 85.5, 90, 77.25
Contoh input invalid: "A", [90], -100 (harus divalidasi)
Proses:
Mencari nilai maksimal dengan max()
Menentukan pemilik nilai dengan .index()
(Alternatif: Bisa menggunakan perulangan manual)
Mencari Nilai Maksimal:

Fungsi max() mencari nilai tertinggi dalam list

Contoh: Untuk input [85, 90, 77, 90, 88] → 90

Mencari Posisi Siswa:
Method .index() mencari posisi nilai tertinggi pertama
+1 karena indeks Python dimulai dari 0
Contoh: Nilai 90 di posisi indeks 1 dan 3 → output "siswa ke-2"
Output:
Menampilkan hasil dalam format jelas
Bisa dikembangkan dengan statistik tambahan (rata-rata, dll)

tugas 3 kasir_sederhana.py
Program dimulai dengan menampilkan header
Variabel total_harga diinisialisasi dengan nilai 0 untuk menyimpan akumulasi harga
Perulangan for digunakan untuk meminta input harga 3 barang:
range(1, 4) menghasilkan urutan 1, 2, 3
Setiap harga yang diinput ditambahkan ke total_harga menggunakan operator +=
Hasil total ditampilkan dengan format mata uang (Rp) dan 2 digit desimal

tugas 4 syarat lulus.py
Penjelasan Program
Program meminta input 3 nilai mata pelajaran dengan validasi:
Memastikan input berupa angka (menggunakan try-except)
Memastikan nilai antara 0-100 (menggunakan if)
Menghitung rata-rata:

sum() untuk menjumlahkan semua nilai

len() untuk mendapatkan banyaknya mata pelajaran

Operator / untuk membagi jumlah nilai dengan jumlah mata pelajaran

Menentukan kelulusan:
Operator >= untuk membandingkan rata-rata dengan batas kelulusan (75)
Percabangan if-else untuk menentukan status
Menampilkan output:
Rata-rata dengan 2 digit desimal (:.2f)

 tugas 5 ecommerce_py
Penjelasan Logika:
Struktur Percabangan (if-else):
Kondisi: total_belanja > 500000
Jika True:
Hitung diskon 10% (total_belanja * 0.1)
Hitung total bayar setelah diskon
Jika False:
Tidak ada diskon (diskon = 0)
Total bayar = total belanja awal
Operasi Matematika:
Perkalian (*) untuk menghitung diskon
Pengurangan (-) untuk menghitung total akhir
Status kelulusan
