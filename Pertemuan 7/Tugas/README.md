# Form Registrasi Event - Resto Nusantara

Proyek ini adalah tugas praktikum pengembangan web untuk membuat halaman pendaftaran (*event registration form*) yang dilengkapi dengan elemen input HTML lengkap, validasi sisi klien menggunakan JavaScript, serta desain antarmuka (*UI*) yang bersih dan responsif dengan CSS eksternal.

## 🛠️ Fitur Utama
1. **Navigasi Responsif (Navbar)**: Header dengan logo merek "Resto Nusantara" dan menu navigasi.
2. **Kontrol Form Lengkap**:
   - Teks input (`<input type="text">` untuk Nama Lengkap)
   - Pilihan kategori (`<select>` untuk Mahasiswa, Umum, Pelajar)
   - Tombol pilihan (`<input type="radio">` untuk jenis kehadiran Offline/Online)
   - Area teks (`<textarea>` untuk alasan mengikuti event)
   - Unggah berkas (`<input type="file">` untuk KTP/Identitas)
   - Kotak centang (`<input type="checkbox">` untuk persetujuan syarat & ketentuan)
3. **Validasi Formulir (JavaScript)**:
   - Validasi panjang minimal karakter nama.
   - Pengecekan pilihan kategori dan jenis kehadiran.
   - Validasi format berkas (PDF, JPG, PNG) serta pembatasan ukuran maksimal file (2MB).
   - Validasi kotak persetujuan (*checkbox*).

---

## 📁 Struktur Berkas Proyek
Pastikan semua file berikut berada di dalam satu folder yang sama:
```text
📂 nama-folder-proyek/
│
├── index.html            # File struktur utama HTML dan skrip validasi JS
├── style.css             # Berkas desain tampilan (CSS Eksternal)
└── logorestonusantara.jpg  # Aset gambar logo brand