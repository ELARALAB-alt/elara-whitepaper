# 🔍 ELARA NET — Laporan Transparansi

**Tanggal:** 12 Juni 2026  
**Versi Whitepaper:** v0.2.5  
**Status:** Soft Launch — Token ELR aktif di BSC Mainnet

---

## 1. Alamat Dompet Alokasi Token ELR

Semua alamat dompet alokasi dipublikasikan sesuai Whitepaper v0.2.5. Total suplai **1.800.000.000 ELR** (tetap, tidak akan bertambah).

| Alokasi | Persentase | Jumlah (ELR) | Alamat Dompet |
| :--- | :---: | :---: | :--- |
| **Founder (H.A.S)** | 15% | 270.000.000 | [`0x63A359f4480110e6D61cE8b16152069E59A957EE`](https://bscscan.com/address/0x63A359f4480110e6D61cE8b16152069E59A957EE) |
| **Kas Pengembangan (Multi-Sig 5/7)** | 25% | 450.000.000 | [`0x3b6254165e47eb9992D275fbf66e08331AD2Ab29`](https://bscscan.com/address/0x3b6254165e47eb9992D275fbf66e08331AD2Ab29) |
| **Likuiditas Awal** | 30% | 540.000.000 | [`0x3A68f005D63DbF14e9d1C8487ecB5F88c1325E2B`](https://bscscan.com/address/0x3A68f005D63DbF14e9d1C8487ecB5F88c1325E2B) |
| **Hadiah Komunitas** | 15% | 270.000.000 | [`0x8E940708a51045Afc68DD93632B8CE75b43E59CF`](https://bscscan.com/address/0x8E940708a51045Afc68DD93632B8CE75b43E59CF) |
| **Cadangan** | 15% | 270.000.000 | [`0x0240125aEc9945a4408460795417340C576634d1`](https://bscscan.com/address/0x0240125aEc9945a4408460795417340C576634d1) |

---

## 2. Informasi Token

| Parameter | Detail |
| :--- | :--- |
| **Nama Token** | ELARA |
| **Simbol** | ELR |
| **Total Suplai** | 1.800.000.000 ELR (tetap) |
| **Blockchain** | BNB Smart Chain (BEP-20) |
| **Alamat Kontrak** | [`0xb489258429f4e1a350fc4534292f148f91902ccb`](https://bscscan.com/address/0xb489258429f4e1a350fc4534292f148f91902ccb) |
| **Status Verifikasi** | ✅ Terverifikasi (Compiler v0.8.34) |

---

## 3. Likuiditas & Penguncian LP Token

| Parameter | Detail |
| :--- | :--- |
| **Platform DEX** | PancakeSwap V2 |
| **Pasangan** | ELR/USDT |
| **Likuiditas Saat Ini** | 1.890.000 ELR + 18,90 USDT (~$37,80 total) |
| **Sumber ELR** | Dompet Likuiditas Awal (alokasi proyek 30%) |
| **Sumber USDT** | Kontribusi pribadi Founder (H.A.S) — telah menjadi aset proyek |
| **LP Token Address** | [`0xbb77819c2f56d4fc4f448a1208fd27e513f5b1d7`](https://bscscan.com/address/0xbb77819c2f56d4fc4f448a1208fd27e513f5b1d7) |
| **Platform Pengunci** | Mudra Liquidity Locker |
| **Jumlah LP Terkunci** | 3.945,089 LP Token (100% dari total LP) |
| **Masa Penguncian** | 12 bulan (hingga 13 Juni 2027) |
| **Kepemilikan LP Token** | **Aset proyek** — dikelola oleh dompet Likuiditas Awal |

### Riwayat Penambahan Likuiditas

| Tanggal | USDT Ditambah | ELR Ditambah | Total Pool | Hash Transaksi |
| :--- | :--- | :--- | :--- | :--- |
| 7 Jun 2026 | $5,00 | 500.000 | ~$10 | `0x260f...` |
| 12 Jun 2026 | $13,90 | 1.390.000 | ~$37,80 | [`0x49bbd2a...`](https://bscscan.com/tx/0x49bbd2a01f72666142bc506091f8e5b7bb9d73bf28949877033c82951464f172) |

---

## 4. Status Vesting Founder (15%)

Sesuai Whitepaper v0.2.5, alokasi Founder sebesar **270.000.000 ELR** telah dikunci di Mudra dengan rincian:

| Batch | Jumlah Dikunci | Durasi | Perkiraan Unlock | Status |
| :--- | :---: | :--- | :--- | :--- |
| 1 | 134.325.000 ELR | 12 bulan | 13 Jun 2027 | 🔒 Terkunci |
| 2 | 134.325.000 ELR | 24 bulan | 13 Jun 2028 | 🔒 Terkunci |
| **Total** | **268.650.000 ELR** | | | |

**Catatan:** Selisih 1.350.000 ELR digunakan untuk membayar fee Mudra (0,5% per batch). Tidak ada token Founder yang dapat dijual atau dipindahkan sebelum Juni 2027.

---

## 5. Kontribusi Dana Pribadi Founder & Pengembalian

### 5.1 Prinsip Utama

> **"Semua token ELR yang dikembalikan ke Founder—baik dari Cadangan, pendapatan AETHER, atau sumber lain—wajib dikunci minimal 12 bulan di Mudra. Tidak ada penguncian di bawah 12 bulan di fase awal proyek."**

### 5.2 Konversi Real-Time Saat Penambahan Likuiditas

Setiap kali Founder menyuntikkan USDT ke likuiditas, pada saat itu juga dicatat dalam jumlah ELR berdasarkan harga pasar.

### 5.3 Akumulasi & Penggantian 6 Bulanan

Setiap 6 bulan, total ELR yang dicatat dijumlahkan. **50%** dari total tersebut dikirim ke Founder sebagai penggantian.

| Porsi | Sumber | Keterangan |
| :--- | :--- | :--- |
| **50%** | Cadangan (Reserve) | ELR langsung dari dompet Cadangan, dikirim saat batch |
| **50%** | Pendapatan AETHER | ELR dari subscription pengguna — **jumlah sudah dicatat sejak konversi, tetapi pengiriman menunggu hingga pendapatan tersedia.** Setelah dikirim, langsung dikunci 12 bulan. |

### 5.4 Pelunasan Kontribusi Awal (USD $18,90)

Kontribusi awal sebelum sistem 6 bulan berlaku dilunasi dengan 2 batch tetap:

| Batch | Tanggal | Sumber | Jumlah ELR | Status |
| :--- | :--- | :--- | :---: | :--- |
| **1** | Jul 2026 | Cadangan | 472.500 | 🔒 Dikunci 12 bulan (Jul 2027) |
| **2** | Des 2026 | Cadangan | 472.500 | 🔒 Dikunci 12 bulan (Des 2027) |

### 5.5 Log Konversi Likuiditas (Real-Time)

| Tanggal | USDT | Harga ELR | ELR Dicatat |
| :--- | :---: | :---: | :---: |
| 7 Jun 2026 | $5,00 | $0,00001 | 500.000 |
| 12 Jun 2026 | $13,90 | $0,00001 | 1.390.000 |
| ... | ... | ... | ... |

### 5.6 Batch Penggantian 6 Bulanan

| Batch | Periode | Total ELR Dicatat | Dikirim (50%) | Dari Cadangan (50%) | Dari AETHER (50%, tertunda) | Kunci |
| :--- | :--- | :---: | :---: | :---: | :---: | :---: |
| 1 | Jun–Nov 2026 | [Akumulasi] | [50%] | ✅ Dikirim | ⏳ Dicatat, dikirim setelah ada pendapatan | 🔒 12 bln |
| 2 | Des–Mei 2027 | ... | ... | ✅ | ⏳ | 🔒 12 bln |

---

## 6. Status Soft Launch

| Parameter | Detail |
| :--- | :--- |
| **Fase** | 2.6 — Soft Launch |
| **Genesis Witness (GW)** | 20 dari 30 target tercapai |
| **Pengumuman Publik** | 🔒 Ditunda hingga 30 GW tercapai |
| **Airdrop ke GW** | 🔒 Ditunda hingga 30 GW terverifikasi |

---

## 7. Tim & Kontributor Awal

| Peran | Nama | Status |
| :--- | :--- | :--- |
| **Founder & Lead Developer** | H.A.S | Aktif |
| **Community Advocate — Global Outreach** | Alex | Sukarela |

---

## 8. Komitmen Selanjutnya

- [x] Deploy token ELR
- [x] Distribusi token ke alamat alokasi
- [x] Tambah likuiditas (2x)
- [x] Kunci LP Token 12 bulan
- [x] Kunci Vesting Founder 12 & 24 bulan
- [x] Publikasikan semua alamat dompet
- [x] Verifikasi kontrak & keamanan
- [ ] Audit smart contract pihak ketiga (Fase 3)
- [ ] Pengumuman resmi setelah 30 GW

---

*Ex Lapsus Resurgam. Dari kegagalan, kita bangkit kembali — dengan transparansi yang tak tergoyahkan.*

**H.A.S**  
Founder, ELARA NET
