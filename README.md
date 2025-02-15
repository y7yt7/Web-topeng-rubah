# Web-topeng-rubah
<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1.0" name="viewport"/>
  <title>
   Topeng Rubah
  </title>
  <script src="https://cdn.tailwindcss.com">
  </script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&amp;display=swap" rel="stylesheet"/>
  <style>
   body {
            font-family: 'Roboto', sans-serif;
        }
  </style>
 </head>
 <body class="bg-black text-white">
  <!-- Web Intro (Halaman Depan) -->
  <section class="min-h-screen flex flex-col items-center justify-center text-center">
   <img alt="Logo topeng rubah dengan desain misterius" class="mb-8" height="150" src="https://storage.googleapis.com/a1aa/image/WQ9K6dJzDrb1CJPdUJWZ4fD8ki36cUmMsKzreZhk7sxLkAHUA.jpg" width="150"/>
   <h1 class="text-4xl md:text-6xl font-bold text-red-600">
    Selamat Datang di Dunia Topeng Rubah
   </h1>
   <p class="mt-4 text-lg md:text-2xl text-gray-300">
    Misi dan visi komunitas kami adalah menjaga rahasia dan kebersamaan.
   </p>
   <button class="mt-8 px-6 py-3 bg-red-600 text-white rounded-full hover:bg-red-700 transition duration-300">
    Masuk untuk Anggota
   </button>
  </section>
  <!-- Sistem Data (Pengelolaan Anggota) -->
  <section class="py-16 bg-gray-900">
   <div class="container mx-auto px-4">
    <h2 class="text-3xl md:text-4xl font-bold text-center text-gold-500 mb-8">
     Pengelolaan Anggota
    </h2>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
     <div class="bg-gray-800 p-6 rounded-lg shadow-lg">
      <h3 class="text-2xl font-bold mb-4">
       Tambah Anggota
      </h3>
      <form>
       <div class="mb-4">
        <label class="block text-gray-400 mb-2">
         Nama Panggilan
        </label>
        <input class="w-full p-2 bg-gray-700 rounded" type="text"/>
       </div>
       <div class="mb-4">
        <label class="block text-gray-400 mb-2">
         ID Anggota
        </label>
        <input class="w-full p-2 bg-gray-700 rounded" type="text"/>
       </div>
       <div class="mb-4">
        <label class="block text-gray-400 mb-2">
         Tanggal Bergabung
        </label>
        <input class="w-full p-2 bg-gray-700 rounded" type="date"/>
       </div>
       <div class="mb-4">
        <label class="block text-gray-400 mb-2">
         Level Keanggotaan
        </label>
        <select class="w-full p-2 bg-gray-700 rounded">
         <option>
          Pemula
         </option>
         <option>
          Senior
         </option>
         <option>
          Master
         </option>
        </select>
       </div>
       <div class="mb-4">
        <label class="block text-gray-400 mb-2">
         Catatan Khusus
        </label>
        <textarea class="w-full p-2 bg-gray-700 rounded"></textarea>
       </div>
       <button class="w-full py-2 bg-red-600 rounded hover:bg-red-700 transition duration-300" type="submit">
        Tambah Anggota
       </button>
      </form>
     </div>
     <div class="bg-gray-800 p-6 rounded-lg shadow-lg">
      <h3 class="text-2xl font-bold mb-4">
       Statistik Keanggotaan
      </h3>
      <img alt="Grafik statistik keanggotaan komunitas Topeng Rubah" class="w-full rounded" height="300" src="https://storage.googleapis.com/a1aa/image/nfnhxLna8NUe2Uafr2ojJfL9fUfaFS6mlA5rOj4kkWdRCJwBF.jpg" width="400"/>
     </div>
    </div>
   </div>
  </section>
  <!-- Fitur Khusus untuk Anggota -->
  <section class="py-16 bg-gray-800">
   <div class="container mx-auto px-4">
    <h2 class="text-3xl md:text-4xl font-bold text-center text-gold-500 mb-8">
     Fitur Khusus untuk Anggota
    </h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
     <div class="bg-gray-700 p-6 rounded-lg shadow-lg">
      <h3 class="text-2xl font-bold mb-4">
       Profil Anggota
      </h3>
      <p class="text-gray-300">
       Menampilkan data pribadi, pencapaian, dan level keanggotaan.
      </p>
     </div>
     <div class="bg-gray-700 p-6 rounded-lg shadow-lg">
      <h3 class="text-2xl font-bold mb-4">
       Forum Diskusi
      </h3>
      <p class="text-gray-300">
       Ruang obrolan tertutup untuk anggota.
      </p>
     </div>
     <div class="bg-gray-700 p-6 rounded-lg shadow-lg">
      <h3 class="text-2xl font-bold mb-4">
       Koleksi Khusus
      </h3>
      <p class="text-gray-300">
       Unduhan wallpaper, lagu tema, atau dokumen komunitas.
      </p>
     </div>
    </div>
   </div>
  </section>
  <!-- Sistem Login -->
  <section class="py-16 bg-gray-900">
   <div class="container mx-auto px-4">
    <h2 class="text-3xl md:text-4xl font-bold text-center text-gold-500 mb-8">
     Sistem Login
    </h2>
    <div class="max-w-md mx-auto bg-gray-800 p-6 rounded-lg shadow-lg">
     <h3 class="text-2xl font-bold mb-4">
      Login Anggota
     </h3>
     <form>
      <div class="mb-4">
       <label class="block text-gray-400 mb-2">
        Email
       </label>
       <input class="w-full p-2 bg-gray-700 rounded" type="email"/>
      </div>
      <div class="mb-4">
       <label class="block text-gray-400 mb-2">
        Kata Sandi
       </label>
       <input class="w-full p-2 bg-gray-700 rounded" type="password"/>
      </div>
      <button class="w-full py-2 bg-red-600 rounded hover:bg-red-700 transition duration-300" type="submit">
       Masuk
      </button>
     </form>
     <div class="mt-4 text-center">
      <a class="text-gray-400 hover:text-gray-200" href="#">
       Lupa Kata Sandi?
      </a>
     </div>
    </div>
   </div>
  </section>
  <!-- Pengiriman Otomatis ke Grup -->
  <section class="py-16 bg-gray-800">
   <div class="container mx-auto px-4">
    <h2 class="text-3xl md:text-4xl font-bold text-center text-gold-500 mb-8">
     Pengiriman Otomatis ke Grup
    </h2>
    <div class="bg-gray-700 p-6 rounded-lg shadow-lg">
     <h3 class="text-2xl font-bold mb-4">
      Integrasi Grup
     </h3>
     <p class="text-gray-300 mb-4">
      Sambungkan web dengan platform seperti WhatsApp, Telegram, atau Discord API.
     </p>
     <h4 class="text-xl font-bold mb-2">
      Format Pesan Otomatis:
     </h4>
     <p class="text-gray-300 mb-2">
      Judul: "Pembaruan Anggota Baru!"
     </p>
     <p class="text-gray-300 mb-2">
      Isi:
     </p>
     <p class="text-gray-300 mb-2">
      Halo, Topeng Rubah!
     </p>
     <p class="text-gray-300 mb-2">
      Ada anggota baru/aktivitas baru:
     </p>
     <p class="text-gray-300 mb-2">
      Nama: [Nama Panggilan]
     </p>
     <p class="text-gray-300 mb-2">
      ID: [ID Anggota]
     </p>
     <p class="text-gray-300 mb-2">
      Level: [Level Keanggotaan]
     </p>
     <button class="mt-4 px-6 py-3 bg-red-600 text-white rounded-full hover:bg-red-700 transition duration-300">
      Kirim Manual
     </button>
    </div>
   </div>
  </section>
 </body>
</html>
