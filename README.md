# 📊 Laporan Backtest Historis & Performa Resmi: BOT TENMA (XAUUSD Scalper EA)

Selamat datang di repositori data verifikasi resmi **BOT TENMA**. Repositori ini menyediakan catatan transaksi lengkap (*tick-level historical trade logs*) hasil uji performa (backtesting) Expert Advisor (EA) **TENMA** pada instrumen **XAUUSD (Gold)**.

Data ini dipublikasikan secara transparan dalam format Microsoft Excel (`.xlsx`) multi-sheet (termasuk tampilan ramah ponsel / *mobile-friendly*) agar setiap calon pengguna, investor, dan pembeli lisensi dapat mengaudit, memverifikasi, dan meninjau setiap parameter eksekusi secara independen.

---

## 🌟 Ikhtisar Kinerja Utama (Executive Summary)

Berdasarkan data riil pengujian transaksi historis pada pair **XAUUSDm**:

| Indikator Performa | Nilai Metrik | Keterangan |
| :--- | :--- | :--- |
| **Periode Pengujian** | **01 Sep 2026 – 02 Nov 2026** | Menguji pasar aktif Gold (Trending & Ranging) |
| **Modal Awal (Initial Balance)** | **1.000.000** | Basis akun (Cent / Standard) |
| **Saldo Akhir (Final Balance)** | **26.930.943,99** | Pertumbuhan modal signifikan |
| **Total Net Profit** | **+25.930.943,99** | **ROI +2.593%** |
| **Gross Profit** | **61.591.544,51** | Total keuntungan transaksi win |
| **Gross Loss** | **-35.660.600,52** | Manajemen proteksi risiko terkontrol |
| **Profit Factor** | **1.73** | Rasio keuntungan berbanding kerugian sangat sehat |
| **Total Transaksi** | **2.773 Posisi** | Sampel data statistik valid dan teruji |
| **Transaksi Menang (Profit)** | **2.416** | Akurasi eksekusi tinggi |
| **Transaksi Kalah (Loss)** | **314** | Kerugian dibatasi secara disiplin |
| **Break-Even (BEP)** | **43** | Proteksi modal saat arah pasar berubah |
| **Win Rate** | **87,13%** | Tingkat kemenangan konsisten |
| **Rata-rata Net / Trade** | **+9.351,22** | Rata-rata laba bersih per transaksi |
| **Transaksi Terbaik** | **+1.207.225,63** | Peluang tren maksimal terkapitalisasi |
| **Transaksi Terburuk** | **-579.534,87** | Batas risiko terukur tanpa MC |
| **Max Drawdown (Closed)** | **~23,89%** | Ketahanan drawdown dalam batas wajar |

---

## 💎 Keunggulan Arsitektur BOT TENMA

Mengapa performa **BOT TENMA** dapat diandalkan oleh para trader dan investor?

### 1. 🛡️ Disiplin Tanpa Martingale Ekstrem (*Fixed Lot Discipline*)
Salah satu penyebab utama kegagalan bot trading di pasaran adalah skema martingale pelipatgandaan lot yang tidak terukur saat posisi floating minus.
- **BOT TENMA** diuji dengan **volume lot konsisten 0.01** pada seluruh 2.773 transaksi.
- Profitabilitas tidak dimanipulasi dengan melipatgandakan lot secara berisiko, melainkan murni dari **akurasi sinyal (*edge*) dan rasio *risk-to-reward***.

### 2. ⚡ Mesin Scalping Cepat (*Ultra-Fast Execution Engine*)
- Menggunakan arsitektur mesin **SCALP** dengan rata-rata durasi penahanan posisi (*holding time*) hanya **~12 menit**.
- Meminimalkan eksposur terhadap risiko berita fundamental berdampak tinggi (*news volatility*) dan membebaskan akun dari beban biaya inap semalam (*overnight swap*).

