# 🛵 MRD Rental Motor - Inventory & Booking System

[![GitHub Pages](https://img.shields.io/badge/Deployment-GitHub_Pages-blue?style=for-the-badge&logo=github)](https://mrdokey.github.io/mrdrent/)
[![Powered By](https://img.shields.io/badge/Powered_By-Google_Apps_Script-green?style=for-the-badge&logo=google-apps-script)](https://www.google.com/script/start/)

**MRD Rental** adalah ekosistem penyewaan sepeda motor modern yang mengintegrasikan kemudahan manajemen data **AppSheet** dengan fleksibilitas katalog web statis melalui **GitHub Pages**. Sistem ini dirancang untuk memberikan transparansi unit kepada pelanggan secara *real-time*.

---

## 🌟 Fitur Utama

* **Live Catalog**: Menampilkan daftar unit motor secara dinamis langsung dari database Google Sheets.
* **Real-time Availability**: Fitur cek ketersediaan unit berdasarkan tanggal sewa untuk menghindari *double booking*.
* **Automated Switch**: Integrasi skrip saklar otomatis untuk pengiriman notifikasi WhatsApp.
* **WhatsApp Integration**: Reservasi langsung terhubung ke nomor admin dengan format pesan otomatis yang rapi.
* **SEO Optimized**: Landing page yang ringan dan ramah mesin pencari (Google Search).

---

## 🛠️ Arsitektur Teknologi

Sistem ini dibangun dengan pendekatan *serverless* untuk efisiensi biaya dan performa:

1.  **Frontend**: HTML5, CSS3 (Bootstrap 5), dan Vanilla JavaScript.
2.  **Hosting**: GitHub Pages.
3.  **Backend/API**: Google Apps Script (GAS) sebagai jembatan data.
4.  **Database**: Google Sheets (Sinkron dengan AppSheet).
5.  **Management**: AppSheet (Untuk operasional admin & input data).

---

## 📁 Struktur File

* `index.html`: Katalog utama unit motor (Landing Page).
* `cariunit.html`: Fitur pencarian dan filter ketersediaan unit berdasarkan jadwal.
* `README.md`: Dokumentasi proyek.

---

## 🚀 Cara Instalasi (Untuk Developer)

Jika Anda ingin melakukan *cloning* atau pengembangan mandiri:

1.  **Clone Repositori**:
    ```bash
    git clone [https://github.com/mrdokey/mrdrent.git](https://github.com/mrdokey/mrdrent.git)
    ```
2.  **Konfigurasi API**:
    Buka `index.html` dan `cariunit.html`, lalu ganti `API_URL` dengan URL *web app* dari Google Apps Script Anda.
3.  **Deployment**:
    Aktifkan GitHub Pages melalui menu **Settings > Pages** di repositori GitHub Anda.

---

## 📬 Kontak & Dukungan

Dibuat dengan ❤️ oleh **MRD Rental Team**.
* **Website**: [mrdokey.github.io/mrdrent](https://mrdokey.github.io/mrdrent/)
* **WhatsApp**: [Hubungi Admin](https://wa.me/62895428400665)

---

### 📄 Lisensi
Proyek ini bersifat privat untuk operasional **Arta Rental** & **JSR**. Penggunaan ulang kode harus seizin pengembang.
