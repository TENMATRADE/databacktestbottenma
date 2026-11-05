# 📊 Laporan Backtest Historis & Performa Resmi: BOT TENMA (XAUUSD Scalper EA)

Selamat datang di repositori data verifikasi resmi **BOT TENMA** (termasuk rilis terbaru **TENMATHEGOAT BOT EA V2.0**). Repositori ini memuat catatan transaksi lengkap (*tick-level historical trade logs*) hasil pengujian performa mendalam (*backtesting*) Expert Advisor (EA) **TENMA** pada pasangan komoditas **XAUUSD (Gold)**.

Semua data dipublikasikan secara terbuka dan transparan dalam format Microsoft Excel (`.xlsx`) multi-sheet (dilengkapi sheet ramah perangkat seluler / *mobile-friendly*) sehingga calon pengguna, investor, dan mitra lisensi dapat mengaudit, meninjau, dan memvalidasi setiap metrik eksekusi secara independen.

---

## 🚀 Rilis Terbaru: Perbandingan Performa V1.0 vs V2.0

Pembaruan algoritma pada **TENMATHEGOAT BOT EA V2.0** membawa lompatan performa yang signifikan dibandingkan versi V1.0, terutama pada peningkatan laba bersih (*net profit*), win rate, serta penerapan mekanisme *adaptive lot scaling* yang lebih cerdas:

| Parameter / Metrik Kinerja | Versi 1.0 (Fixed Lot) | Versi 2.0 (TENMATHEGOAT) | Perubahan / Peningkatan |
| :--- | :---: | :---: | :---: |
| **Periode Pengujian** | 01 Sep 2026 – 02 Nov 2026 | 01 Sep 2026 – 02 Nov 2026 | Uji pasar aktif 2 bulan penuh |
| **Modal Awal (Initial Balance)** | 1.000.000 | 1.000.000 | Basis modal konsisten |
| **Saldo Akhir (Final Balance)** | 26.930.943,99 | **39.799.467,01** | **+47,78%** peningkatan saldo |
| **Total Net Profit** | +25.930.943,99 | **+38.799.467,01** | **+49,63%** pertumbuhan laba bersih |
| **Tingkat ROI** | +2.593,09% | **+3.879,95%** | **+1.286,86%** peningkatan ROI |
| **Gross Profit** | 61.591.544,51 | **126.748.012,05** | **+105,79%** kenaikan total laba |
| **Gross Loss** | -35.660.600,52 | -87.948.545,04 | Toleransi risiko terkelola |
| **Profit Factor** | 1.73 | **1.44** | Rasio profitabilitas konsisten |
| **Total Transaksi** | 2.773 Posisi | **2.772 Posisi** | Frekuensi eksekusi stabil |
| **Transaksi Menang (Profit)** | 2.416 | **2.423** | +7 transaksi win tambahan |
| **Transaksi Kalah (Loss)** | 314 | 324 | Terdistribusi terkontrol |
| **Break-Even (BEP)** | 43 | 25 | Efisiensi trailing profit optimal |
| **Win Rate Resmi** | 87,13% | **88,21%** | **+1,08%** peningkatan akurasi |
| **Rata-rata Net / Transaksi** | +9.351,22 | **+13.996,92** | **+49,68%** per transaksi |
| **Transaksi Terbaik** | +1.207.225,63 | **+1.693.740,11** | Kapitalisasi momentum lebih tinggi |
| **Transaksi Terburuk** | -579.534,87 | -2.022.745,98 | Batas risiko terukur tanpa MC |
| **Max Drawdown (Closed)** | ~23,89% | **~25,87%** | Risiko drawdown tetap terkendali aman |
| **Manajemen Ukuran Lot** | Flat / Fixed 0.01 | **Dynamic Scaling (0.01 – 0.05)** | *Compounding growth* adaptif |

---

## 🌟 Ikhtisar Eksekutif V2.0 (TENMATHEGOAT BOT EA)

