# AI Screen Assistant — prototipe awal

Starter project Android (Kotlin) berisi halaman awal dan tombol overlay. Ini **belum merupakan bot AI lengkap**: pemanggilan API AI dan pembacaan layar/MediaProjection belum diimplementasikan. Tombol melayang hanya membuka aplikasi saat diketuk.

## Build APK
Project ini ditujukan untuk dibuka di Android Studio/lingkungan build Android dengan internet. Workflow GitHub Actions tersedia di `.github/workflows/build.yml`; setelah project diunggah ke repository GitHub dan workflow dijalankan, APK debug akan tersedia sebagai artifact.

## Sebelum dipakai
- Tambahkan backend HTTPS untuk panggilan AI; jangan menanam API key rahasia di APK.
- Implementasikan MediaProjection dengan persetujuan sistem setiap sesi untuk mengambil layar.
- Jelaskan data yang dikirim ke penyedia AI dan jangan mengirim layar tanpa persetujuan.
- APK debug bukan aplikasi siap produksi.
