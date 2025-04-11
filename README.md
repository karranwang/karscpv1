# 🧿 Script Phishing WhatsApp Group Simulation  
**Made by [@karranwang](https://github.com/karranwang)**  

Simulasi tampilan grup WhatsApp yang dirancang untuk memberikan kesan percakapan real-time, lengkap dengan balasan otomatis, efek "sedang mengetik...", dan pengalihan ke halaman login secara otomatis.  

---

## 🟢 FITUR-FITUR UTAMA

### 1. ✅ Simulasi Chat WhatsApp Grup
- Menampilkan percakapan grup secara otomatis.
- Desain mirip WhatsApp: avatar, nama, nomor, pesan, balasan, dan waktu.
- Pesan muncul satu per satu, menyerupai chatting asli.
- Redirect otomatis ke `login.php` setelah pesan terakhir.

### 2. 🕒 Efek "Sedang Mengetik..." Sebelum Pesan Muncul
- Simulasi pengetikan sebelum tiap pesan muncul.
- Menambah nuansa realistis seperti di WhatsApp.

### 3. 🧠 Balasan Pesan & Gambar Otomatis
- Jika `reply` diawali dengan `#`, maka akan menampilkan gambar dengan nama sesuai tag (`#teenage` → `teenage.jpg`).
- Jika tidak, reply ditampilkan sebagai balasan teks biasa.

### 4. 🔄 Redirect Otomatis ke `login.php`
- Setelah semua pesan selesai, halaman langsung berpindah ke halaman login tanpa interaksi pengguna.

### 5. 🎨 Tampilan UI yang Responsif dan Mirip WhatsApp
- Header dengan nama grup dan avatar.
- Bubble chat dengan layout khas WA.
- Avatar pengguna di sebelah kiri setiap pesan.

### 6. 📱 Responsive Design
- Desain responsif menggunakan media queries.
- Tampilan tetap optimal di perangkat mobile.

### 7. 📦 Struktur Modular & Terorganisir
- **`index.html`** → Struktur halaman utama.
- **`style.css`** → Style dan layout visual.
- **`script.js`** → Logika chat dan animasi dinamis.
- Mudah dikembangkan atau dikustomisasi.

---

## ✨ Potensi Pengembangan (Optional)
Fitur tambahan yang bisa diterapkan:
- Tombol kirim pesan (interaksi dari pengguna).
- Sistem autentikasi login yang sebenarnya (`login.php`).
- Tambahan animasi atau efek transisi.
- Deteksi perangkat (hanya redirect di mobile).
- Sound notifikasi seperti "ping" saat pesan masuk.

---

## 🔐 Keamanan & Perlindungan Kode
Untuk mencegah pencurian atau penyalahgunaan:
- Obfuscate/meminify file **JavaScript** dan **CSS**.
- Blok akses developer tools jika diperlukan (opsional).
- Gunakan server-side logic untuk melindungi data sensitif.

---

## ⚠️ Disclaimer
Proyek ini dibuat hanya untuk **edukasi, simulasi UI/UX**, dan **tujuan pembelajaran**.  
**Dilarang digunakan untuk tujuan ilegal, phising, atau merugikan orang lain.**  
Penggunaan script ini sepenuhnya tanggung jawab pengguna.

---

## 💻 Author
**[@karranwang](https://github.com/karranwang)**  
Feel free to fork, modify, and build something creative ✨
