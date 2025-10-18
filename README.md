# Portofolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portfolio | Nama Kamu</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-900 text-gray-100 font-sans">
  <!-- Navbar -->
  <nav class="bg-gray-800 shadow p-4 flex justify-between items-center sticky top-0 z-50">
    <h1 class="text-2xl font-bold text-blue-400">Fullstack Dev</h1>
    <div class="space-x-4">
      <a href="#about" class="hover:text-blue-400">About</a>
      <a href="#skills" class="hover:text-blue-400">Skills</a>
      <a href="#projects" class="hover:text-blue-400">Projects</a>
      <a href="#contact" class="hover:text-blue-400">Contact</a>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="text-center py-20 bg-gradient-to-b from-gray-900 to-gray-800">
    <div class="w-32 h-32 mx-auto mb-6 rounded-full overflow-hidden border-4 border-blue-400">
      <img src="https://via.placeholder.com/150" alt="Foto Profil" class="w-full h-full object-cover" />
    </div>
    <h2 class="text-4xl font-bold mb-4">Hi, I'm <span class="text-blue-400">[RANDI ZIKRA]</span></h2>
    <p class="text-lg mb-6 text-gray-300">Full Stack Developer & Data Entry Specialist</p>
    <a href="#projects" class="bg-blue-500 text-white px-6 py-3 rounded-lg hover:bg-blue-600 transition">Lihat Project</a>
  </section>

  <!-- About Section -->
  <section id="about" class="max-w-4xl mx-auto py-16 px-4">
    <h3 class="text-2xl font-bold mb-4 text-blue-400">Tentang Saya</h3>
    <p class="text-gray-300 leading-relaxed">
      Saya seorang mahasiswa yang bersemangat membangun aplikasi web modern dan juga memiliki keahlian dalam data entry dan pengolahan data. Fokus saya adalah membuat solusi digital yang fungsional, cepat, dan mudah digunakan.
    </p>
  </section>

  <!-- Skills Section -->
  <section id="skills" class="bg-gray-800 py-16">
    <div class="max-w-5xl mx-auto px-4">
      <h3 class="text-2xl font-bold mb-8 text-center text-blue-400">Skills</h3>
      <div class="grid grid-cols-2 md:grid-cols-4 gap-6 text-center">
        <div><p class="font-semibold">HTML5</p></div>
        <div><p class="font-semibold">CSS3</p></div>
        <div><p class="font-semibold">JavaScript (ES6+)</p></div>
        <div><p class="font-semibold">React.js</p></div>
        <div><p class="font-semibold">Next.js</p></div>
        <div><p class="font-semibold">Tailwind CSS</p></div>
        <div><p class="font-semibold">Node.js</p></div>
        <div><p class="font-semibold">PHP / Laravel</p></div>
        <div><p class="font-semibold">Python (Flask/FastAPI)</p></div>
        <div><p class="font-semibold">MySQL / PostgreSQL</p></div>
        <div><p class="font-semibold">MongoDB</p></div>
        <div><p class="font-semibold">Git & GitHub</p></div>
        <div><p class="font-semibold">Excel / Google Sheets</p></div>
        <div><p class="font-semibold">Pandas (Python)</p></div>
        <div><p class="font-semibold">CMS / WordPress</p></div>
        <div><p class="font-semibold">Data Cleaning</p></div>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="max-w-5xl mx-auto py-16 px-4">
    <h3 class="text-2xl font-bold mb-8 text-center text-blue-400">Project</h3>
    <div class="grid md:grid-cols-3 gap-8">
      <div class="bg-gray-800 rounded-lg shadow p-4">
        <img src="https://via.placeholder.com/300x180" alt="Project 1" class="rounded mb-4" />
        <h4 class="font-bold text-lg mb-2">Project 1</h4>
        <p class="text-gray-400 text-sm mb-4">Deskripsi singkat project. Bisa berupa aplikasi web, dashboard, atau automation tools.</p>
        <a href="#" class="text-blue-400 font-semibold hover:underline">Lihat Live</a>
      </div>
      <div class="bg-gray-800 rounded-lg shadow p-4">
        <img src="https://via.placeholder.com/300x180" alt="Project 2" class="rounded mb-4" />
        <h4 class="font-bold text-lg mb-2">Project 2</h4>
        <p class="text-gray-400 text-sm mb-4">Deskripsi singkat project kedua.</p>
        <a href="#" class="text-blue-400 font-semibold hover:underline">Lihat Live</a>
      </div>
      <div class="bg-gray-800 rounded-lg shadow p-4">
        <img src="https://via.placeholder.com/300x180" alt="Project 3" class="rounded mb-4" />
        <h4 class="font-bold text-lg mb-2">Project 3</h4>
        <p class="text-gray-400 text-sm mb-4">Deskripsi singkat project ketiga.</p>
        <a href="#" class="text-blue-400 font-semibold hover:underline">Lihat Live</a>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="bg-gradient-to-b from-gray-800 to-gray-900 text-white py-16 text-center">
    <h3 class="text-2xl font-bold mb-4 text-blue-400">Hubungi Saya</h3>
    <p class="mb-6 text-gray-300">Tertarik bekerja sama? Kirim pesan langsung ke email saya!</p>
    <a href="mailto:randypradytia@gmail.com" class="bg-blue-500 text-white px-6 py-3 rounded-lg font-semibold hover:bg-blue-600 transition">Email Saya</a>
    <a href="https://wa.me/6289509017068" target="_blank" class="inline-block mt-4 bg-green-500 text-white px-6 py-3 rounded-lg font-semibold hover:bg-green-600 transition">
  Hubungi via WhatsApp
</a>

  </section>

  <footer class="text-center py-4 text-sm text-gray-500">
    © 2025 Nama Kamu. Dibuat dengan ♥ dan Tailwind CSS.
  </footer>
</body>
</html>
