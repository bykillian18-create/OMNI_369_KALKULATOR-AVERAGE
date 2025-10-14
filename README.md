# [IDN] OMNI 369 KALKULATOR-AVERAGE

Ini adalah project **OMNI 369 - Kalkulator Average Saham (Indonesia)**  
Fitur utama:
- Multi-emiten (multiple stocks)
- Auto-save ke `localStorage`
- Simulasi average & simulasi average-reverse
- Simulasi jual (memperhitungkan fee beli 0.15%, fee jual 0.25%, PPh final 0.1%, bea materai Rp10.000)
- Auto-update harga pasar via **Yahoo Finance (.JK)** dengan **auto-proxy fallback** (ThingProxy → AllOrigins → CORS Anywhere)
- Indikator proxy aktif & status online/offline
- Dark mode toggle (disimpan di localStorage)
- Toast notifications untuk update / error
- Update interval default: **30 detik**

## Cara pakai (GitHub Pages)

1. Buat repository baru di GitHub (public).
2. Upload file `index.html` dan `README.md` ke repo.
3. Aktifkan GitHub Pages (Settings → Pages → deploy from branch `main`, folder `/`).
4. Buka URL: `https://<username>.github.io/<repo-name>/`

> Jika Anda membuka file secara langsung di HP (`file://`), kalkulator dapat bekerja, tapi beberapa browser mungkin menolak request cross-origin. Jika mengalami masalah, jalankan lewat GitHub Pages atau server lokal.

## Lisensi
Proyek ini disediakan "as-is" untuk penggunaan pribadi. Anda bebas memodifikasi.

