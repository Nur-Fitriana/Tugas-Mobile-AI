# IT-Terms Translator  
(AI Asisten Mahasiswa Informatika)

Tugas Praktik Pengembangan Aplikasi Mobile Berbasis AI  
Kelas IF 23 B

---

## 📝 Deskripsi
IT-Terms Translator adalah aplikasi asisten berbasis kecerdasan buatan (AI) yang dirancang untuk membantu mahasiswa Informatika memahami istilah-istilah teknologi dan pemrograman yang sering dianggap sulit.

Aplikasi ini menggunakan **Google Gemini AI (gemini-3-flash-preview)** untuk memberikan penjelasan istilah IT dengan bahasa Indonesia yang sederhana, singkat, dan mudah dipahami.

Aplikasi dibuat sederhana sesuai ketentuan tugas dan berfokus pada pemanfaatan AI sebagai asisten pembelajaran.

---

## ✨ Fitur Utama
- **AI Chatbot**
  Pengguna dapat bertanya tentang istilah atau konsep Informatika (contoh: API, Flutter, OOP, Framework).

- **Mode Respons AI**
  AI memberikan jawaban informatif dan ringkas sesuai pertanyaan pengguna.

- **Antarmuka Sederhana**
  Tampilan aplikasi dibuat minimalis dengan tema warna yang nyaman dan mudah digunakan.

- **Real-time AI Response**
  Jawaban AI ditampilkan langsung melalui integrasi Google Gemini.

---

## 🛠️ Tech Stack
- **Framework**: Flutter  
- **AI Model**: Google Gemini (`gemini-3-flash-preview`)  
- **State Management**: Riverpod  
- **Environment Variable**: Flutter Dotenv  

---

## 🚀 Cara Menjalankan Aplikasi
1. Clone repository ini ke perangkat lokal.
2. Pastikan Flutter SDK sudah terpasang.
3. Dapatkan API Key dari Google AI Studio:  
   https://aistudio.google.com/
4. Buat file `.env` di folder root project.
5. Tambahkan konfigurasi berikut:
   ```env
   GEMINI_API_KEY=API_KEY_KAMU