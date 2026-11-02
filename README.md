# Tugas Mandiri Hands-On 3: E-Commerce Transactions Analysis & ML Prep

## Ringkasan Proyek
- **Dataset:** `case3_ecommerce_transactions.csv` (10.000 transaksi)
- **Tujuan:** Audit kualitas data, data cleaning berbasis kode, analisis bisnis (Groupby, Time Series, RFM), serta persiapan data tanpa data leakage.

## 3 Temuan Utama
1. **Retur Produk:** Kategori Kecantikan (24,58%) dan Otomotif (23,76%) memiliki angka retur tertinggi.
2. **Retensi Pelanggan (RFM):** Rata-rata Recency pelanggan mencapai 293 hari, mengindikasikan perlunya program *re-engagement*.
3. **Kontribusi Pendapatan:** Fashion Pria (Rp6,93 Miliar) dan Perabot Rumah (Rp6,80 Miliar) menyumbang omset terbesar.

## Petunjuk Penggunaan
1. Install modul pendukung:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn