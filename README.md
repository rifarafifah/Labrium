# Laborium v9 Publik — Replit

Versi demo publik tanpa login, menyimpan data **hanya di localStorage browser pengunjung**. Tidak memakai server/database bersama.

## Publish di Replit
1. Impor ZIP sebagai proyek baru (HTML/CSS/JS).
2. Jalankan Preview dan uji tambah data, refresh, lalu unduh DOCX/PDF.
3. Klik Publish, pilih deployment **Static** jika tersedia, dengan direktori publik `.` dan file `index.html`.
4. Bagikan URL publik hasil deployment.

Jangan gunakan konfigurasi server.py lama untuk versi publik ini. Jika Replit meminta build command, tidak diperlukan: aplikasi ini HTML statis.

## Penyimpanan
- Data tersimpan per browser + origin situs, bukan per akun.
- Data tidak tersinkron antarperangkat/browser dan dapat hilang jika storage dibersihkan.
- Gunakan Cadangkan JSON untuk memindahkan/menjaga data.
- Jika sebelumnya memakai v9 dengan server bersama, cadangkan dan impor JSON di versi publik bila ingin memindahkan data.
- Jangan mengisi data pribadi/sensitif dalam demo publik.
