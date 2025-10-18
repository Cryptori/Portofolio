<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Renpa | Full Stack Developer</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    html {
      scroll-behavior: smooth;
    }
    .fade-in {
      opacity: 0;
      transform: translateY(20px);
      transition: opacity 0.8s ease-out, transform 0.8s ease-out;
    }
    .fade-in.show {
      opacity: 1;
      transform: translateY(0);
    }
  </style>
</head>
<body class="bg-black text-white font-sans">

  <!-- HERO -->
  <header class="min-h-screen flex flex-col justify-center items-center text-center px-4 fade-in">
    <img src="foto-profil.jpg" alt="Foto Profil" class="w-32 h-32 rounded-full mb-4 border-4 border-blue-400 shadow-lg">
    <h1 class="text-4xl md:text-5xl font-bold">Renpa</h1>
    <p class="text-blue-400 text-lg mt-2">Full Stack Developer & Data Enthusiast</p>
    <div class="mt-6 flex gap-4">
      <a href="https://wa.me/62xxxxxxxxxxx" target="_blank" class="bg-blue-500 px-5 py-2 rounded-full hover:bg-blue-600 transition">WhatsApp</a>
      <a href="mailto:emailkamu@gmail.com" class="border border-blue-500 px-5 py-2 rounded-full hover:bg-blue-500 hover:text-white transition">Email</a>
    </div>
    <a href="#projects" class="mt-10 text-blue-400 hover:underline">↓ Lihat Project</a>
  </header>

  <!-- SKILLS -->
  <section id="skills" class="py-16 bg-gray-950 px-6 fade-in">
    <h2 class="text-3xl font-bold text-center mb-10">Skills</h2>
    <div class="max-w-3xl mx-auto space-y-6">
      <div>
        <p class="mb-2">HTML / CSS / JavaScript</p>
        <div class="w-full bg-gray-800 rounded-full h-3">
          <div class="bg-blue-500 h-3 rounded-full w-[90%]"></div>
        </div>
      </div>
      <div>
        <p class="mb-2">PHP / Python</p>
        <div class="w-full bg-gray-800 rounded-full h-3">
          <div class="bg-blue-500 h-3 rounded-full w-[80%]"></div>
        </div>
      </div>
      <div>
        <p class="mb-2">Frontend & Backend Framework</p>
        <div class="w-full bg-gray-800 rounded-full h-3">
          <div class="bg-blue-500 h-3 rounded-full w-[75%]"></div>
        </div>
      </div>
      <div>
        <p class="mb-2">Data Entry & Admin Tools</p>
        <div class="w-full bg-gray-800 rounded-full h-3">
          <div class="bg-blue-500 h-3 rounded-full w-[85%]"></div>
        </div>
      </div>
    </div>
  </section>

  <!-- PROJECTS -->
  <section id="projects" class="py-16 px-6 fade-in">
    <h2 class="text-3xl font-bold text-center mb-10">Projects</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8 max-w-6xl mx-auto">
      <!-- Project 1 -->
      <div class="bg-gray-900 rounded-xl overflow-hidden shadow-lg hover:shadow-blue-500/40 transition hover:scale-105">
        <img src="project1.jpg" alt="Project 1" class="w-full h-48 object-cover">
        <div class="p-4">
          <h3 class="text-xl font-semibold mb-2">Project 1</h3>
          <p class="text-gray-400 text-sm mb-4">Deskripsi singkat project pertama kamu...</p>
          <a href="#" target="_blank" class="text-blue-400 hover:underline">View Project →</a>
        </div>
      </div>

      <!-- Project 2 -->
      <div class="bg-gray-900 rounded-xl overflow-hidden shadow-lg hover:shadow-blue-500/40 transition hover:scale-105">
        <img src="project2.jpg" alt="Project 2" class="w-full h-48 object-cover">
        <div class="p-4">
          <h3 class="text-xl font-semibold mb-2">Project 2</h3>
          <p class="text-gray-400 text-sm mb-4">Deskripsi singkat project kedua...</p>
          <a href="#" target="_blank" class="text-blue-400 hover:underline">View Project →</a>
        </div>
      </div>

      <!-- Project 3 -->
      <div class="bg-gray-900 rounded-xl overflow-hidden shadow-lg hover:shadow-blue-500/40 transition hover:scale-105">
        <img src="project3.jpg" alt="Project 3" class="w-full h-48 object-cover">
        <div class="p-4">
          <h3 class="text-xl font-semibold mb-2">Project 3</h3>
          <p class="text-gray-400 text-sm mb-4">Deskripsi singkat project ketiga...</p>
          <a href="#" target="_blank" class="text-blue-400 hover:underline">View Project →</a>
        </div>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="bg-gray-950 text-center py-6 text-gray-500 text-sm">
    © 2025 Renpa. Built with ❤️ and TailwindCSS.
  </footer>

  <script>
    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) entry.target.classList.add('show');
      });
    });
    document.querySelectorAll('.fade-in').forEach(el => observer.observe(el));
  </script>
</body>
</html>
