<p align="center">
  <img src="logo.png" width="96" alt="Rythim Music">
</p>

<h1 align="center">Rythim Music untuk Windows</h1>

<p align="center">
  Pemutar musik bergaya liquid glass, ringan, dengan libVLC bawaan.<br>
  Halaman ini berisi installer dan rilis resmi.
</p>

---

## Unduh

1. Buka tab **[Releases](../../releases/latest)**.
2. Unduh **`RythimMusic-Setup.exe`** (ukurannya kecil, puluhan KB).
3. Jalankan. Installer mengunduh paket aplikasi terbaru sendiri, lalu memasangnya.

Tidak perlu akun dan tidak perlu izin administrator. Aplikasi dipasang ke `%LOCALAPPDATA%\Programs\RythimMusic`, lengkap dengan pintasan Start Menu dan (opsional) Desktop.

## Persyaratan

- Windows 10 atau 11 (64-bit)
- Koneksi internet saat memasang dan memutar musik

## Update

- **Dari dalam aplikasi:** Pengaturan, Pembaruan, **Cek pembaruan**. Kalau ada versi baru, aplikasi mengunduh installer dan memperbarui dirinya sendiri.
- **Manual:** jalankan `RythimMusic-Setup.exe` dari rilis terbaru.

Data kamu (playlist, riwayat, pengaturan) tersimpan di `%APPDATA%\RythimMusic` dan tidak terhapus saat update.

## Hapus aplikasi

Windows Settings, Aplikasi, **Rythim Music**, Uninstall. Data di `%APPDATA%\RythimMusic` tetap ada; hapus manual kalau tidak diperlukan.

## Isi rilis

| Berkas | Fungsi |
| --- | --- |
| `RythimMusic-Setup.exe` | Installer kecil, ini yang kamu unduh |
| `RythimMusic-win-x64.zip` | Paket aplikasi (diunduh otomatis oleh installer) |

Versi memakai format `1.0.<nomor build>` dan setiap build dirilis otomatis lewat GitHub Actions.

## Masalah umum

**Windows SmartScreen memperingatkan "aplikasi tidak dikenal".**
Installer belum ditandatangani sertifikat code signing. Klik **Informasi lebih lanjut**, lalu **Tetap jalankan**.

**Pemasangan gagal saat mengunduh.**
Periksa koneksi internet atau antivirus yang memblokir unduhan, lalu klik **Coba lagi**.

**Lagu tidak muncul di overlay media Windows atau widget Dynamic Island.**
Rythim Music mendaftar ke kontrol media Windows lewat PowerShell. Pastikan PowerShell tidak diblokir kebijakan keamanan perangkat.

## Lisensi

Rythim Music dirilis di bawah **GPL-3.0**.
