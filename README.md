# TUGAS 7 #

PERTANYAAN
1. Apa perbedaan utama antara stateless dan stateful widget dalam konteks pengembangan aplikasi Flutter?
2. Sebutkan seluruh widget yang kamu gunakan untuk menyelesaikan tugas ini dan jelaskan fungsinya masing-masing.
3. Jelaskan bagaimana cara kamu mengimplementasikan checklist di atas secara step-by-step (bukan hanya sekadar mengikuti tutorial)

JAWABAN
1. Perbedaan yang paling utama antara stateless dan stateful widget terdapat pada adaptibilitas dan responsivitas terhadap kegiatan yang dilakukan oleh seorang 
   user di dalam sebuah aplikasi. Stateful widget dapat merubah bentuk widgetnya sesuai kondisi yang di tentukan sedangkan stateless widget bentuknya atau 
   tampilannya tidak akan berubah.

2. a) Padding --> untuk mengatur jarak border dan konten yang ingin di atur paddingnya
   b) Text --> untuk menampilkan sebuah text yang bisa di atur font, warna, dan lainnya dengan TextStyle
   c) AppBar --> untuk menampilkan sebuah bar di bagian atas aplikasi yang dapat diisi dengan text, icon, dan semacanya
   d) Icon --> untuk bisa mengakses icon-icon yang disediakan flutter dan bisa digunakan
   e) Container --> berfungsi sebagai tempat dimana konten-konten yang kita inginkan bisa ditaruh
   f) GridView --> jika ada sebuah konten repetitif atau yang sama dan ingin ditampilkan secara vertikal atau horizontal bisa memakai gridview ini
   g) SingleChildScrollView --> buat memastikan kalau ada sebuah konten tetap bisa terlihat sepenuhnya jika di scroll saat containernya terlalu kecil
   h) Column --> untuk menampilkan widget secara vertikal

3. 