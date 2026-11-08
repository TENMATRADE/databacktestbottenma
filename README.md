# 📊 Laporan Backtest Historis & Performa Resmi: BOT TENMA (XAUUSD Scalper EA)

Selamat datang di repositori data verifikasi resmi **BOT TENMA** (termasuk rilis **TENMATHEGOAT BOT EA V2.0**). Repositori ini menyediakan rekam jejak transaksi lengkap (*tick-level historical trade logs*) hasil uji performa mendalam (*backtesting*) Expert Advisor (EA) **TENMA** pada instrumen **XAUUSD (Gold)**, mulai dari uji intensif 2 bulan hingga **uji ketahanan 1 tahun penuh (13.406 transaksi)**.

Seluruh data disajikan secara terbuka dan transparan dalam format Microsoft Excel (`.xlsx`) multi-sheet (termasuk sheet khusus ramah pengguna *smartphone* / *mobile-friendly*), dilengkapi tangkapan layar verifikasi resmi dari MetaTrader Strategy Tester agar calon pengguna, investor, dan mitra lisensi dapat mengaudit setiap metrik secara independen.

> [!IMPORTANT]
> **Spesifikasi Mata Uang Akun Pengujian (USC / Exness Cent):**  
> Pengujian historis pada repositori ini menggunakan basis mata uang **USC (USD Cent)**, khususnya pada **Akun Exness Cent (USC)** di mana:  
> $$\mathbf{10.000\ \text{USC} = \$100\ \text{USD}}$$  
> Artinya, pengujian 1 tahun penuh dijalankan dengan **deposit awal riil hanya sebesar \$100 USD (10.000 USC)** dan berhasil bertumbuh menjadi **\$35.027,16 USD (3.502.716 USC)**. Hal ini membuktikan bahwa strategi **BOT TENMA** sangat ramah modal bagi trader ritel namun memiliki daya ungkit *compounding* yang luar biasa kuat dan terukur.

---

## 🏆 Rilis Unggulan: Pengujian 1 Tahun Penuh (1-Year Backtest)

Data pengujian ketahanan algoritma jangka panjang selama **10+ bulan (02 Jan 2026 – 05 Nov 2026)** pada pair **XAUUSDm** menggunakan akun **Exness Cent (USC)** melalui berkas resmi **`TENMATHEGOAT_BOT_EA_V2.0_Backtest_1tahun.xlsx`**:

<p align="center">
  <img src="WhatsApp%20Image%202026-11-07%20at%2003.46.13.jpeg" alt="Kurva Pertumbuhan Ekuitas dan Deposit Load 1 Tahun" width="100%" />
  <em>Gambar 1: Kurva pertumbuhan Balance / Equity yang konsisten menanjak dan stabil dengan Deposit Load selalu di bawah 1%.</em>
</p>

### 📈 Metrik Statistik Kunci (1-Year Performance Highlights)