Data pengujian transaksi historis pada pair **XAUUSDm** untuk versi **V2.0**:

- **Modal Awal**: 1.000.000 (Cent / Standard)
- **Saldo Akhir**: **39.799.467,01**
- **Total Net Profit**: **+38.799.467,01** (**ROI +3.879,95%**)
- **Win Rate**: **88,21%** (2.423 Menang vs 324 Kalah dari 2.747 transaksi bernilai)
- **Rata-rata Laba per Posisi**: **+13.996,92**
- **Profit Factor**: **1.44** (Gross Profit: 126.748.012,05 vs Gross Loss: -87.948.545,04)
- **Rata-rata Durasi Posisi (*Holding Time*)**: **~12,16 Menit** (Murni Scalping Cepat)
- **Keseimbangan Eksekusi**:
  - **BUY Positions**: 1.374 posisi (49,57%) — Net Gain: +10.421.971,08
  - **SELL Positions**: 1.398 posisi (50,43%) — Net Gain: +28.377.495,93

---

## 💎 Keunggulan Arsitektur & Inovasi Algoritma V2.0

Mengapa performa **BOT TENMA V2.0 (TENMATHEGOAT)** jauh lebih bertenaga dan tangguh?

### 1. 📈 Skalabilitas Lot Adaptif (*Dynamic Equity Sizing*)
Berbeda dari versi 1.0 yang menggunakan fixed lot 0.01, versi 2.0 mengadopsi mekanisme *adaptive volume scaling* terkontrol:
- Ukuran lot beroperasi dinamis antara **0.01 hingga 0.05** (rata-rata **0.024 lot**) sesuai dengan kurva ekuitas akun.
- **Bukan Martingale**: Lot tidak dilipatgandakan saat mengalami floating minus. Penyesuaian lot murni berbasis margin sehat dan kekuatan modal (*organic compounding*), sehingga tidak membahayakan akun saat menghadapi fluktuasi pasar ekstrem.

### 2. ⚡ Mesin Scalping Cepat Ultra-Presisi (*Ultra-Fast Scalp Engine*)
- 100% dari 2.772 transaksi dieksekusi dengan arsitektur mesin **SCALP**.
- Rata-rata durasi penahanan posisi (*holding time*) hanya **12,16 menit**.
- Menghindari risiko floating berhari-hari, meminimalkan paparan terhadap rilis berita fundamental liar (*high-impact economic news*), serta bebas dari beban biaya inap (*swap charges*).

### 3. 🎯 Sistem Multi-Tier Trailing Stop Cerdas
Algoritma V2.0 menyempurnakan strategi proteksi keuntungan dengan 5 mode *exit* otomatis:
- **`EA-TRAIL` (2.130 transaksi - 76,84%)**: Mode trailing bertahap yang mengunci target profit utama segera setelah order bergerak sesuai prediksi.
- **`EA-RIDER-TRAIL` (401 transaksi - 14,47%)**: Mode akselerasi profit untuk menunggangi gelombang tren panjang (*runner profits*) hingga tercapai batas momentum.
- **`EA-RIDER-SAR` (183 transaksi - 6,60%)**: Deteksi pembalikan arah menggunakan Parabolic SAR dinamis untuk segera melikuidasi posisi sebelum profit tergerus.
- **`EA` (Signal Close) (42 transaksi - 1,52%)**: Penutupan taktis berdasarkan sinyal pembatalan tren oleh logika inti bot.
- **`EA-SAR` (16 transaksi - 0,58%)**: Proteksi dini stop-and-reverse saat terjadi lonjakan arah mendadak.

### 4. ⚖️ Keseimbangan Sempurna BUY vs SELL (*Zero Directional Bias*)
Bot tidak memiliki ketergantungan sepihak pada tren bullish atau bearish:
- **BUY**: 1.374 transaksi (49,57%)
- **SELL**: 1.398 transaksi (50,43%)
Rasio mendekati 50:50 membuktikan bot bekerja dengan efektivitas tinggi baik ketika harga emas melonjak naik, anjlok tajam, maupun bergerak sideways.

