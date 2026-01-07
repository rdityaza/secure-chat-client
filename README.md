# Integrated Secure Messaging Client

![Vue.js](https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)

> **Tugas Besar Sistem Terintegrasi (II3160) - Tugas 3**
> Layanan antarmuka pengguna (Frontend) yang mengintegrasikan Chat Service dan Encryption Service.

## 📖 Deskripsi
Aplikasi web ini bertindak sebagai **Orchestrator** di sisi klien (*Client-Side Composition*). Aplikasi ini tidak memiliki database sendiri, melainkan menggabungkan dua layanan mikro independen:
1.  **Encryption Service:** (Milik Raditya) untuk mengenkripsi pesan sebelum dikirim.
2.  **Chat Core Service:** (Milik Partner: Mudzaki) untuk menyimpan dan mengirim pesan.

## 🌟 Fitur Integrasi
* **Secure Orchestration:** Pesan dienkripsi *on-the-fly* sebelum meninggalkan browser.
* **Multi-API Consumption:** Mengonsumsi endpoint dari dua domain berbeda secara bersamaan.
* **Decryption On-Demand:** Dekripsi pesan hanya dilakukan saat pengguna meminta (klik pesan).

## 💻 Cara Akses
Layanan ini telah dideploy dan di-hosting melalui *Embedding Strategy* pada server utama.

**Live Demo:** [https://radit.tugastst.my.id/](https://radit.tugastst.my.id/)

## 📂 Struktur File
* `index.html`: File utama yang memuat logika Vue.js untuk manajemen state chat dan pemanggilan API (Fetch).