# DasarAlgoritmaDanPemrograman-BisDig
Ujian Tengah Semester (UTS) Vara Desvita Maharani (24110310086) 2A Bisnis Digital

penjelasan dalam soal UTS

1. Struktur kontrol percabangan (if-else) digunakan untuk menentukan apakah diskon akan diberikan atau tidak. Logikanya sederhana:
- Memeriksa Total Belanja: Program pertama-tama memeriksa apakah total belanja pelanggan melebihi Rp500.000.
- Menerapkan Diskon (jika memenuhi syarat): Jika total belanja melebihi Rp500.000 (if bernilai benar), program menghitung diskon 10% dari total belanja dan mengurangi diskon tersebut dari total belanja untuk mendapatkan total pembayaran setelah diskon.
- Tidak Memberikan Diskon (jika tidak memenuhi syarat): Jika total belanja kurang dari atau sama dengan Rp500.000 (else), tidak ada diskon yang diberikan, dan total pembayaran sama dengan total belanja.
  

2. Dalam menentukan kelulusan siswa berdasarkan rata-rata nilai 3 mata pelajaran, tipe data dan operator memainkan peran penting dalam perhitungan dan representasi data.
   - Tipe Data:
float (atau double dalam beberapa bahasa): Tipe data ini paling tepat untuk merepresentasikan nilai ujian karena nilai ujian bisa berupa angka desimal (misalnya, 75.5). Menggunakan int (bilangan bulat) akan menghilangkan informasi desimal, yang mungkin penting dalam perhitungan rata-rata. Jika sistem hanya menerima nilai bulat, maka int bisa digunakan.
int: Tipe data ini bisa digunakan jika sistem hanya menerima nilai ujian sebagai bilangan bulat.
float untuk rata-rata: Hasil perhitungan rata-rata juga sebaiknya direpresentasikan sebagai float untuk menjaga akurasi desimal.

   - Operator:
Operator Aritmatika:
+ (penjumlahan): Digunakan untuk menjumlahkan nilai tiga mata pelajaran.
/ (pembagian): Digunakan untuk membagi jumlah nilai dengan 3 (jumlah mata pelajaran) untuk memperoleh rata-rata.
Operator Perbandingan:
>= (lebih besar dari atau sama dengan): Digunakan untuk membandingkan rata-rata nilai dengan nilai ambang batas kelulusan (misalnya, 70). Hasil perbandingan ini akan menghasilkan nilai boolean (True atau False).


3. Manfaat Penggunaan Fungsi:

Fungsi menawarkan beberapa keuntungan signifikan dalam pemrograman:
- Modularitas: Fungsi memecah program menjadi bagian-bagian yang lebih kecil, lebih mudah dikelola, dan lebih mudah dipahami. Ini meningkatkan keterbacaan dan mengurangi kompleksitas kode.
- Reusabilitas: Fungsi dapat dipanggil berulang kali dari bagian yang berbeda dari program, menghindari duplikasi kode dan mengurangi usaha pemrograman.
Kemudahan Pemeliharaan: Jika ada kesalahan atau perlu perubahan, Anda hanya perlu mengubah kode di dalam fungsi, bukan di setiap tempat fungsi tersebut digunakan.
- Abstraksi: Fungsi menyembunyikan detail implementasi dari bagian lain program. Anda hanya perlu tahu apa yang dilakukan fungsi, bukan bagaimana fungsi tersebut melakukannya.
Pengorganisasian Kode: Fungsi membantu mengorganisir kode menjadi blok-blok logis yang sesuai dengan tugas-tugas tertentu.

Bagaimana Rekursi Bekerja dalam Menghitung Faktorial:
Rekursi adalah teknik pemrograman di mana sebuah fungsi memanggil dirinya sendiri. Dalam konteks menghitung faktorial, ini bekerja sebagai berikut:
Kasus Dasar (Base Case): Rekursi harus memiliki kasus dasar, yaitu kondisi yang menghentikan pemanggilan fungsi berulang. Dalam faktorial, kasus dasarnya adalah ketika angka yang diberikan adalah 0 atau 1. Faktorial dari 0 dan 1 adalah 1.
Langkah Rekursif (Recursive Step): Jika angka yang diberikan bukan kasus dasar, fungsi memanggil dirinya sendiri dengan angka yang lebih kecil (biasanya dikurangi 1). Ini adalah langkah rekursif. Hasil pemanggilan rekursif ini kemudian dikalikan dengan angka awal.


4. Penggunaan Array/List:

Array (atau list di Python) digunakan untuk menyimpan nilai dari kelima siswa. Setiap elemen dalam array merepresentasikan nilai seorang siswa. Ini memungkinkan kita untuk mengakses dan memproses nilai-nilai tersebut secara sistematis.
Penggunaan Perulangan:
Perulangan digunakan untuk:
Input Nilai: Perulangan for atau while digunakan untuk meminta input nilai dari masing-masing siswa. Perulangan akan berjalan sebanyak jumlah siswa (5 dalam kasus ini).
Mencari Nilai Tertinggi: Setelah semua nilai telah diinput dan disimpan dalam array, perulangan digunakan lagi untuk iterasi melalui array dan membandingkan setiap nilai dengan nilai tertinggi yang telah ditemukan sejauh ini. Nilai tertinggi akan diperbarui setiap kali ditemukan nilai yang lebih besar.


5. Algoritma untuk menghitung total harga pembelian 3 barang:
Langkah-langkah Algoritma:
- Inisialisasi Variabel:
Buat tiga variabel untuk menyimpan harga masing-masing barang (misalnya, harga1, harga2, harga3). Inisialisasi variabel-variabel ini dengan nilai 0 atau nilai awal lainnya jika diperlukan.
Buat variabel total_harga untuk menyimpan total harga pembelian. Inisialisasi dengan nilai 0.
- Input Harga Barang:
Minta pengguna untuk memasukkan harga barang pertama (harga1). Gunakan mekanisme input yang sesuai (misalnya, fungsi input() di Python).
Minta pengguna untuk memasukkan harga barang kedua (harga2).
Minta pengguna untuk memasukkan harga barang ketiga (harga3).
Lakukan validasi input untuk memastikan bahwa input adalah angka (bukan teks atau karakter lain yang akan menyebabkan error).
- Hitung Total Harga:
Jumlahkan harga ketiga barang: total_harga = harga1 + harga2 + harga3.
- Tampilkan Total Harga:
Tampilkan nilai total_harga kepada pengguna. Gunakan mekanisme output yang sesuai (misalnya, fungsi print() di Python).
