<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Mica Louise | E-Portfolio</title>
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 text-gray-800 font-sans">

  <!-- Header -->
  <header class="bg-rose-100 text-black py-8 text-center">
    <h1 class="text-4xl font-bold">Mica Louise's E-Portfolio</h1>
    <p class="text-lg mt-2">Web Developer | Designer | Esports Enthusiast</p>
  </header>

  <!-- Navigation -->
  <nav class="bg-rose-700">
    <ul class="flex flex-col sm:flex-row justify-center items-center gap-4 py-4 text-white text-sm font-medium">
      <li><a href="#about" class="hover:underline">About Me</a></li>
      <li><a href="#projects" class="hover:underline">Projects</a></li>
      <li><a href="#skills" class="hover:underline">Skills</a></li>
      <li><a href="#contact" class="hover:underline">Contact</a></li>
    </ul>
  </nav>


  <main class="max-w-4xl mx-auto p-6">


    <section id="about" class="mb-12">
      <h2 class="text-2xl font-semibold mb-6 border-b pb-2 border-gray-300">About Me</h2>

      <div class="flex flex-col sm:flex-row items-center sm:items-start gap-6">
        <!-- Profile Image -->
        <img src="H:\network 2\download.jpg" alt="Profile Photo" class="w-36 h-36 rounded-full object-cover border-4 border-gray-300 shadow-md">

        <!-- About Info -->
        <div class="text-gray-700 leading-relaxed space-y-4">
          <p>
            Hello! I'm <strong>Mica Louise</strong>, a passionate web developer and project manager specializing in building responsive and accessible websites using HTML, CSS, and JavaScript. I’m always eager to learn new technologies and take on creative projects that make a real impact.
          </p>

      
          <div class="bg-white p-4 rounded shadow-md">
            <h3 class="text-lg font-semibold mb-2 border-b pb-1 border-gray-200">Basic Information</h3>
            <ul class="space-y-1">
              <li><strong>Name:</strong> Mica Louise Nuega</li>
              <li><strong>Age:</strong> 21</li>
              <li><strong>Birthday:</strong> November 23, 2003</li>
              <li><strong>Address:</strong> Barangay Zone 4A, Mabini Street, Talisay City, Negros Occidental</li>
            </ul>
          </div>

  
          <div class="bg-white p-4 rounded shadow-md">
            <h3 class="text-lg font-semibold mb-2 border-b pb-1 border-gray-200">Affiliations</h3>
            <ul class="list-disc list-inside">
              <li>STI West Negros University Alumni</li>
              <li>Mustang Esports Board Member  SY 2023-2024</li>
              <li>SSG 3rd Year Representative SY. 2024-2025</li>
              <li>Mustang Esports Vice President  SY 2024-2025</li>
              <li>Mustang Esports Vice President for External Affairs SY 2025-2026</li>
              
            </ul>
          </div>
        </div>
      </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="mb-12">
      <h2 class="text-2xl font-semibold mb-4 border-b pb-2 border-gray-300">Projects</h2>

      <div class="bg-white p-5 rounded shadow mb-4">
        <h3 class="text-xl font-bold">Marbels Eatery App</h3>
        <p class="text-gray-700 mt-2">A responsive application for Mabels Eatery that has an Inventory, POS, and Ordering system. Built using React Native and Firebase.</p>
      </div>

      <div class="bg-white p-5 rounded shadow mb-4">
        <h3 class="text-xl font-bold">Portfolio Website</h3>
        <p class="text-gray-700 mt-2">This very site! Designed to showcase my work, skills, and contact information.</p>
      </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="mb-12">
      <h2 class="text-2xl font-semibold mb-4 border-b pb-2 border-gray-300">Skills</h2>
      <div class="flex flex-wrap gap-3">
        <span class="bg-gray-200 px-4 py-2 rounded-full">HTML</span>
        <span class="bg-gray-200 px-4 py-2 rounded-full">CSS</span>
        <span class="bg-gray-200 px-4 py-2 rounded-full">JavaScript</span>
        <span class="bg-gray-200 px-4 py-2 rounded-full">React-Native</span>
        <span class="bg-gray-200 px-4 py-2 rounded-full">Project Managing</span>
        <span class="bg-gray-200 px-4 py-2 rounded-full">Responsive Design</span>
      </div>
    </section>


    <section id="contact" class="mb-12">
      <h2 class="text-2xl font-semibold mb-4 border-b pb-2 border-gray-300">Contact</h2>
      <p class="mb-2">📧 Email: <a href="mlnuega@gmail.com" class="text-blue-600 hover:underline">mlnuega@gmail.com</a></p>
      <p class="mb-2">🐱 GitHub: <a href="https://github.com/psyche112303" target="_blank" class="text-blue-600 hover:underline">github.com/psyche112303</a></p>
    </section>

  </main>


  <footer class="bg-rose-700 text-white text-center py-6 mt-8">
    <p>&copy; 2025 Mica Louise. All rights reserved.</p>
  </footer>

</body>
</html>