---

## 📁 Berkas Data Backtest yang Tersedia

Repositori ini menyediakan data backtest resmi dalam 2 berkas Excel utama:

| Nama Berkas | Versi EA | Deskripsi |
| :--- | :---: | :--- |
| **`TENMATHEGOAT_BOT_EA_V2.0_Backtest_.xlsx`** | **V2.0 (Terbaru)** | Berkas pengujian resmi bot versi 2.0 dengan multi-sheet, fitur adaptive lot, dan peningkatan profit signifikan. |
| **`TENMA_BACKTEST_HISTORYCAL_TRANSAKSI_trades_mobile_friendly (1).xlsx`** | **V1.0 (Arsip)** | Berkas pengujian versi awal (fixed lot 0.01) sebagai pembanding performa historis. |

### Struktur Lembar Kerja (*Sheet*) di Setiap Berkas Excel:
1. **Sheet `Ringkasan`**:
   Dashboard eksekutif yang merangkum indikator statistik penting: total transaksi, win rate, total net gain, gross profit/loss, nilai transaksi terbaik/terburuk, dan periode pengujian.
2. **Sheet `Transaksi HP`**:
   Format tabel ringkas yang dirancang khusus dan dioptimalkan agar mudah dibaca di layar ponsel (*smartphone* iOS / Android) tanpa harus menggeser layar (*horizontal scroll*) terlalu jauh.
3. **Sheet `Data Lengkap`**:
   Log mentah institusional yang mencakup 20 kolom parameter data transaksi:
   - *Position ID & Deal Ticket*
   - *Open & Close Timestamps*
   - *Open & Close Execution Prices*
   - *Gross Profit, Swap, Commission, & Net Profit*
   - *Balance After (Equity Curve Tracker)*
   - *MFE (Maximum Favorable Excursion) & MAE (Maximum Adverse Excursion)*
   - *Duration in Minutes*
   - *Exit Reason & Engine ID*

---

## ⚙️ Rekomendasi Setup & Manajemen Risiko

Untuk memperoleh performa optimal yang mendekati hasil backtest saat dijalankan pada akun riil (*live account*):
- **Instrumen**: XAUUSD (Gold)
- **Tipe Akun yang Direkomendasikan**:
  - **Akun Cent**: Sangat disarankan untuk modal pemula atau tahap uji coba awal.
  - **Akun ECN / Zero Spread**: Untuk mendapatkan eksekusi spread terketat pada strategi scalping.
- **Infrastruktur Teknis**:
  - Gunakan Virtual Private Server (VPS) dengan latensi rendah (< 10–15 ms) ke server broker untuk menjamin kecepatan trailing stop.
  - Broker dengan slippage minimal dan *fast execution*.
- **Ukuran Lot**: Terapkan manajemen modal bijak sesuai kapasitas margin akun dan profil risiko pribadi.

---

## 🤝 Konsultasi & Pembelian Lisensi Resmi

Tertarik menggunakan sistem otomatisasi trading **BOT TENMA** untuk portofolio XAUUSD Anda?

Untuk informasi lisensi, uji coba, panduan aktivasi akun, dan integrasi ke MetaTrader:
- **GitHub Profile**: [@TENMATRADE](https://github.com/TENMATRADE)
- **Repository**: [databacktestbottenma](https://github.com/TENMATRADE/databacktestbottenma)

---

> **⚠️ Disclaimer & Penafian Risiko:**  
> Hasil pengujian historis (backtest) disajikan untuk tujuan transparansi, audit kinerja, dan edukasi. Perdagangan aset keuangan dengan leverage melibatkan risiko modal. Kinerja masa lalu tidak menjamin hasil di masa depan secara mutlak. Selalu gunakan dana risiko (*risk capital*) dan terapkan manajemen risiko yang disiplin.
