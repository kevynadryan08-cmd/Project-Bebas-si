<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Study Case - Git &amp; GitHub Workshop</title>
  <link rel="stylesheet" href="style.css">
 
  <!--
    TODO (Anggota 2 - branch "styling"):
    Tambahkan tag <link> di bawah ini untuk menghubungkan file style.css
    Contoh: <link rel="stylesheet" href="style.css">
  -->


</head>
<body>

  <header class="navbar">
    <h1 class="logo">Profile Card</h1>
    <div class="navbar-actions">
      <nav class="member-nav" aria-label="Navigasi anggota">
        <button class="member-link active" type="button" data-member="0" aria-pressed="true">1. Kevyn Adryan Liong</button>
        <button class="member-link" type="button" data-member="1" aria-pressed="false">2. Ganice Geralyn</button>
        <button class="member-link" type="button" data-member="2" aria-pressed="false">3. Darryll Adrien Putra Purnomo</button>
      </nav>
      <button id="theme-toggle" class="btn-toggle">🌙 Dark Mode</button>
    </div>
  </header>

  <main>
    <section class="hero">
      <img
        src="https://i.pinimg.com/736x/fc/af/7a/fcaf7aec4b7be05a0d062eff7851d2aa.jpg"
        alt="Foto profil Anggota 1"
        class="avatar"
      />
      <h2 id="user-name">Kevyn Adryan  Liong</h2>
      <p id="user-role">Frontend Developer</p>
      <button id="counter-btn" class="btn-primary">
        👍 Like (<span id="counter">0</span>)
      </button>
    </section>

<section class="about">
      <h3>Tentang Saya</h3>
      <p>
        Saya fokus membangun tampilan web yang rapi, responsif, dan mudah
        digunakan melalui struktur HTML dan desain antarmuka yang konsisten.
      </p>
    </section>

<section class="skills">
      <h3>Skill</h3>
      <ul id="skill-list">
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
      </ul>
    </section>
  </main>

  <footer>
    <p>&copy; 2026 Workshop Git &amp; GitHub</p>
  </footer>

 
  <!--
    TODO (Anggota 3 - branch "scripting"):
    Tambahkan tag <script> di bawah ini (sebelum </body>) untuk
    menghubungkan file script.js
    Contoh: <script src="script.js"></script>
  -->


</body>
</html>

## Visualisasi

<!-- Tempel screenshot tampilan halaman di sini, atau link demo (misalnya GitHub Pages).-->

![Screenshot](link-screenshot-kamu.png)

Live Demo: [link-demo-jika-ada](#)

---

## Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla)
- Git & GitHub

---

## Fitur Utama

- [ ] Toggle Dark Mode
- [ ] Like Counter interaktif
- [ ] Responsive layout
- [ ] _(tambahkan fitur lain sesuai pengembangan kelompok)_

---


## Contribution

| Jokowi Muda | Role | Kontribusi |
|---|---|---|
| Kevyn Adryan Liong | Project Initiator | Membuat repository, mengatur akses kolaborator, commit `index.html` |
| Ganice Geralyn | Styling Engineer | Membuat branch `styling`, menambahkan & menghubungkan `style.css` |
| Darryll Adrien Putra Purnomo | Script Engineer | Membuat branch `scripting`, menambahkan & menghubungkan `script.js` |

---

## How to Run

1. Clone repository ini:
   ```bash
   git clone <url-repo-kalian>
   ```
2. Buka folder hasil clone, lalu klik dua kali file `index.html` (atau klik kanan → Open with → Browser).

## Feature Improvement

Ide pengembangan lanjutan jika project ini dilanjutkan, misalnya:

- Menyimpan status like counter ke `localStorage`
- Menambahkan animasi transisi
- Membuat halaman menjadi responsive penuh untuk mobile
- Deploy otomatis via GitHub Actions ke GitHub Pages

