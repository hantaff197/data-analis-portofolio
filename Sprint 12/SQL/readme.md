# Deskripsi data:

books:
Berisi data tentang buku:
- book_id — ID buku
- author_id — ID penulis
- title — judul buku
- num_pages — jumlah halaman
- publication_date — tanggal penerbitan
- publisher_id — ID penerbit

authors:
Berisi data tentang penulis:
- author_id — ID penulis
- author — nama penulis

publishers:
Berisi data tentang penerbit:
- publisher_id — ID penerbit
- publisher — nama penerbit

ratings:
Berisi data tentang ulasan pengguna:
- rating_id — ID rating
- book_id — ID buku
- username — nama pengguna yang memberi rating buku
- rating

reviews:
Berisi data tentang ulasan pelanggan:
- review_id — ID ulasan
- book_id — ID buku
- username — nama pengguna yang mengulas buku
- text — teks ulasan
