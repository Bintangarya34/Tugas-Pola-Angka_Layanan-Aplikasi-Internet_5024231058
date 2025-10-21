# 🚀 Cara Mengaktifkan GitHub Pages

Panduan lengkap untuk mengaktifkan GitHub Pages agar website dapat diakses publik.

## 📋 Langkah-Langkah

### 1. Merge Pull Request (PR)
Sebelum mengaktifkan GitHub Pages, pastikan Pull Request ini sudah di-merge ke branch `main`:

1. Buka repository di GitHub
2. Klik tab **Pull requests**
3. Klik pada PR yang berjudul sesuai dengan perubahan ini
4. Klik tombol **Merge pull request**
5. Konfirmasi dengan klik **Confirm merge**

### 2. Aktifkan GitHub Pages

Setelah PR di-merge ke `main`, ikuti langkah berikut:

1. **Buka Settings (Pengaturan)**
   - Dari halaman repository, klik tab **Settings** di bagian atas
   - (Anda harus memiliki akses admin ke repository)

2. **Navigasi ke Pages**
   - Di sidebar kiri, scroll ke bawah dan klik **Pages** (di bagian "Code and automation")

3. **Konfigurasi Source**
   - Di bagian **Build and deployment**
   - Sub-bagian **Source**: Pilih **Deploy from a branch**
   - Sub-bagian **Branch**:
     - Dropdown pertama: Pilih **`main`**
     - Dropdown kedua: Pilih **`/ (root)`**
   - Klik tombol **Save**

4. **Tunggu Deployment**
   - GitHub akan mulai mem-build dan deploy website Anda
   - Proses ini biasanya memakan waktu 1-5 menit
   - Anda akan melihat notifikasi di bagian atas halaman Pages setelah deployment selesai

### 3. Akses Website

Setelah deployment selesai, website Anda akan tersedia di:

```
https://bintangarya34.github.io/Tugas-Pola-Angka_Layanan-Aplikasi-Internet_5024231058/
```

## ✅ Verifikasi

Untuk memastikan GitHub Pages sudah aktif:

1. Kembali ke halaman **Settings > Pages**
2. Anda akan melihat banner hijau dengan tulisan:
   ```
   Your site is live at https://bintangarya34.github.io/Tugas-Pola-Angka_Layanan-Aplikasi-Internet_5024231058/
   ```
3. Klik link tersebut untuk membuka website Anda

## 🔧 Troubleshooting

### Website tidak muncul atau error 404?
- Pastikan PR sudah di-merge ke branch `main`
- Pastikan file `index.html` ada di root directory
- Tunggu beberapa menit lagi, deployment mungkin masih berlangsung
- Coba refresh cache browser dengan `Ctrl+F5` (Windows) atau `Cmd+Shift+R` (Mac)

### Gambar tidak muncul?
- File `b201.png` sudah menggunakan relative path, jadi seharusnya muncul otomatis
- Periksa console browser (F12) untuk melihat error

## 📱 Berbagi dengan Orang Lain

Setelah GitHub Pages aktif, Anda bisa berbagi link website dengan siapa saja:
```
https://bintangarya34.github.io/Tugas-Pola-Angka_Layanan-Aplikasi-Internet_5024231058/
```

Website ini akan:
- ✅ Dapat diakses 24/7
- ✅ Gratis hosting dari GitHub
- ✅ Memiliki SSL certificate (HTTPS)
- ✅ Bisa dibuka dari device apa saja
- ✅ Otomatis update ketika ada perubahan di branch `main`

## 🎉 Selesai!

Sekarang tugas Anda sudah dapat dilihat oleh orang lain secara online!