### 3. 🎯 Sistem Multi-Tier Trailing Stop Adaptif
Setiap transaksi dikawal secara cerdas dengan proteksi berbasis algoritma trailing terukur:
- **`EA-TRAIL` (2.132 transaksi - 76,88%)**: Mengunci keuntungan secara bertahap saat harga bergerak ke arah yang ditargetkan.
- **`EA-RIDER-TRAIL` (402 transaksi - 14,50%)**: Memaksimalkan perolehan poin saat terjadi pergerakan tren kuat (*runner profit*).
- **`EA-RIDER-SAR` & `EA-SAR` (198 transaksi - 7,14%)**: Deteksi pembalikan arah menggunakan Parabolic SAR adaptif untuk keluar dari pasar sebelum profit tergerus.

### 4. ⚖️ Keseimbangan Dua Arah (*Bi-directional Equilibrium*)
Bot tidak memiliki bias sepihak yang membahayakan akun:
- **BUY Trades**: 1.374 posisi (49,5%)
- **SELL Trades**: 1.399 posisi (50,5%)
Distribusi 50:50 ini membuktikan bahwa algoritma bekerja optimal dalam segala siklus pasar: saat Gold sedang naik (*bullish*), turun (*bearish*), maupun berkonsolidasi (*sideways*).

---

## 📱 Panduan Membaca File Excel Backtest

File pengujian di repositori ini dirancang khusus untuk kenyamanan evaluasi, baik di komputer maupun di layar *smartphone*:

*Nama file:* **`TENMA_BACKTEST_HISTORYCAL_TRANSAKSI_trades_mobile_friendly (1).xlsx`**

Di dalam berkas Excel terdapat 3 lembar kerja (*sheet*):
1. **Sheet `Ringkasan`**:
   Dashboard eksekutif yang memuat seluruh ringkasan metrik statistik utama, win rate, total net gain, serta instruksi ringkas penggunaan.
2. **Sheet `Transaksi HP`**:
   Format tabel ringkas 11 kolom yang dioptimalkan khusus untuk pengguna perangkat seluler (iPhone/Android). Kolom penting seperti Waktu Close, Hasil, Arah (BUY/SELL), Volume, Poin, Durasi, dan Alasan Tutup diposisikan agar mudah difilter tanpa perlu menggeser layar terlalu jauh.
3. **Sheet `Data Lengkap`**:
   Rekam jejak mentah berstandar institusional yang memuat 20 parameter lengkap per transaksi, meliputi:
   - *Position ID & Deal Ticket*
   - *Open/Close Timestamp & Prices*
   - *Gross Profit, Swap, Commission, Net Profit*
   - *Balance After (Perkembangan Ekuitas Real-Time)*
   - *MFE (Maximum Favorable Excursion)* & *MAE (Maximum Adverse Excursion)*
   - *Execution Reason & Engine ID*

---

## ⚙️ Rekomendasi Penggunaan & Manajemen Risiko

Untuk mereplikasi hasil performa maksimal pada akun trading nyata (*live account*):
- **Instrumen**: XAUUSD / Gold
- **Rekomendasi Akun**: Akun Cent (untuk modal awal ramah pemula) atau Akun ECN/Zero Spread (untuk eksekusi scalping optimal).
- **Spesifikasi Teknis**:
  - Broker dengan spread ketat dan eksekusi latensi rendah.
  - Virtual Private Server (VPS) dengan latensi < 10 ms ke server broker untuk menjamin ketepatan trailing stop.
- **Manajemen Modal**: Sesuaikan ukuran lot dengan ketahanan margin dan batas toleransi risiko masing-masing.

---

## 🤝 Konsultasi & Pembelian Lisensi Resmi

Ingin mengotomatiskan perdagangan Gold Anda dengan sistem yang teruji secara transparan?

Untuk pertanyaan seputar pembelian lisensi, aktivasi akun, instalasi ke MetaTrader, maupun konsultasi pengaturan:
- **GitHub**: [@TENMATRADE](https://github.com/TENMATRADE)
- **Repository**: [databacktestbottenma](https://github.com/TENMATRADE/databacktestbottenma)

---

> **⚠️ Disclaimer & Penafian Risiko:**  
> Kinerja masa lalu yang ditunjukkan dalam pengujian historis (backtest) tidak menjadi jaminan absolut atas hasil di masa mendatang. Perdagangan valuta asing dan komoditas dengan leverage mengandung tingkat risiko tertentu. Gunakan dana dingin (*risk capital*) dan selalu terapkan manajemen risiko yang bijak.
