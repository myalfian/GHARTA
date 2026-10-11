# PORTAL RESMI BUMDES GRAHARTA KANUGRAHAN
*Website Profil, Layanan Publik & Cek Tagihan Air Desa Terinspirasi Arsitektur PAM JAYA (pamjaya.co.id)*

---

## 📌 Ringkasan Proyek
Portal resmi **BUMDes Graharta Kanugrahan** (Desa Kanugrahan, Kec. Maduran, Kab. Lamongan, Jawa Timur) dirancang sebagai sistem utilitas publik dan transparansi badan usaha milik desa dengan standar korporat modern.

Website ini berfokus pada:
1. **Kemudahan Layanan Warga (Smartphone Friendly)**: Warga dapat mengecek tagihan air HIPPAM mandiri, mendaftar sambungan pipa baru, dan memesan kebutuhan tani via smartphone bahkan pada jaringan 3G/4G desa.
2. **Respon Cepat Aduan via WhatsApp**: Format aduan otomatis berpenomoran tiket (`#ADU-KNG-...`) yang langsung terhubung ke WhatsApp Customer Service BUMDes.
3. **Transparansi Dana & PADes**: Infografis pembagian laba bersih BUMDes untuk pembangunan desa, beasiswa anak yatim/dhuafa, dan peremajaan aset air bersih.

---

## 🎨 Spesifikasi Desain & Palet Warna
- **Primary (Deep Navy)**: `#0B3B60` & `#07243B` — Menggambarkan tata kelola korporat terpercaya, stabilitas institusi, dan elemen air.
- **Accent (Fresh Emerald Teal)**: `#0284C7` & `#059669` — Cerminan kesuburan desa agraris, kelestarian lingkungan, dan kesegaran air bersih.
- **Background (Slate White)**: `#F8FAFC` — Bersih, kontras tinggi, dan nyaman dibaca di bawah sinar matahari.
- **Mobile Usability**: Minimum touch target 48x48px, navigasi hamburger halus, dan floating WhatsApp pill.

---

## 🚀 Fitur Unggulan

### 1. PAM JAYA Inspired Quick Access Widget (4 Tab Interaktif)
- **Tab 1: Cek Tagihan Air & Iuran Warga**
  - Input ID Pelanggan / No. Sambungan (misal: `KNG-2024-001`, `KNG-2024-042`, `KNG-2024-108`).
  - Menampilkan rincian stand meter lalu & kini, total pemakaian m³, biaya abonemen, iuran sampah, dan status lunas / belum lunas.
  - Tombol **Rincian Struk** (Invoice modal interaktif siap cetak) dan tombol **Bayar Online via QRIS Desa / Bank Jatim**.
- **Tab 2: Pasang Sambungan Baru**
  - Formulir pengajuan pemasangan pipa air baru dengan estimasi biaya transparan dan opsi subsidi bagi sarana ibadah / masjid.
- **Tab 3: Lapor Gangguan Cepat (Auto WhatsApp Generator)**
  - Mengirim tiket keluhan pipa bocor, air keruh, atau keterlambatan sampah langsung ke WhatsApp tim teknis BUMDes.
- **Tab 4: Kanugrahan Mart**
  - Katalog sembako, beras pulen desa, pupuk organik BUMDes, dan elpiji 3kg pangkalan resmi.

### 2. Live Monitoring & Metrik Kinerja Desa
- Status real-time debit pompa (14.8 L/detik), tekanan pipa (2.8 - 3.2 Bar), dan tingkat kejernihan (0.4 NTU).
- Counter capaian: **1.450+ KK terlayani**, **99.4% efisiensi distribusi**, **4 unit usaha aktif**, serta **Rp 285.500.000 PADes/tahun**.

### 3. Profil Direktur & Tata Kelola Berintegritas
- Sambutan Direktur BUMDes dan Kepala Desa dengan 4 pilar nilai pelayanan: *Amanah, Responsif, Transparan, Berkelanjutan*.
- Tanda legalitas resmi berbadan hukum SK Kemenkumham RI & Perdes Kanugrahan.

### 4. Transparansi PADes & Arsip Dokumen
- Progress alokasi laba bersih: 50% PADes, 25% modal/pipa, 15% beasiswa & dhuafa, 10% insentif teknisi.
- Arsip unduh Laporan Keuangan Kuartalan dan Hasil Musdes.

### 5. FAQ & Pusat Aduan
- Accordion interaktif untuk prosedur pembayaran, jadwal baca meteran, dan tarif perdes.

---

## 📂 Struktur File
```
GRAHARTA/
├── SITEMAP_AND_WIREFRAME.md   # Dokumen arsitektur informasi & wireframe PAM JAYA
├── index.html                 # Kode website utama production-ready (Tailwind + Vanilla JS)
└── README.md                  # Dokumentasi teknis & panduan instalasi
```

---

## 💻 Cara Menjalankan Secara Lokal
Cukup buka file `index.html` langsung di browser, atau jalankan server lokal:

```bash
# Menggunakan Python
python -m http.server 8085

# Atau menggunakan Node.js (npx serve)
npx serve .
```

Akses website di browser: `http://localhost:8085`
