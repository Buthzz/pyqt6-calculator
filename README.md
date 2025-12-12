# Aplikasi Kalkulator PyQt6

Proyek UTS Semester 3 - Pemrograman Desktop

## 📋 Deskripsi Proyek

Aplikasi kalkulator desktop yang dibangun menggunakan PyQt6 dengan implementasi berbagai layout untuk mendemonstrasikan kemampuan GUI programming. Aplikasi ini menampilkan dua tab berbeda yang masing-masing menggunakan pendekatan layout yang berbeda.

## 👥 Anggota Kelompok

| No | Nama | NIM | Peran |
|----|------|-----|-------|
| 1 | Yohanes Oktanio | 240411100095 | Ketua Kelompok |
| 2 | Muhammad Fajar Nugroho | 240411100103 | Anggota |
| 3 | Muhammad Rafi Lazuardi | 230411100060 | Anggota |
| 4 | Ahmad Ubaydir Rohman | 230411100116 | Anggota |

## ✨ Fitur

- **Grid Layout**: Tampilan kalkulator dengan susunan grid layout
- **Kombinasi Layout**: Tampilan kalkulator dengan kombinasi horizontal dan vertical layout
- **Tab Navigation**: Navigasi antar layout menggunakan tab yang dapat dipindahkan
- **Menu Bar**: Menu bar untuk operasi matematika tambahan
- **Operasi Matematika**: Mendukung operasi dasar (tambah, kurang, kali, bagi)

## 🛠️ Teknologi yang Digunakan

- **Python 3.x**
- **PyQt6** - Framework GUI untuk aplikasi desktop
- **PyQt6.QtWidgets** - Widget components untuk antarmuka pengguna

## 📁 Struktur Proyek

```
pyqt6-calculator/
├── main.py                      # File utama aplikasi
├── layouts/                     # Folder berisi berbagai layout
│   ├── grid_layout.py          # Layout kalkulator bentuk grid
│   ├── kombinasi_layout.py     # Layout kombinasi (QH & QV)
│   └── menu.py                 # Menu bar aplikasi
├── utils/                       # Folder utility
│   └── function_button.py      # Logic operasi matematika
└── README.md                    # Dokumentasi proyek
```

## 🚀 Cara Menjalankan

1. **Install Python** (versi 3.8 atau lebih baru)

2. **Install PyQt6**:
   ```bash
   pip install PyQt6
   ```

3. **Jalankan Aplikasi**:
   ```bash
   python main.py
   ```

## 📖 Penggunaan

1. Buka aplikasi dengan menjalankan `main.py`
2. Pilih tab layout yang diinginkan (Grid Layout atau Kombinasi Layout)
3. Gunakan tombol-tombol untuk melakukan operasi matematika
4. Hasil kalkulasi akan ditampilkan pada layar kalkulator

## 📝 Catatan Pengembangan

- Proyek ini dibuat sebagai tugas UTS mata kuliah Pemrograman Desktop semester 3
- Mendemonstrasikan pemahaman tentang:
  - Layout Management di PyQt6
  - Event Handling
  - Widget Organization
  - MVC Pattern (separation of logic dan UI)

## 📄 Lisensi

Proyek ini dibuat untuk keperluan pembelajaran di Universitas Trunojoyo Madura.

---

**Pemrograman Desktop - Semester 3**  
*Universitas Trunojoyo Madura*
