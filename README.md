# Kalkulator-
Create by Elizan
1. Bahasa yang Digunakan
HTML → Untuk struktur tampilan kalkulator.
CSS → Untuk memberikan gaya pada tampilan agar lebih menarik dan responsif.
JavaScript → Untuk menangani interaksi pengguna, seperti menambahkan angka, operator, menghapus input, dan melakukan perhitungan.
2. Fitur Utama
✅ Input Angka dan Operator

Pengguna dapat memasukkan angka dari 0 hingga 9.
Operator matematika dasar tersedia (+, -, *, /).
Mendukung penggunaan titik desimal (.).
Bisa memasukkan angka nol ganda ("00").
✅ Tombol Hapus ("del")

Menghapus satu karakter terakhir dari input yang sedang diketik.
✅ Tombol Hasil ("=")

Menghitung hasil dari ekspresi matematika yang telah dimasukkan.
Menggunakan fungsi eval() untuk mengeksekusi ekspresi matematika.
✅ Penanganan Error

Jika terjadi kesalahan dalam perhitungan, layar akan menampilkan "Error" dan input akan direset.
✅ Tampilan Responsif dan Modern

Warna latar belakang abu-abu untuk tampilan minimalis.
Tata letak tombol berbasis grid untuk keseragaman.
Tombol dengan sudut membulat (border-radius) agar terlihat lebih modern.
Input area dengan teks rata kanan, seperti kalkulator pada umumnya.
3. Struktur Kode
a) HTML (Struktur Tampilan)
Menggunakan elemen <input> untuk menampilkan angka dan hasil perhitungan.
Menggunakan elemen <button> untuk semua tombol angka dan operasi.
Seluruh tombol dikelompokkan dalam div dengan class "tombol".
b) CSS (Desain Tampilan)
Menggunakan display: flex agar tampilan berada di tengah layar.
Menggunakan grid-template-columns: repeat(4, 1fr) agar tombol tersusun rapi dalam format 4 kolom.
Setiap tombol memiliki padding, border-radius, dan ukuran font yang nyaman untuk digunakan.
c) JavaScript (Interaksi dan Logika Perhitungan)
appendNumber(number) → Menambahkan angka ke layar.
appendOperator(operator) → Menambahkan operator matematika jika input terakhir bukan operator.
deleteLastCharacter() → Menghapus karakter terakhir dalam input.
calculate() → Mengevaluasi ekspresi matematika dan menampilkan hasilnya.
Menggunakan try-catch untuk menangani error dalam perhitungan.
4. Cara Menggunakan
Masukkan angka dengan menekan tombol angka.
Pilih operator untuk melakukan operasi matematika.
Gunakan tombol "del" jika ingin menghapus angka terakhir yang diketik.
Tekan tombol "=" untuk melihat hasil perhitungan.
Jika terjadi error, layar akan menampilkan "Error", dan input akan direset.
5. Pengembangan Selanjutnya (Ide Peningkatan)
🔹 Menambahkan tombol persen (%) untuk perhitungan persentase.
🔹 Memperbaiki input agar lebih fleksibel dengan keyboard.
🔹 Menambahkan tema gelap/terang untuk variasi tampilan.
🔹 Menggunakan algoritma parsing ekspresi matematika yang lebih aman dibanding eval().

Kesimpulan
Kalkulator ini merupakan proyek sederhana namun fungsional yang dapat digunakan untuk melakukan perhitungan matematika dasar dengan tampilan yang menarik dan mudah digunakan. Dengan tambahan fitur dan peningkatan di masa depan, kalkulator ini bisa menjadi lebih canggih dan user-friendly.






