# Scraper

> Koleksi script untuk scraping berbagai sumber data

<div style="text-align: center;">
  <img src="https://img.shields.io/badge/Python-3.14.6-blue?style=flat-square&logo=python" alt="Python">
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="License">
  <img src="https://img.shields.io/badge/Status-Active-success?style=flat-square" alt="Status">
</div>

---

## <i class="fas fa-list"></i> Daftar Isi

- [Requirement](#)
- [Langkah 1: Install Requirement](#)
- [Langkah 2: Download Scraper](#)
- [Langkah 3: Jalankan Script](#)
- [Kategori Scraper](#)
- [Lisensi](#)

---

## <i class="fas fa-exclamation-circle"></i> Requirement

Sebelum mulai, pastikan perangkat kamu punya hal-hal berikut:

| Requirement | Versi/Keterangan |
|-------------|-----------------|
| Python | 3.14.6 atau lebih tinggi |
| Node.js | v26.4.0 atau lebih tinggi |
| Terminal | Command Line / CMD / PowerShell / Termux |
| Internet Connection | Koneksi internet stabil |

Jangan khawatir kalau belum terinstall, ikuti langkah di bawah ini satu per satu.

---

## <i class="fas fa-download"></i> Langkah 1: Install Requirement

Pilih sistem operasi yang kamu pakai, lalu ikuti caranya.

### <i class="fab fa-windows"></i> Windows

1. Download Python di: https://www.python.org/downloads/
   - Saat instalasi, **centang kotak "Add Python to PATH"**
2. Download Node.js di: https://nodejs.org/
3. Cek apakah sudah terinstall dengan benar, buka **CMD** lalu ketik:
   ```cmd
   python --version
   node --version
   ```
   Jika muncul nomor versi, berarti berhasil.

### <i class="fab fa-linux"></i> Linux

1. Buka terminal, lalu jalankan:
   ```bash
   sudo apt update
   sudo apt install python3 -y
   ```
2. Install Node.js:
   ```bash
   curl -fsSL https://deb.nodesource.com/setup_current.x | sudo -E bash -
   sudo apt install nodejs -y
   ```
3. Cek apakah sudah terinstall:
   ```bash
   python3 --version
   node --version
   ```

### <i class="fab fa-apple"></i> macOS

1. Install [Homebrew](https://brew.sh) jika belum ada, lalu jalankan:
   ```bash
   brew install python node
   ```
2. Cek apakah sudah terinstall:
   ```bash
   python3 --version
   node --version
   ```

### <i class="fas fa-mobile-alt"></i> Termux

1. Buka aplikasi Termux, lalu jalankan:
   ```bash
   pkg update && pkg upgrade -y
   pkg install python nodejs git -y
   ```
2. Cek apakah sudah terinstall:
   ```bash
   python --version
   node --version
   ```

---

## <i class="fas fa-folder-download"></i> Langkah 2: Download Scraper

Setelah requirement siap, download repository ini.

**Semua OS (Windows/Linux/macOS/Termux)** menggunakan command yang sama:

```bash
git clone "https://github.com/kisaragikiyzen-webdevelopment-id/Scraper"
cd Scraper
```

> Jika belum punya `git`, install dulu sesuai OS kamu (Termux: `pkg install git`, Linux: `sudo apt install git`, macOS: `brew install git`, Windows: download dari [git-scm.com](https://git-scm.com)).

---

## <i class="fas fa-play-circle"></i> Langkah 3: Jalankan Script

Pastikan kamu sudah berada di dalam folder `Scraper` (dari Langkah 2). Pilih command sesuai OS kamu:

### <i class="fab fa-windows"></i> Windows (CMD)

```cmd
python <nama_script>.py
```

### <i class="fab fa-linux"></i> Linux

```bash
python3 <nama_script>.py
```

### <i class="fab fa-apple"></i> macOS

```bash
python3 <nama_script>.py
```

### <i class="fas fa-mobile-alt"></i> Termux

```bash
python <nama_script>.py
```

Ganti `<nama_script>` dengan nama script yang mau dijalankan, contoh: `python ffscrp.py`

Setelah dijalankan, ikuti instruksi yang muncul di layar terminal.

---

## <i class="fas fa-folder-open"></i> Kategori Scraper

Berikut daftar script yang tersedia, dikelompokkan berdasarkan sumbernya.

### <i class="fas fa-gamepad"></i> Game

Script untuk scraping ID pemain dari berbagai game:

| Script | Deskripsi | Command |
|--------|-----------|---------|
| `ffscrp.py` | Free Fire ID Scraper | `python ffscrp.py` |
| `mlbbscrp.py` | Mobile Legends ID Scraper | `python mlbbscrp.py` |
| `coming soon...` | Genshin Impact ID Scraper | `coming soon...` |

---

### <i class="fas fa-share-alt"></i> Sosial Media

Script untuk scraping data dari platform sosial media:

| Script | Deskripsi | Command |
|--------|-----------|---------|
| - | Coming Soon | - |

---

### <i class="fas fa-ellipsis-h"></i> Lainnya

Script untuk scraping berbagai sumber lainnya:

| Script | Deskripsi | Command |
|--------|-----------|---------|
| - | Coming Soon | - |

---

## <i class="fas fa-circle-question"></i> Bantuan

Jika mengalami error atau kesulitan:

- Pastikan Python dan Node.js sudah terinstall dengan benar (cek ulang Langkah 1)
- Pastikan posisi terminal sudah di dalam folder `Scraper` sebelum menjalankan script
- Pastikan koneksi internet aktif
- Coba jalankan ulang command dari awal

---

## <i class="fas fa-file-alt"></i> Lisensi

Project ini dilisensikan di bawah MIT License.

---

<div style="text-align: center; margin-top: 30px; color: #666;">
  <p>
    <i class="fas fa-copyright"></i> © Kyzz Code - All rights reserved.
  </p>
</div>

<!-- Font Awesome CSS -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
