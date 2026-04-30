# 🖼️ My Wallpaper Collection

Koleksi wallpaper pribadi yang dikurasi untuk melengkapi setup desktop Linux (GNOME, KDE, Qtile, i3, dll).

## 📂 Struktur Folder
Wallpaper di dalam repository ini dikelompokkan berdasarkan kategori atau tema (jika ada). Sebagian besar memiliki resolusi tinggi (FHD/4K) untuk memastikan tampilan yang tajam.

## 🚀 Cara Menggunakan

### Manual
Cukup klik kanan pada gambar yang Anda suka di file manager dan pilih **"Set as Wallpaper"**.

### Command Line (Sway/i3/Qtile)
Jika Anda menggunakan Window Manager, Anda bisa menggunakan `feh` untuk mengatur wallpaper:

```bash
# Mengatur wallpaper tunggal
feh --bg-fill ~/Pictures/my-wallpaper/nama-file.jpg

# Mengatur wallpaper secara acak dari folder
feh --bg-fill --randomize ~/Pictures/my-wallpaper/*
```

## 🔄 Cara Menambah Koleksi
1. Tambahkan file gambar baru ke dalam folder ini.
2. Lakukan git commit dan push:
```bash
git add .
git commit -m "Add new awesome wallpapers"
git push origin main
```

---
*Koleksi ini dikelola secara personal. Silakan gunakan untuk setup desktop Anda sendiri!* ✨