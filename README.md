<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Landing Page</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-50 text-gray-800">

  <!-- Navbar -->
  <header class="bg-white shadow-md sticky top-0">
    <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold text-blue-600">MySite</h1>
      <nav class="space-x-6">
        <a href="#" class="hover:text-blue-500">Home</a>
        <a href="#" class="hover:text-blue-500">About</a>
        <a href="#" class="hover:text-blue-500">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="text-center py-16 bg-gradient-to-r from-blue-50 to-blue-100">
    <h2 class="text-4xl font-extrabold mb-4">Sdiybt</h2>
    <p class="text-lg mb-6 text-gray-600">Click on any image below to explore more.</p>
    <a href="#gallery" class="bg-blue-600 text-white px-6 py-3 rounded-full shadow-md hover:bg-blue-700 transition">Get Started</a>
  </section>

  <!-- Clickable Image Gallery -->
  <section id="gallery" class="max-w-6xl mx-auto px-6 py-16">
    <h3 class="text-3xl font-bold text-center mb-12">Choose Your Path</h3>
    <div class="grid md:grid-cols-3 gap-8">
      
      <!-- Card 1 -->
      <a href="https://example.com/option1" target="_blank" class="group block rounded-2xl overflow-hidden shadow-lg hover:shadow-2xl transition">
        <img src="https://via.placeholder.com/400x250.png?text=Option+1" alt="Option 1" class="w-full h-56 object-cover group-hover:scale-105 transition duration-300" />
        <div class="p-4 bg-white">
          <h4 class="text-xl font-semibold group-hover:text-blue-600">Option 1</h4>
          <p class="text-gray-600">Description of this option goes here.</p>
        </div>
      </a>
      
      <!-- Card 2 -->
      <a href="https://example.com/option2" target="_blank" class="group block rounded-2xl overflow-hidden shadow-lg hover:shadow-2xl transition">
        <img src="https://via.placeholder.com/400x250.png?text=Option+2" alt="Option 2" class="w-full h-56 object-cover group-hover:scale-105 transition duration-300" />
        <div class="p-4 bg-white">
          <h4 class="text-xl font-semibold group-hover:text-blue-600">Option 2</h4>
          <p class="text-gray-600">Description of this option goes here.</p>
        </div>
      </a>
      
      <!-- Card 3 -->
      <a href="https://example.com/option3" target="_blank" class="group block rounded-2xl overflow-hidden shadow-lg hover:shadow-2xl transition">
        <img src="https://via.placeholder.com/400x250.png?text=Option+3" alt="Option 3" class="w-full h-56 object-cover group-hover:scale-105 transition duration-300" />
        <div class="p-4 bg-white">
          <h4 class="text-xl font-semibold group-hover:text-blue-600">Option 3</h4>
          <p class="text-gray-600">Description of this option goes here.</p>
        </div>
      </a>

    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-800 text-gray-200 py-8">
    <div class="max-w-6xl mx-auto px-6 flex flex-col md:flex-row justify-between items-center">
      <p>&copy; 2025 MySite. All rights reserved.</p>
      <div class="space-x-4 mt-4 md:mt-0">
        <a href="#" class="hover:text-blue-400">Privacy</a>
        <a href="#" class="hover:text-blue-400">Terms</a>
      </div>
    </div>
  </footer>

</body>
</html>
