# 🌸 WaifuCode Text Editor

**WaifuCode Text Editor** adalah aplikasi editor berbasis web untuk menyimpan teks dalam format **WaifuCode (.wfc)** — sistem encoding unik yang menghasilkan file berbentuk non-printable dan hanya dapat dibuka menggunakan editor ini.

---

## ✨ Fitur Utama

- ✅ **WaifuCode Encoding (WFC1)**: Teks dikodekan ke dalam format khusus dengan setiap karakter disimpan dalam 4-byte non-printable (XOR 0xA5 + UTF-32).
- ✅ **Real-time WaifuCode Preview**: Tampilkan hasil encoding secara langsung saat mengetik.
- ✅ **Auto-check File Integrity**: File `.wfc` dilengkapi header dan checksum CRC32 untuk verifikasi integritas saat dibuka.
- ✅ **Keyboard Shortcut:**
  - `Ctrl + S` → Simpan file
  - `Ctrl + N` → File baru
  - `Ctrl + O` → Buka file
  - `Escape` → Tutup modal bantuan
- ✅ **Export TXT**: Ekspor teks biasa untuk kompatibilitas dengan editor lain.
- ✅ **Responsive Design**: Tampilan cantik untuk desktop & mobile.
- ✅ **Info Modal + Bantuan**: Tersedia petunjuk penggunaan lengkap.

---

## 🚀 Cara Penggunaan

1️⃣ **Tulis teks** di panel editor.  
2️⃣ Klik **Simpan WFC** (💾) untuk mengunduh file `.wfc`.  
3️⃣ Klik **Buka File** (📁) untuk memuat file `.wfc` yang pernah disimpan.  
4️⃣ Gunakan **Export TXT** (📤) untuk mengunduh sebagai file teks biasa.  
5️⃣ Klik **Lihat Code** (👀) untuk melihat WaifuCode dalam jendela terpisah.

---

## 🛡 Keamanan

- File `.wfc` hanya dapat dibuka dengan WaifuCode Editor karena menggunakan format non-printable dan validasi CRC32.
- Konten file tidak dapat dibaca di editor biasa.

---

## 💻 Teknologi

- **HTML + CSS + JavaScript murni**
- Tidak menggunakan library eksternal
- Semua operasi berjalan offline di browser (no server)
