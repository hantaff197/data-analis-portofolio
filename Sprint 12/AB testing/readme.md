# Deskripsi data:

Pada proyek ini terdapat 4 dataset:
- ab_project_marketing_events_us.csv — kalender event pemasaran untuk tahun 2020
- final_ab_new_users_upd_us.csv — semua pengguna yang mendaftar di toko daring dari tanggal 7 sampai 21 Desember 2020
- final_ab_events_upd_us.csv — semua peristiwa dari pengguna baru sepanjang periode 7 Desember 2020 sampai 1 Januari 2021
- final_ab_participants_upd_us.csv — tabel yang berisi daftar peserta eksperimen

Struktur dari ab_project__marketing_events_us.csv:
- name — nama event pemasaran
- regions — kawasan tempat kampanye iklan akan berlangsung
- start_dt — tanggal awal kampanye
- finish_dt — tanggal akhir kampanye

Struktur dari final_ab_new_users_upd_us.csv:
- user_id
- first_date — tanggal pendaftaran (sign up)
- region
- device — perangkat yang digunakan untuk mendaftar

Struktur dari final_ab_events_upd_us.csv:
- user_id
- event_dt — tanggal dan waktu peristiwa
- event_name — nama jenis peristiwa
- details — data tambahan terkait peristiwa tersebut (misalnya, jumlah total pesanan dalam USD untuk peristiwa purchase)

Struktur dari final_ab_participants_upd_us.csv:
- user_id
- ab_test — nama eksperimen
- group — kelompok eksperimen pengguna berasal