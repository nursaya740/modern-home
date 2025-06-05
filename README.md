# modern-home<!DOCTYPE html>
<html lang="kk">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Modern Home – Заманауи үй сайты</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-50 font-sans text-gray-800">

  <!-- Header -->
  <header class="bg-white shadow-md px-6 py-4 flex justify-between items-center sticky top-0 z-50">
    <h1 class="text-2xl font-bold text-blue-600">Modern Home</h1>
    <nav class="space-x-4">
      <a href="#home" class="font-semibold text-blue-500">Басты бет</a>
      <a href="#gallery" class="hover:text-blue-500">Галерея</a>
      <a href="#services" class="hover:text-blue-500">Қызметтер</a>
      <a href="#contact" class="hover:text-blue-500">Байланыс</a>
    </nav>
  </header>

  <!-- Home / Hero Section -->
  <section id="home" class="relative h-[80vh] bg-cover bg-center flex items-center justify-center text-center text-white" style="background-image: url('https://images.unsplash.com/photo-1588854337119-3f8a0faff8c5');">
    <div class="bg-black/50 w-full h-full absolute top-0 left-0"></div>
    <div class="relative z-10 px-4">
      <h2 class="text-4xl md:text-5xl font-bold mb-6">Сіздің арманыңыздағы үй – бізбен бірге</h2>
      <a href="#gallery" class="inline-block bg-blue-600 hover:bg-blue-700 text-white px-6 py-3 rounded text-lg font-medium transition">Дизайнды көру</a>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="px-6 py-12 max-w-5xl mx-auto text-center">
    <h3 class="text-3xl font-bold mb-4">Біз туралы</h3>
    <p class="text-gray-700 text-lg max-w-3xl mx-auto">
      Modern Home — заманауи архитектура мен интерьер дизайнына маманданған кәсіби студия. Біз әр клиенттің арманына сай ерекше жобалар ұсынамыз.
    </p>
  </section>

  <!-- Advantages Section -->
  <section id="advantages" class="bg-gray-100 py-12 px-6">
    <h3 class="text-3xl font-bold text-center mb-10">Неліктен бізді таңдайды?</h3>
    <div class="grid md:grid-cols-3 gap-6 max-w-5xl mx-auto text-center">
      <div class="bg-white p-6 rounded-lg shadow">
        <div class="text-blue-600 text-4xl mb-3">🏠</div>
        <h4 class="text-xl font-semibold mb-2">Жеке жобалар</h4>
        <p>Әр үй – жеке идея. Біз стандартқа емес, адамға жұмыс жасаймыз.</p>
      </div>
      <div class="bg-white p-6 rounded-lg shadow">
        <div class="text-blue-600 text-4xl mb-3">💡</div>
        <h4 class="text-xl font-semibold mb-2">Креативті шешімдер</h4>
        <p>Инновациялық дизайн, кеңістікті тиімді қолдану, заманауи стильдер.</p>
      </div>
      <div class="bg-white p-6 rounded-lg shadow">
        <div class="text-blue-600 text-4xl mb-3">🔍</div>
        <h4 class="text-xl font-semibold mb-2">Толық бақылау</h4>
        <p>Идеядан бастап кілт тапсыруға дейінгі барлық кезеңдер бізде.</p>
      </div>
    </div>
  </section>

  <!-- Gallery Section -->
  <section id="gallery" class="px-6 py-8">
    <h2 class="text-3xl font-bold mb-4 text-gray-800 text-center max-w-5xl mx-auto">Жобалар галереясы</h2>
    <div class="mb-6 flex justify-center flex-wrap gap-4 max-w-5xl mx-auto">
      <button class="bg-blue-100 text-blue-700 px-4 py-2 rounded-full hover:bg-blue-200">Барлығы</button>
      <button class="bg-gray-200 px-4 py-2 rounded-full hover:bg-gray-300">Интерьер</button>
      <button class="bg-gray-200 px-4 py-2 rounded-full hover:bg-gray-300">Экстерьер</button>
      <button class="bg-gray-200 px-4 py-2 rounded-full hover:bg-gray-300">Модерн</button>
      <button class="bg-gray-200 px-4 py-2 rounded-full hover:bg-gray-300">Минимализм</button>
    </div>
    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6 max-w-5xl mx-auto">
      <div class="bg-white shadow-md rounded-lg overflow-hidden">
        <img src="https://source.unsplash.com/400x300/?modern-house,exterior" alt="Үй экстерьері" class="w-full h-56 object-cover" />
        <div class="p-4">
          <h3 class="font-semibold text-gray-800">Экстерьер – Модерн</h3>
          <p class="text-sm text-gray-500">Алматы, 2023</p>
        </div>
      </div>
      <div class="bg-white shadow-md rounded-lg overflow-hidden">
        <img src="https://source.unsplash.com/400x300/?living-room,modern" alt="Қонақ бөлме" class="w-full h-56 object-cover" />
        <div class="p-4">
          <h3 class="font-semibold text-gray-800">Қонақ бөлме – Минимализм</h3>
          <p class="text-sm text-gray-500">Астана, 2024</p>
        </div>
      </div>
      <div class="bg-white shadow-md rounded-lg overflow-hidden">
        <img src="https://source.unsplash.com/400x300/?kitchen,interior" alt="Ас үй" class="w-full h-56 object-cover" />
        <div class="p-4">
          <h3 class="font-semibold text-gray-800">Ас үй – Жеңіл стиль</h3>
          <p class="text-sm text-gray-500">Шымкент, 2024</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Services Section -->
  <section id="services" class="px-6 py-12">
    <h2 class="text-3xl font-bold text-center mb-10">Қызметтеріміз</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-5xl mx-auto">
      <div class="bg-white shadow-md rounded-lg p-6 text-center">
        <div class="mx-auto w-16 h-16 flex items-center justify-center bg-blue-100 rounded-full mb-4">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-blue-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 20h16M4 4h16M4 4v16M4 4l8 8" />
          </svg>
        </div>
        <h3 class="text-xl font-semibold mb-2">Жоба жасау</h3>
        <p>Тұрғын үй, коттедж, интерьер және экстерьерге арналған 3D жобалар дайындау. Тапсырыс берушінің талаптары мен стандарттарды ескере отырып жүзеге асырылады.</p>
      </div>
      <div class="bg-white shadow-md rounded-lg p-6 text-center">
        <div class="mx-auto w-16 h-16 flex items-center justify-center bg-blue-100 rounded-full mb-4">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-blue-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 10h.01M12 10h.01M16 10h.01M9 16h6m2 4H7a2 2 0 01-2-2V6a2 2 0 012-2h10a2 2 0 012 2v12a2 2 0 01-2 2z" />
          </svg>
        </div>
        <h3 class="text-xl font-semibold mb-2">Кеңес беру</h3>
        <p>Дизайн, стиль, түстер үйлесімі бойынша онлайн немесе офлайн форматта кәсіби кеңес алу мүмкіндігі.</p>
      </div>
      <div class="bg-white shadow-md rounded-lg p-6 text-center">
        <div class="mx-auto w-16 h-16 flex items-center justify-center bg-blue-100 rounded-full mb-4">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-blue-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-3 -3v6m-4 4h10a1 1 0 001-1V7a1 1 0 00-1-1H7a1 1 0 00-1 1v10a1 1 0 001 1z" />
          </svg>
        </div>
        <h3 class="text-xl font-semibold mb-2">Авторлық бақылау</h3>
        <p>Жоба құрылысы барысында орындалуын бақылау. Қателіктерді болдырмай, сапаның сақталуын қамтамасыз ету.</p>
      </div>
      <div class="bg-white shadow-md rounded-lg p-6 text-center">
        <div class="mx-auto w-16 h-16 flex items-center justify-center bg-blue-100 rounded-full mb-4">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-blue-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 3h12l2 7H4l2-7zM4 10h16v10H4V10z" />
          </svg>
        </div>
        <h3 class="text-xl font-semibold mb-2">Құрылыс материалдарын таңдау</h3>
        <p>Сапалы, үнемді және стильге сай құрылыс материалдарын таңдауда кеңес беру және жеткізушілерді ұсыну.</p>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="px-6 py-12 max-w-5xl mx-auto">
    <h2 class="text-3xl font-bold text-center mb-8">Бізбен байланысыңыз</h2>
    <div class="grid md:grid-cols-2 gap-10">
      <!-- Contact Info -->
      <div class="space-y-4">
        <p><strong>Мекенжай:</strong> Алматы қаласы, Төлебаев көшесі, 56</p>
        <p><strong>Телефон:</strong> +7 (707) 123 45 67</p>
        <p><strong>Email:</strong> info@modernhome.kz</p>
        <p><strong>Жұмыс уақыты:</strong> Дүйсенбі – Жұма, 09:00 – 18:00</p>
        <iframe class="w-full h-64 mt-4 rounded-lg shadow" src="https://maps.google.com/maps?q=Алматы&t=&z=13&ie=UTF8&iwloc=&output=embed" allowfullscreen loading="lazy"></iframe>
      </div>
      <!-- Contact Form -->
      <form class="bg-white shadow-md rounded-lg p-6 space-y-6" action="#" method="POST">
        <div>
          <label for="name" class="block font-semibold mb-1">Аты-жөні</label>
          <input type="text" id="name" name="name" required class="w-full border border-gray-300 rounded px-3 py-2 focus:outline-none focus:ring-2 focus:ring-blue-500" />
        </div>
        <div>
          <label for="email" class="block font-semibold mb-1">Электрондық пошта</label>
          <input type="email" id="email" name="email" required class="w-full border border-gray-300 rounded px-3 py-2 focus:outline-none focus:ring-2 focus:ring-blue-500" />
        </div>
        <div>
          <label for="message" class="block font-semibold mb-1">Хабарлама</label>
          <textarea id="message" name="message" rows="4" required class="w-full border border-gray-300 rounded px-3 py-2 focus:outline-none focus:ring-2 focus:ring-blue-500"></textarea>
        </div>
        <button type="submit" class="bg-blue-600 hover:bg-blue-700 text-white px-6 py-3 rounded font-semibold w-full">Жіберу</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-800 text-gray-200 text-center py-6 mt-12">
    <p>&copy; 2025 Modern Home. Барлық құқықтар қорғалған.</p>
  </footer>

</body>
</html>
