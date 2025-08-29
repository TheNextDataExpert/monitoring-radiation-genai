# Aplikasi Pencatatan Radiasi Kr-85

Ini adalah aplikasi web sederhana yang berfungsi sebagai formulir untuk mencatat data paparan radiasi dari sumber Krypton-85 (Kr-85). Aplikasi ini dirancang untuk digunakan oleh pekerja radiasi di berbagai area.

## Fitur Utama

-   **Formulir Input Data:** Memungkinkan pencatatan tanggal, jam, nama pekerja, area, dan hasil pengukuran radiasi pada jarak yang berbeda (1m, 5m, dan sekitar).
-   **Integrasi Google Sheets:** Data yang dikirim melalui formulir akan secara otomatis disimpan secara permanen di Google Sheets.
-   **Pemisahan Data Otomatis:** Skrip di backend akan secara cerdas memisahkan dan menyimpan data ke file Google Sheet yang berbeda berdasarkan area yang dipilih, memudahkan pengelolaan dan analisis data.
-   **Antarmuka Modern:** Didesain dengan antarmuka yang bersih dan responsif untuk kemudahan penggunaan di berbagai perangkat.

## Pengaturan

Untuk menjalankan aplikasi ini, Anda perlu menghubungkannya dengan Google Apps Script.

1.  Siapkan beberapa file Google Sheet (satu untuk setiap area).
2.  Buat proyek Google Apps Script dan gunakan kode yang disediakan untuk menangani pengiriman data.
3.  Deploy skrip sebagai Aplikasi Web dan salin URL-nya.
4.  Tempelkan URL tersebut ke dalam variabel `SCRIPT_URL` di dalam file `index.html`.