| Parameter Kinerja | Nilai Statistik | Keterangan & Analisis |
| :--- | :---: | :--- |
| **Tipe Akun Pengujian** | **Exness Cent (USC)** | **10.000 USC = \$100 USD** |
| **Periode Pengujian** | **02 Jan 2026 – 05 Nov 2026** | Menguji seluruh siklus pasar Gold selama hampir 1 tahun penuh |
| **Kualitas Riwayat Data** | **99% (80.786.039 Ticks)** | Data tick riil berkualitas institusional tertinggi |
| **Modal Awal (Initial Deposit)** | **10.000 USC (\$100 USD)** | Modal awal terjangkau untuk trader ritel |
| **Saldo Akhir (Final Balance)** | **3.502.716 USC (\$35.027,16 USD)** | Pertumbuhan modal konsisten |
| **Total Net Profit** | **+3.492.716 USC (+\$34.927,16 USD)** | **ROI +34.927,16%** (~350x lipat dari deposit awal) |
| **Gross Profit / Loss** | **9.912.687 USC / -6.419.971 USC** | Manajemen risiko dan proteksi modal teruji |
| **Profit Factor** | **1.54** | Rasio keuntungan berbanding kerugian sangat sehat |
| **Sharpe Ratio** | **10.62** | Tingkat imbal hasil terhadap risiko tergolong *Exceptional* |
| **Recovery Factor** | **24.73** | Kecepatan pemulihan luar biasa setelah fase drawdown |
| **Total Transaksi** | **13.406 Posisi** | Sampel data masif dan valid secara statistik |
| **Win Rate Resmi** | **87,65%** *(excl BEP)* / **86,55%** *(all)* | 11.603 Posisi Win vs 1.635 Loss & 168 BEP |
| **Rata-rata Net / Trade** | **+260,53 USC (+\$2,61 USD)** | Nilai ekspektasi keuntungan positif konsisten |
| **Kemenangan Beruntun Maks** | **54 Transaksi Berturut-turut** | Total perolehan keuntungan beruntun mencapai +19.144 USC (+\$191,44) |
| **Kerugian Beruntun Maks** | **Hanya 5 Transaksi** | Pembatasan risiko disiplin (kerugian beruntun max -14.189 USC) |
| **Rata-rata Menang / Kalah** | **9 Win vs 1 Loss** | Rata-rata 9 kali menang setiap 1 kali kalah |
| **Distribusi Posisi** | **BUY: 49,78% \| SELL: 50,22%** | Seimbang sempurna (6.674 BUY vs 6.732 SELL) |
| **Rata-rata Waktu Tahan** | **~13,11 Menit** | Murni Scalping Cepat (bebas risiko inap / overnight swap) |
| **Ukuran Lot Adaptif** | **0.10 s/d 10.00 (Rata-rata 5.67)** | *Dynamic equity compounding scaling* pada lot cent |

<p align="center">
  <img src="WhatsApp%20Image%202026-11-07%20at%2003.50.03.jpeg" alt="Laporan Resmi MetaTrader Strategy Tester 1 Tahun" width="100%" />
  <em>Gambar 2: Rekam laporan resmi MetaTrader Strategy Tester dengan History Quality 99%, Sharpe Ratio 10.62, dan Margin Level 7800.92%.</em>
</p>

---

## 🕒 Karakteristik Eksekusi & Distribusi Transaksi

Berdasarkan data audit eksekusi sepanjang tahun 2026:

<p align="center">
  <img src="WhatsApp%20Image%202026-11-07%20at%2003.50.02.jpeg" alt="Distribusi Transaksi Berdasarkan Jam, Hari, dan Bulan" width="100%" />
  <em>Gambar 3: Distribusi frekuensi order dan profitabilitas per jam sesi trading (Asia, Eropa, USA), hari dalam seminggu, dan bulan.</em>
</p>

- **Performa Lintas Sesi**: Bot aktif menghasilkan profit di ketiga sesi perdagangan utama dunia (Asia, London/Eropa, dan New York/USA) dengan volume eksekusi puncak saat likuiditas pasar optimal.
- **Konsistensi Bulanan**: Mengalami pertumbuhan positif konsisten dari Januari hingga November tanpa satu bulan pun mengalami kerugian bersih (*zero losing months*).
- **Distribusi Hari**: Perolehan keuntungan terdistribusi merata dari Senin hingga Jumat, menunjukkan ketangguhan algoritma terhadap berbagai dinamika mingguan.

---

## 📊 Perbandingan Komprehensif Antar Versi & Periode

Tabel berikut merangkum evolusi performa dari rilis V1.0, V2.0 (Uji 2 Bulan), hingga V2.0 (Uji 1 Tahun Penuh):

