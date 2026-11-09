# SIMPASI (Sistem Perencanaan dan Analisis Simpang APILL)
### Berbasis Pedoman Kapasitas Jalan Indonesia (PKJI 2023) • Universitas Tidar (UNTIDAR)

Aplikasi web interaktif (*Single Page Application*) untuk perencanaan geometrik, analisis kapasitas, alokasi waktu sinyal Webster, dan evaluasi kinerja simpang bersinyal APILL sesuai standar teknis **PKJI 2023** (Kementerian PUPR Ditjen Bina Marga).

---

## 🚀 Fitur Unggulan

1. **Formulir SA Series Identik PKJI 2023**:
   - **Formulir SA-I**: Data Geometri, Lingkungan, dan Pengaturan Sinyal APILL.
   - **Formulir SA-II**: Arus Lalu Lintas (Kendaraan/jam), Angka Ekivalen Mobil Penumpang (EMP), dan Arus Total ($Q$ smp/jam).
   - **Formulir SA-III**: Penentuan Waktu Antarfase, Waktu Hilang Total ($L$), Rasio Arus Kritis ($\Sigma Y_{crit}$), dan Penetapan Waktu Siklus Webster ($c$).
   - **Formulir SA-IV**: Kapasitas Pendekat ($C$), Arus Jenuh Dasar ($S_0$), dan Faktor-Faktor Koreksi ($F_{cs}, F_{sf}, F_G, F_p, F_{RT}, F_{LT}$).
   - **Formulir SA-V**: Evaluasi Kinerja (Derajat Kejenuhan $DJ$, Tundaan Lalu Lintas & Geometrik $DT, DG, T$, Panjang Antrean Fisik/PKJI, serta Tingkat Pelayanan / *Level of Service* LOS).

2. **Fleksibilitas Tipe Simpang**:
   - Mendukung **Simpang 4 Lengan (Crossroad)** dan **Simpang 3 Lengan (T-Junction)** dengan opsi penonaktifan lengan buntu (Barat, Timur, Utara, atau Selatan).
   - Pilihan pengaturan sinyal 2 fase, 3 fase, atau 4 fase dengan panduan rekomendasi *Pros & Cons*.

3. **Simulasi Visual 2D Top-Down Real-Time**:
   - Kanvas animasi persimpangan dengan proporsi geometrik jalan sesuai data input.
   - Pergerakan kendaraan (*Sepeda Motor, Mobil Pribadi, Bus/Truk*) dengan dinamika antrean fisik, lampu rem menyala saat merah, dan pelepasan gelombang kejut hijau (*shockwave accordion*).
   - Lampu APILL sinkron secara real-time dengan waktu siklus Webster formulir SA-III.

4. **Transparansi Rumus (*Explainable Engine*)**:
   - Dilengkapi penjabaran rumus matematika dan rujukan pasal PKJI 2023 pada setiap formulir SA-I s.d. SA-V.

5. **Utilitas Ekspor & Presets**:
   - Ekspor seluruh formulir SA-I s.d. SA-V ke format spreadsheet Excel (.xlsx) rapi siap cetak.
   - Simpan dan muat file konfigurasi proyek (.json).
   - Pilihan preset skenario instan (Simpang 4 Magelang, Simpang 3 Kebonpolo, dll).

---

## 💻 Cara Menjalankan Secara Lokal

Cukup buka file `index.html` menggunakan browser modern apa saja (Google Chrome, Microsoft Edge, Mozilla Firefox, Safari). Tidak memerlukan instalasi server atau dependensi tambahan.

---

## 🏛️ Pengembang & Hak Cipta
- **Institusi**: Program Studi Teknik Sipil, Fakultas Teknik, Universitas Tidar (UNTIDAR) Magelang.
- **Rujukan**: *Pedoman Kapasitas Jalan Indonesia (PKJI 2023)* — Direktorat Jenderal Bina Marga, Kementerian Pekerjaan Umum dan Perumahan Rakyat.
