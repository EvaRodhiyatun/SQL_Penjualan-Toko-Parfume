# Analisis Penjualan Toko Parfume menggunakan SQL
Menganalisis data penjualan toko parfum menggunakan SQL di Google BigQuery. Kumpulan query ini menjawab pertanyaan bisnis dasar seputar produk, brand, channel penjualan, segmen pembeli, hingga status transaksi.
# Tujuan Proyek
- Memahami performa penjualan toko parfum dari berbagai sudut pandang (produk, brand, channel, gender, konsentrasi).
- Mempraktikkan teknik SQL dasar hingga menengah untuk analisis data.
- Menyajikan insight yang dapat mendukung keputusan bisnis, seperti stok, promosi, dan strategi channel.
# Pertanyaan Bisnis
| No | Analisis | Teknik SQL |
|---|---|---|
| 1 | Daftar produk beraroma "Sauvage" beserta brand-nya | `SELECT DISTINCT`, `LIKE` |
| 2 | Jumlah transaksi untuk 3 brand sekaligus (Dior, Chanel, Lattafa) | `COUNT`, `IN` |
| 3 | Jumlah transaksi di bulan Desember 2025 | `EXTRACT`, `WHERE` |
| 4 | 10 transaksi dengan pembelian terbanyak | `ORDER BY`, `LIMIT` |
| 5 | Jumlah transaksi kelas menengah (Rp1.000.000 – Rp2.000.000) | `BETWEEN` |
| 6 | Rata-rata nilai transaksi per channel | `AVG`, `ROUND`, `GROUP BY` |
| 7 | Jenis wangi terlaris (lebih dari 500 transaksi) | `GROUP BY`, `HAVING` |
| 8 | Persentase transaksi berstatus selesai | `CASE WHEN`, `COUNT` |
| 9 | Top 5 brand terlaris untuk pembeli wanita | `GROUP BY`, `HAVING`, `SUM`, `LIMIT` |
| 10 | Konsentrasi parfum dengan rata-rata harga di atas Rp500.000 | `AVG`, `HAVING` |
