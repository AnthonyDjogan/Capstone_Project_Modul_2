# Capstone_Project_Modul_2
Melakukan Data Analysis dengan data-set bertema Netflix Originals Content

Pada project ini kita akan menganalisa dataset yang berisi informasi mengenai konten original netflix. Dataset memiliki 6 kolom , yaitu :
- Title = Judul konten
- Genre = Genre dari konten
- Premiere = Waktu premiere konten
- Runtime = Durasi konten dalam satuan menit
- IMDB Score = IMDB score konten per tanggal 06-01-2021
- Language = Bahasa yang tersedia per tanggal 06-01-2021

Output dari project ini adalah suatu rekomendasi mengenai jenis konten potensial berdasarkan analisi data yang ada di dataset. Untuk bisa membuat rekomendasi kita harus merumuskan masalah dan menyusun tahap analisa yang akan kita lakukan.

Rumusan masalah:
- Konten seperti apa yang sedang diminati konsumen?
- Kapan waktu yang tepat untuk merilis konten tersebut?

Tahap analisa:
- Mencari main-genre populer
  Informasi genre pada dataset tidak konsisten, dimana informasi di kolom ini ada yang berupa main-genre dan sub-genre. Kita akan membuat kolom baru untuk mempermudah analisa,      dimana kolom ini akan berisi main-genre dari konten tersebut. Jika terdapat banyak genre pada konten, kita akan mengasumsikan genre yang disebut paling pertama sebagai main-      genre dari konten tersebut. 
- Melihat performa genre berdasarkan median IMDB Score
- Mencari kombinasi genre berdasarkan main-genre populer
- Melihat bahasa apa saja yang sering digunakan
- Mencari kapan waktu yang tepat untuk merilis konten
