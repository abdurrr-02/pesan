# Generator Pesanan WhatsApp & Sistem Kasir Thermal (Konteks: Produk Herbal SR 12)

Aplikasi web kasir dan generator pesanan WhatsApp yang ringan, responsif, serta siap pakai. Dibuat menggunakan HTML5, CSS3, dan Vanilla JavaScript tanpa dependensi *framework* atau *backend* eksternal. Data tersimpan secara lokal di peramban pengguna menggunakan **LocalStorage**.

---

## ✨ Fitur Utama

### 📝 1. Form Pesanan WhatsApp
* **Pencarian Produk Cepat**: Fitur pencarian otomatis untuk menemukan dan menambahkan produk ke keranjang belanja.
* **Kalkulasi Otomatis**: Menghitung subtotal dan total harga secara *real-time*.
* **Catatan Pesanan**: Tambahan instruksi atau catatan khusus untuk setiap transaksi.
* **Integrasi WhatsApp**: Mengirimkan rincian pesanan yang terformat rapi langsung ke nomor WhatsApp tujuan.

### 🏧 2. Sistem Kasir & Cetak Struk
* **Skema Diskon Kategori Pembeli**:
  * Konsumen (Tanpa Diskon)
  * Reseller (Diskon 10%)
  * Sub-agen (Diskon 20%)
  * Agen (Diskon 30%)
* **Kalkulator Kembalian**: Menghitung otomatis kembalian berdasarkan jumlah uang tunai yang diterima.
* **Dukungan Printer Thermal**: Format cetak struk siap pakai untuk ukuran kertas **58mm** dan **80mm**.
* **Cetak Ulang Struk**: Fitur cetak ulang transaksi terakhir yang tersimpan di memori lokal.

### ⚙️ 3. Manajemen Produk (Admin)
* **Pengelolaan Produk**: Tambah, edit, dan hapus katalog produk dengan mudah.
* **Katalog Bawaan**: Dilengkapi data produk awal yang siap digunakan.
* **Penyimpanan Lokal**: Semua perubahan katalog tersimpan di peramban (`localStorage`).

### 📱 4. PWA (Progressive Web App) Ready
* Siap dipasang di perangkat seluler maupun komputer layaknya aplikasi native.

---

## 🛠️ Teknologi yang Digunakan

| Teknologi | Fungsi |
| :--- | :--- |
| **HTML5** | Struktur antarmuka dan elemen cetak struk |
| **CSS3** | Tata letak responsif, mode cetak, dan tampilan bergaya WhatsApp |
| **Vanilla JavaScript (ES6+)** | Logika keranjang, manipulasi DOM, perhitungan harga, dan integrasi LocalStorage |
| **Web Storage API** | Penyimpanan data produk dan riwayat struk terakhir |

---

## 🚀 Cara Penggunaan

### Tanpa Instalasi (Langsung Jalankan)
1. Unduh atau salin repositori ini:
   ```bash
   git clone [https://github.com/username/wa-order-kasir.git](https://github.com/username/wa-order-kasir.git)