| Parameter / Metrik Kinerja | V1.0 (Fixed Lot 0.01) | V2.0 (Dynamic 0.01–0.05) | V2.0 (1 Tahun Compounding) |
| :--- | :---: | :---: | :---: |
| **Tipe Akun / Satuan** | Akun Cent (USC) | Akun Cent (USC) | **Exness Cent (USC: 10k = \$100)** |
| **Periode Data** | 01 Sep 2026 – 02 Nov 2026 | 01 Sep 2026 – 02 Nov 2026 | **02 Jan 2026 – 05 Nov 2026** |
| **Durasi Pengujian** | 2 Bulan | 2 Bulan | **~10+ Bulan (1 Tahun)** |
| **Total Transaksi** | 2.773 Posisi | 2.772 Posisi | **13.406 Posisi** |
| **Modal Awal** | 1.000.000 USC (\$10.000) | 1.000.000 USC (\$10.000) | **10.000 USC (\$100 USD)** |
| **Saldo Akhir** | 26.930.943,99 USC | 39.799.467,01 USC | **3.502.716 USC (\$35.027,16)** |
| **Total Net Profit** | +25.930.943,99 USC | +38.799.467,01 USC | **+3.492.716 USC (+\$34.927,16)** |
| **ROI (Return on Investment)** | +2.593,09% | +3.879,95% | **+34.927,16%** |
| **Win Rate (Excl BEP)** | 87,13% | 88,21% | **87,65%** |
| **Win Rate (Semua Order)** | 87,13% | 87,41% | **86,55%** |
| **Profit Factor** | 1.73 | 1.44 | **1.54** |
| **Sharpe Ratio** | - | - | **10.62** |
| **Recovery Factor** | - | - | **24.73** |
| **Rata-rata Holding Time** | ~12 Menit | ~12,16 Menit | **~13,11 Menit** |
| **BUY Trades (Win Rate)** | 1.374 (49,5%) | 1.374 (49,57%) | **6.674 (49,78% - Win 87,15%)** |
| **SELL Trades (Win Rate)** | 1.399 (50,5%) | 1.398 (50,43%) | **6.732 (50,22% - Win 88,44%)** |
| **Metode Ukuran Lot** | Flat 0.01 Lot | Scaled 0.01 – 0.05 Lot | **Auto Compounding (0.10 – 10.00)** |

---

## 💎 Keunggulan Arsitektur & Logika Eksekusi BOT TENMA

Apa yang membuat **BOT TENMA V2.0 (TENMATHEGOAT)** terbukti stabil dan menguntungkan dalam jangka panjang?

### 1. 📈 Skalabilitas Lot Adaptif (*Dynamic Auto-Compounding Sizing*)
- **Bukan Martingale**: Bot tidak pernah melipatgandakan ukuran lot ketika posisi sedang mengalami floating minus.
- Ukuran lot dinaikkan secara proporsional murni berbasis pertumbuhan margin bebas (*free margin*) dan ekuitas akun yang sehat. Dengan demikian, risiko per transaksi tetap terukur dalam toleransi yang aman.

### 2. ⚡ Mesin Scalping Cepat (*Ultra-Fast Execution Engine*)
- 100% dari 13.406 transaksi dieksekusi dengan arsitektur mesin **SCALP**.
- Rata-rata durasi posisi hanya **~12 hingga 13 menit**.
- Menghilangkan risiko floating berhari-hari, meminimalkan paparan fluktuasi liar berita fundamental besar (*news spikes*), dan bebas dari beban biaya inap semalam (*overnight swap*).

### 3. 🎯 Sistem Multi-Tier Trailing Stop Teruji Konsisten
Konsistensi logika trailing stop terbukti identik baik pada pengujian 2 bulan maupun 1 tahun penuh:
- **`EA-TRAIL` (76,67% - 10.278 transaksi)**: Mode trailing bertahap untuk mengunci profit utama secara presisi.
- **`EA-RIDER-TRAIL` (14,41% - 1.932 transaksi)**: Mode akselerasi untuk memaksimalkan poin saat terjadi tren panjang (*trend runner*).
- **`EA-RIDER-SAR` (6,71% - 900 transaksi)**: Deteksi pembalikan arah menggunakan Parabolic SAR adaptif.
- **`EA` (Signal Close) (1,75% - 235 transaksi)**: Penutupan taktis berbasis pembatalan sinyal inti.
- **`EA-SAR` (0,46% - 61 transaksi)**: Proteksi dini stop-and-reverse saat momentum mendadak berbalik arah.

### 4. ⚖️ Keseimbangan Dua Arah (*Bi-Directional Zero-Bias Equilibrium*)
- **BUY Positions**: 49,78%
- **SELL Positions**: 50,22%
Rasio seimbang ini memastikan bahwa algoritma tidak terjebak dalam bias sepihak (bullish atau bearish), melainkan mampu mencetak laba konsisten pada tren naik, tren turun, maupun fase konsolidasi (*sideways*).

---

## 📁 Berkas Data Backtest yang Tersedia di Repositori

Repositori ini memuat 3 berkas Excel resmi:

