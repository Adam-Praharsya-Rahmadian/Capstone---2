# Optimasi Armada Bus Listrik TransJakarta

## Deskripsi Proyek
Proyek ini bertujuan untuk mengoptimalkan distribusi armada bus listrik pada tujuh rute utama TransJakarta sebagai bagian dari upaya pengurangan emisi karbon di Jakarta. Dengan latar belakang tingginya tingkat polusi udara dan perlunya transisi menuju transportasi ramah lingkungan, proyek ini menggunakan analisis data untuk mendukung pengambilan keputusan berbasis bukti.

## Latar Belakang
Jakarta menghadapi tantangan serius terkait polusi udara, dan salah satu penyumbang utama emisi karbon adalah transportasi. Dalam rangka mengatasi masalah ini, TransJakarta telah memilih tujuh rute untuk dioperasikan menggunakan bus listrik. Namun, terdapat pertanyaan terkait optimalisasi distribusi armada agar efisien dan efektif.

## Tujuan
Proyek ini bertujuan untuk:
- Mengoptimalkan distribusi armada bus listrik pada rute-rute utama.
- Mengevaluasi kinerja implementasi bus listrik berdasarkan data yang tersedia.
- Memberikan rekomendasi berbasis analisis untuk mendukung keputusan operasional TransJakarta.

## Data
Dataset yang digunakan yaitu `Transjakarta.csv` berasal dari [Kaggle](https://www.kaggle.com/dataset](https://www.kaggle.com/datasets/dikisahkan/transjakarta-transportation-transaction)) dan mencakup informasi operasional, jumlah penumpang, serta data lingkungan yang relevan.

## Deskripsi Kolom

| Nama Kolom        | Deskripsi                                                                 |
|--------------------|---------------------------------------------------------------------------|
| transID           | ID transaksi yang unik untuk setiap transaksi.                           |
| payCardID         | Identifikasi utama dari pelanggan. Kartu yang digunakan pelanggan sebagai tiket untuk masuk dan keluar. |
| payCardBank       | Nama bank penerbit kartu pembayaran milik pelanggan.                     |
| payCardName       | Nama pelanggan yang ada di kartu.                                        |
| payCardSex        | Jenis kelamin pelanggan yang ada di kartu.                               |
| payCardBirthDate  | Tahun kelahiran pelanggan.                                               |
| corridorID        | ID Koridor / ID Rute sebagai kunci untuk pengelompokan rute.             |
| corridorName      | Nama Koridor / Nama Rute berisi Mulai dan Selesai untuk setiap rute.     |
| direction         | Arah rute. 0 untuk Pergi, 1 untuk Pulang.                                |
| tapInStops        | ID halte tempat pelanggan melakukan Tap Masuk.                          |
| tapInStopsName    | Nama halte tempat pelanggan melakukan Tap Masuk.                        |
| tapInStopsLat     | Garis lintang dari halte tempat pelanggan melakukan Tap Masuk.           |
| tapInStopsLon     | Garis bujur dari halte tempat pelanggan melakukan Tap Masuk.             |
| stopStartSeq      | Posisi halte awal dalam rute perjalanan pelanggan pada saat melakukan Tap Masuk. |
| tapInTime         | Waktu pelanggan melakukan Tap Masuk yang mencakup tanggal dan jam.       |
| tapOutStops       | ID halte tempat pelanggan melakukan Tap Keluar.                         |
| tapOutStopsName   | Nama halte tempat pelanggan melakukan Tap Keluar.                       |
| tapOutStopsLat    | Garis lintang dari halte tempat pelanggan melakukan Tap Keluar.          |
| tapOutStopsLon    | Garis bujur dari halte tempat pelanggan melakukan Tap Keluar.            |
| stopEndSeq        | Posisi halte akhir dalam rute perjalanan pelanggan pada saat melakukan Tap Keluar. |
| tapOutTime        | Waktu pelanggan melakukan Tap Keluar.                                    |


[DASHBOARD](https://public.tableau.com/app/profile/adam.rahmadian/viz/Capstone-Trasnjakarta-Adam/Dashboard1?publish=yes)
