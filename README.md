<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>IKHWAN ACADEMIC SPACE</title>

  <!-- Google Font -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;700;900&display=swap" rel="stylesheet">

  <!-- Tailwind CDN -->
  <script src="https://cdn.tailwindcss.com"></script>

  <style>
    body{
      font-family: 'Montserrat', sans-serif;
      background:#0f172a;
      color:white;
    }

    .glass{
      background: rgba(255,255,255,0.05);
      backdrop-filter: blur(10px);
      border:1px solid rgba(255,255,255,0.1);
    }

    .gradient-text{
      background: linear-gradient(to right,#38bdf8,#6366f1);
      -webkit-background-clip:text;
      -webkit-text-fill-color:transparent;
    }

    .sidebar{
      height:100vh;
      position:fixed;
      left:0;
      top:0;
      width:250px;
    }

    .content{
      margin-left:260px;
    }

    @media(max-width:768px){
      .sidebar{
        position:relative;
        width:100%;
        height:auto;
      }

      .content{
        margin-left:0;
      }
    }
  </style>
</head>

<body>

<!-- SIDEBAR -->
<div class="sidebar glass p-6">

  <h1 class="text-2xl font-black gradient-text mb-8">
    IKHWAN ACADEMIC SPACE
  </h1>

  <div class="space-y-4">

    <a href="#" class="block hover:text-cyan-400 transition">
      🏠 Beranda
    </a>

    <a href="#" class="block hover:text-cyan-400 transition">
      👤 Profil
    </a>

    <a href="#" class="block hover:text-cyan-400 transition">
      🏆 Prestasi
    </a>

    <a href="#" class="block hover:text-cyan-400 transition">
      📚 RPP
    </a>

    <a href="#" class="block hover:text-cyan-400 transition">
      📊 PPT
    </a>

    <a href="#" class="block hover:text-cyan-400 transition">
      🎮 Game
    </a>

    <a href="#" class="block hover:text-cyan-400 transition">
      🧩 Teka-teki
    </a>

    <a href="#" class="block hover:text-cyan-400 transition">
      🤖 Media AI
    </a>

  </div>

</div>

<!-- MAIN CONTENT -->
<div class="content">

  <!-- HEADER -->
  <header class="sticky top-0 z-50 glass p-5 flex justify-between items-center">

    <div>
      <h2 class="text-xl font-bold">
        Dashboard Portfolio
      </h2>
    </div>

    <button class="bg-cyan-500 hover:bg-cyan-600 px-5 py-2 rounded-xl font-bold transition">
      Login Admin
    </button>

  </header>

  <!-- HERO -->
  <section class="p-8">

    <div class="glass rounded-3xl p-8">

      <h1 class="text-4xl md:text-5xl font-black gradient-text mb-4">
        Nasikhul Ikhwan
      </h1>

      <p class="text-gray-300 mb-6">
        Mahasiswa Pendidikan Bahasa Indonesia - STKIP Al Hikmah Surabaya
      </p>

      <div class="grid md:grid-cols-2 gap-5">

        <div class="glass p-5 rounded-2xl">
          <h3 class="font-bold text-cyan-400 mb-2">
            Informasi Akademik
          </h3>

          <p>NIM : 230142001</p>
          <p>Prodi : Pendidikan Bahasa Indonesia</p>
          <p>Kampus : STKIP Al Hikmah Surabaya</p>

        </div>

        <div class="glass p-5 rounded-2xl">
          <h3 class="font-bold text-cyan-400 mb-2">
            Keahlian
          </h3>

          <p>✔ Desain Grafis</p>
          <p>✔ Media Pembelajaran</p>
          <p>✔ Editing Video</p>
          <p>✔ Pengembangan Konten AI</p>

        </div>

      </div>

    </div>

  </section>

  <!-- ADMIN DASHBOARD -->
  <section class="p-8">

    <h2 class="text-3xl font-black mb-6 gradient-text">
      Admin Dashboard
    </h2>

    <div class="grid md:grid-cols-2 gap-6">

      <!-- FORM PROFIL -->
      <div class="glass p-6 rounded-3xl">

        <h3 class="text-2xl font-bold mb-5">
          Input Profil
        </h3>

        <form class="space-y-4">

          <input type="text" placeholder="Nama Lengkap"
            class="w-full p-4 rounded-xl bg-slate-800 border border-slate-700">

          <input type="text" placeholder="Tempat, Tanggal Lahir"
            class="w-full p-4 rounded-xl bg-slate-800 border border-slate-700">

          <input type="text" placeholder="NIM"
            class="w-full p-4 rounded-xl bg-slate-800 border border-slate-700">

          <input type="text" placeholder="Program Studi"
            class="w-full p-4 rounded-xl bg-slate-800 border border-slate-700">

          <textarea placeholder="Pengalaman"
            class="w-full p-4 rounded-xl bg-slate-800 border border-slate-700 h-32"></textarea>

          <button class="bg-cyan-500 hover:bg-cyan-600 w-full py-4 rounded-xl font-bold">
            Simpan Profil
          </button>

        </form>

      </div>

      <!-- FORM RPP -->
      <div class="glass p-6 rounded-3xl">

        <h3 class="text-2xl font-bold mb-5">
          Input RPP
        </h3>

        <form class="space-y-4">

          <select class="w-full p-4 rounded-xl bg-slate-800 border border-slate-700">

            <option>Fase D</option>
            <option>Fase E</option>
            <option>Fase F</option>

          </select>

          <input type="text" placeholder="Judul Materi"
            class="w-full p-4 rounded-xl bg-slate-800 border border-slate-700">

          <input type="file"
            class="w-full p-4 rounded-xl bg-slate-800 border border-slate-700">

          <textarea placeholder="Deskripsi Materi"
            class="w-full p-4 rounded-xl bg-slate-800 border border-slate-700 h-32"></textarea>

          <button class="bg-indigo-500 hover:bg-indigo-600 w-full py-4 rounded-xl font-bold">
            Upload RPP
          </button>

        </form>

      </div>

    </div>

  </section>

  <!-- REPOSITORY -->
  <section class="p-8">

    <h2 class="text-3xl font-black mb-6 gradient-text">
      Repository Akademik
    </h2>

    <div class="grid md:grid-cols-3 gap-5">

      <!-- CARD -->
      <div class="glass rounded-3xl p-5">

        <h3 class="text-xl font-bold mb-3">
          Fase D
        </h3>

        <ul class="space-y-2 text-gray-300">

          <li>📘 Teks Deskripsi</li>
          <li>📘 Prosedur</li>
          <li>📘 Berita</li>
          <li>📘 Cerpen</li>
          <li>📘 Drama</li>

        </ul>

      </div>

      <!-- CARD -->
      <div class="glass rounded-3xl p-5">

        <h3 class="text-xl font-bold mb-3">
          Fase E
        </h3>

        <ul class="space-y-2 text-gray-300">

          <li>📗 Eksposisi</li>
          <li>📗 Negosiasi</li>
          <li>📗 Hikayat</li>
          <li>📗 Cerpen</li>

        </ul>

      </div>

      <!-- CARD -->
      <div class="glass rounded-3xl p-5">

        <h3 class="text-xl font-bold mb-3">
          Fase F
        </h3>

        <ul class="space-y-2 text-gray-300">

          <li>📕 Karya Ilmiah</li>
          <li>📕 Proposal</li>
          <li>📕 Biografi</li>
          <li>📕 Film Pendek</li>

        </ul>

      </div>

    </div>

  </section>

  <!-- FOOTER -->
  <footer class="glass mt-10 p-8 text-center">

    <h3 class="text-2xl font-bold gradient-text mb-3">
      IKHWAN ACADEMIC SPACE
    </h3>

    <p class="text-gray-300">
      WhatsApp : 08xxxxxxxxxx
    </p>

    <p class="text-gray-300">
      Email : nasikhul@example.com
    </p>

    <div class="flex justify-center gap-5 mt-4 text-2xl">

      <a href="#">📷</a>
      <a href="#">🎵</a>
      <a href="#">📘</a>

    </div>

    <p class="mt-5 text-gray-500">
      © 2026 IKHWAN ACADEMIC SPACE
    </p>

  </footer>

</div>

</body>
</html>
