## Refleksi

Jawab pertanyaan berikut pada laporan:

1. Apa perbedaan jumlah query sebelum dan sesudah optimasi?
2. Mengapa masalah N+1 lebih berbahaya ketika data bertambah banyak?
3. Kapan relasi perlu diambil sejak awal, dan kapan tidak diperlukan?

## jawaban nya

1. di tugas pertama ada 52 sebelum di optimasi yang sudah di optimasi cuman 3 yang tugas 2 sebelum di optimasi ada 801 yang sesudah di optimasi cuman ada 5

2. akan bikin server menjadi lebih lambat kalo tidak di optimasi

3. Relasi perlu diambil sejak awal dengan eager loading jika data relasi memang akan ditampilkan atau digunakan. Jika relasi tidak digunakan, tidak perlu diambil agar query tetap efisien