# BackwardChaining
Ini digunakan dalam pembuktian teorema otomatis, mesin inferensi, asisten pembuktian, dan aplikasi kecerdasan buatan lainnya.
 
#Bagaiamana Cara kerja nya?
Mesin inferensi yang menggunakan Backward chaining akan mencari aturan inferensi sampai menemukan aturan dengan konsekuensi yang sesuai dengan tujuan yang diinginkan.
FOL-BC-Ask adalah algoritma Backward chaining yang diberikan di bawah ini. lalu dipanggil dengan daftar tujuan yang berisi elemen, kueri asli, dan mengembalikan himpunan semua substitusi yang memenuhi kueri

#Algoritma
Fungsi FOL-BC-Ask (KB, goal, @) mengembalikan sekumpulan substitusi
Inputan: KB, basis pengetahuan tujuan, daftar konjungsi membentuk kueri (@ sudah diterapkan)
@, substitusi saat ini, awalnya subs kosong. {}
variabel lokal: jawaban, satu set substitusi, awalnya kosong {}