| Nama Berkas | Periode Pengujian | Ukuran Sampel | Karakteristik Utama |
| :--- | :---: | :---: | :--- |
| **`TENMATHEGOAT_BOT_EA_V2.0_Backtest_1tahun.xlsx`** | **02 Jan 2026 – 05 Nov 2026** | **13.406 Posisi** | **Uji Ketahanan 1 Tahun**: Akun Exness Cent (10k USC = \$100), Sharpe Ratio 10.62, ROI +34.927%. |
| **`TENMATHEGOAT_BOT_EA_V2.0_Backtest_.xlsx`** | 01 Sep 2026 – 02 Nov 2026 | 2.772 Posisi | **Uji Intensif 2 Bulan V2.0**: Peningkatan win rate 88,21% dan adaptive lot 0.01–0.05. |
| **`TENMA_BACKTEST_HISTORYCAL_TRANSAKSI_trades_mobile_friendly (1).xlsx`** | 01 Sep 2026 – 02 Nov 2026 | 2.773 Posisi | **Arsip Uji V1.0**: Baseline performa awal dengan fixed lot 0.01. |

### Struktur Lembar Kerja (*Sheet*) di Dalam Berkas Excel:
1. **Sheet `Ringkasan`**:
   Dashboard eksekutif yang merangkum indikator statistik penting: total transaksi, win rate, total net gain, gross profit/loss, nilai transaksi terbaik/terburuk, dan periode pengujian.
2. **Sheet `Transaksi HP`**:
   Format tabel ringkas yang dirancang khusus dan dioptimalkan agar mudah dibaca di layar ponsel (*smartphone* iOS / Android) tanpa perlu menggeser layar terlalu jauh.
3. **Sheet `Data Lengkap`**:
   Rekam jejak mentah berstandar institusional yang memuat 20 parameter lengkap:
   - *Position ID & Deal Ticket*
   - *Open & Close Timestamps*
   - *Open & Close Prices*
   - *Gross Profit, Swap, Commission, & Net Profit*
   - *Balance After (Equity Curve Tracker)*
   - *MFE (Maximum Favorable Excursion) & MAE (Maximum Adverse Excursion)*
   - *Holding Duration in Minutes*
   - *Execution Reason & Engine ID*

---

## ⚙️ Rekomendasi Setup & Manajemen Risiko

Untuk memperoleh performa optimal saat bot dioperasikan pada akun riil (*live account*):
- **Instrumen**: XAUUSD (Gold)
- **Rekomendasi Akun**:
  - **Akun Exness Cent (USC)** *(Sangat Direkomendasikan)*:
    - Deposit awal cukup **\$100 USD** (akan terkonversi otomatis menjadi **10.000 USC** di terminal MT4/MT5).
    - Memungkinkan eksekusi lot mikro secara leluasa dan memberikan ketahanan margin yang sangat tinggi terhadap fluktuasi pasar emas.
  - **Akun Standard / ECN / Zero Spread**: Untuk modal yang lebih besar (\$1.000+ USD) dengan spread terketat.
- **Infrastruktur Teknis**:
  - Gunakan Virtual Private Server (VPS) dengan latensi rendah (< 10–15 ms) ke server broker untuk menjamin akurasi trailing stop.
  - Pilih broker dengan eksekusi cepat dan slippage minimal.
- **Manajemen Modal**: Sesuaikan pengaturan lot dengan modal dan toleransi risiko masing-masing.

---

## 🤝 Konsultasi & Pembelian Lisensi Resmi

Ingin mengotomatiskan perdagangan Gold Anda dengan sistem yang teruji secara transparan?

Untuk pertanyaan seputar pembelian lisensi, aktivasi akun, panduan instalasi ke MetaTrader, maupun konsultasi pengaturan:
- **GitHub**: [@TENMATRADE](https://github.com/TENMATRADE)
- **Repository**: [databacktestbottenma](https://github.com/TENMATRADE/databacktestbottenma)

---

> **⚠️ Disclaimer & Penafian Risiko:**  
> Kinerja masa lalu yang ditunjukkan dalam pengujian historis (backtest) tidak menjadi jaminan absolut atas hasil di masa mendatang. Perdagangan valuta asing dan komoditas dengan leverage mengandung tingkat risiko modal. Selalu gunakan dana dingin (*risk capital*) dan terapkan manajemen risiko yang disiplin.
