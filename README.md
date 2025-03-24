# WEBSITE PORTFOLIO - Fauzan Abdihi
Mobile Developer Portfolio

🔗 Live Demo: https://fauzanabdihi.github.io/WEBSITE-PORTFOLIO/

📌 Tentang Project
Website portofolio ini dibangun untuk memamerkan skill, pengalaman, dan proyek-proyek yang telah saya kerjakan sebagai Mobile Developer. Dibuat dengan HTML, CSS, dan JavaScript untuk tampilan yang responsif dan interaktif.

🛠 Teknologi & Tools yang Digunakan
📜 Struktur File
Copy
WEBSITE-PORTFOLIO/
├── index.html          # Halaman utama
├── styles/
│   └── style.css       # Styling utama
├── scripts/
│   └── script.js       # Interaktivitas & animasi
├── images/             # Gambar & assets
├── cv/                 # File CV
└── README.md           # Dokumentasi
💻 Frontend
✔ HTML5 – Struktur dasar website
✔ CSS3 – Styling & animasi (Flexbox, Grid, Media Queries)
✔ JavaScript – Interaksi, smooth scrolling, form handling
✔ Font Awesome – Ikon untuk UI
✔ Google Fonts – Typography modern

🎨 Fitur & Animasi
✅ Responsive Design – Tampilan optimal di mobile, tablet, & desktop
✅ Dark/Light Mode (Opsional, bisa ditambahkan)
✅ Smooth Scrolling – Navigasi halus ke setiap section
✅ Hover Effects – Animasi saat interaksi dengan tombol & card
✅ Dynamic Skill Bars – Visualisasi kemampuan teknis
✅ Portfolio Filter (Bisa dikembangkan lebih lanjut)

🚀 Cara Menjalankan Project
⚙️ Lokal Development
Clone repository

bash
Copy
git clone https://github.com/fauzanabdihi/WEBSITE-PORTFOLIO.git
cd WEBSITE-PORTFOLIO
Buka di browser

Buka file index.html di browser favorit Anda.

🌐 Deploy ke GitHub Pages
Push ke branch main

Buka Settings → Pages

Pilih:

Branch: main

Folder: / (root)

Simpan, website akan live di:
https://<username>.github.io/WEBSITE-PORTFOLIO/

📂 Struktur Kode Penting
1. index.html
Header/Navbar – Navigasi dengan efek hover

Hero Section – Gambar profil + tombol CTA

About Me – Deskripsi & informasi personal

Services – Card layanan dengan ikon

Portfolio – Grid project dengan overlay hover

Skills – Progress bar kemampuan teknis

Contact – Form + info media sosial

2. style.css
Variabel CSS (:root) untuk warna & font

Media Queries untuk responsif:

css
Copy
@media (max-width: 768px) {
  /* Mobile styles */
}
Animasi Keyframes (e.g., floating image):

css
Copy
@keyframes float {
  0% { transform: translateY(0); }
  50% { transform: translateY(-15px); }
  100% { transform: translateY(0); }
}
3. script.js
Mobile Menu Toggle

js
Copy
burger.addEventListener('click', () => {
  nav.classList.toggle('active');
});
Smooth Scrolling

js
Copy
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
  anchor.addEventListener('click', smoothScroll);
});
Form Handling (Alert sederhana)

🔧 Potensi Pengembangan
Tambahkan Dark Mode

Integrasi dengan API (e.g., GitHub Projects)

Animasi Lazy Loading

Blog Section

📬 Kontak
📧 Email: fauzan@example.com
🔗 LinkedIn: Fauzan Abdihi
🐱 GitHub: fauzanabdihi

⭐ Feel free to fork, contribute, or use as a template!
Dibuat dengan ❤️ oleh Fauzan Abdihi

📜 License
MIT © 2023 Fauzan Abdihi

README ini memberikan gambaran lengkap tentang:
✅ Teknologi yang digunakan
✅ Struktur kode
✅ Cara menjalankan
✅ Fitur & pengembangan
✅ Kontribusi & lisensi

Anda bisa menyesuaikan bagian kontak, deskripsi, dan fitur sesuai kebutuhan! 🚀
