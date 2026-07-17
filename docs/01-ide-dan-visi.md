# Bank Ide - Baker's Lab

> Ini adalah tempat menampung semua ide tentang bakery.

## 🍞 Ide 1: Katalog Resep

### Koleksi Resep

**Deskripsi:** Database resep roti/kue dengan fitur:

- Upload foto
- Nama Roti/Kue
- Sumber (judul, creator, alamat url, tgl tayangan catatan)
- Komposisi bahan (bahan A, B, C, dst), takaran, proses pembuatan, suhu, dan waktu

**Status:** 🔵 Belum dimulai

### Analisis Resep

**Deskripsi:** Dari resep yang dimasukkan, aplikasi bisa:

- Nama Roti/Kue
- id-Roti/Kue
- Hitung rasio baker's percentage/BP (tepung = 100%)
- Hitung rasio total (TYP) (total = 100%)
- Tampilkan apakah resep "seimbang" (misal: hidrasi terlalu tinggi?)
- Deteksi potensi masalah (misal: gula terlalu banyak -> roti gosong)
- Tag kategori/klasifikasi (roti tawar, sourdough, kue ulang tahun, dll)

**Status:** 🔵 Belum dimulai

### Ujicoba Resep

**Deskripsi:** Eksperimen resep roti/kue dengan fitur:

- Nama Roti/Kue
- id-Roti/Kue
- Komposisi bahan (bahan A, B, C, dst), takaran, proses pembuatan, suhu, dan waktu
- Modifikasi resep existing (ubah takaran, ganti bahan)
- Catat hasil setiap percobaan (foto, tekstur, rasa)
- Upload foto hasil eksperimen
- Simpan versi percobaan (v1, v2, v3...)
- Bandingkan antar versi
- Rating pribadi (mana resep yang berhasil/mana yang gagal)

**Status:** 🔵 Belum dimulai

---

## 📊 Ide 2: Modul UMKM - Kapasitas Produksi

**Deskripsi:** Bantu UMKM roti menghitung:

- **Kapasitas terpasang:** Berapa maksimal produksi jika semua alat jalan 24 jam?
- **Kapasitas efektif:** Berapa produksi riil dengan mempertimbangkan downtime, perawatan, SDM?
- **Utilisasi:** (Efektif / Terpasang) × 100%

**Status:** 🔵 Belum dimulai

**Rumus awal (nanti akan dikembangkan):**

```
Harga Pokok Produksi (HPP) = Total Biaya / Jumlah Produk
Harga Jual = HPP / (1 - Margin%)
```

---

## 📝 Catatan Kecil

- Semua ide ini terlalu besar untuk dibangun sekaligus. Saya harus mulai dari yang PALING SIMPEL.
- Mana yang paling saya butuhkan sekarang? Mungkin **resep katalog** dulu, karena itu fondasi untuk fitur lain.
- Fitur UMKM (kapasitas + harga) bisa jadi "modul terpisah" yang ditambahkan belakangan.

---

_Dibuat: 17 Juli 2026_
_Terakhir diupdate: -_
