# 🦜 Bird Detection Web App using YOLOv8 and Flask

Proyek ini adalah aplikasi web sederhana yang memungkinkan pengguna mengunggah gambar atau video burung, kemudian mendeteksinya secara otomatis menggunakan model YOLOv8. Aplikasi dibangun menggunakan framework Flask dan dapat diakses secara publik melalui ngrok.

## 📁 Struktur Proyek

- `ultralytics` - Untuk pemodelan dan deteksi objek menggunakan YOLOv8.
- `OpenCV` - Untuk menangani pemrosesan gambar dan video.
- `Flask` - Untuk membangun backend aplikasi web.
- `pyngrok` - Untuk membuat endpoint publik ke aplikasi lokal.

## 🚀 Fitur Utama

- Deteksi burung dalam gambar.
- Deteksi burung dalam video.
- Tampilan hasil deteksi (bounding box dan label).
- Deployment mudah menggunakan ngrok (tanpa server).

## 🛠️ Instalasi

Pastikan Anda memiliki Python 3.8+ terinstal. Kemudian jalankan perintah berikut untuk menginstal dependensi:

```bash
pip install ultralytics flask pyngrok opencv-python-headless
