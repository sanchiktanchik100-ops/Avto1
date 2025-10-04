<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>AvtoMaster24 — Онлайн-сервис для СТО</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="antialiased bg-gray-50 text-gray-900">
  <!-- Header -->
  <header class="bg-white shadow">
    <div class="max-w-6xl mx-auto flex items-center justify-between p-4">
      <div class="flex items-center gap-3">
        <div class="w-10 h-10 rounded-full bg-gradient-to-r from-orange-400 to-red-500 flex items-center justify-center text-white font-bold">AM</div>
        <div>
          <div class="text-lg font-bold text-blue-600">AvtoMaster24</div>
          <div class="text-xs text-gray-500">Онлайн-сервис для записи в СТО</div>
        </div>
      </div>
      <nav class="hidden md:flex gap-6 text-gray-700">
        <a href="#for-clients" class="hover:text-blue-600">Клиентам</a>
        <a href="#for-garages" class="hover:text-blue-600">СТО</a>
        <a href="#how" class="hover:text-blue-600">Как это работает</a>
        <a href="#contacts" class="hover:text-blue-600">Контакты</a>
      </nav>
      <div class="flex items-center gap-3">
        <a href="#signup-garage" class="px-4 py-2 border border-orange-400 text-orange-500 rounded-full font-medium hover:bg-orange-50">Подключить СТО</a>
        <a href="#contacts" class="px-4 py-2 bg-blue-600 text-white rounded-full font-medium hover:bg-blue-700">Записаться</a>
      </div>
    </div>
  </header>

  <!-- Hero -->
  <section class="bg-gradient-to-r from-blue-600 to-indigo-700 text-white py-20">
    <div class="max-w-6xl mx-auto px-4 grid md:grid-cols-2 gap-8 items-center">
      <div>
        <h1 class="text-4xl md:text-5xl font-extrabold leading-tight">AvtoMaster24 — Запись в СТО за 2 минуты</h1>
        <p class="mt-4 text-lg text-blue-100">Найди ближайшее СТО, сравни услуги и цены, запишись онлайн — всё в Telegram или на сайте. Удобно для владельцев авто и выгодно для автосервисов.</p>
        <div class="mt-6 flex gap-3">
          <a href="#contacts" class="px-6 py-3 bg-orange-400 text-white rounded-full font-semibold shadow hover:brightness-95">Записаться</a>
          <a href="#for-garages" class="px-6 py-3 border border-white/30 rounded-full text-white hover:bg-white/10">Для СТО</a>
        </div>

        <div class="mt-8 grid grid-cols-2 gap-4 text-sm text-blue-100">
          <div class="flex items-center gap-3">
            <div class="w-10 h-10 bg-white/10 rounded flex items-center justify-center">⏱</div>
            <div>
              <div class="font-semibold">Быстро</div>
              <div class="text-xs">Запись и подтверждение в несколько кликов</div>
            </div>
          </div>
          <div class="flex items-center gap-3">
            <div class="w-10 h-10 bg-white/10 rounded flex items-center justify-center">🔔</div>
            <div>
              <div class="font-semibold">Уведомления</div>
              <div class="text-xs">SMS / Telegram-уведомления о статусе</div>
            </div>
          </div>
        </div>
      </div>

      <div class="bg-white rounded-xl p-6 shadow">
        <h3 class="text-xl font-semibold mb-4">Записаться сейчас</h3>
        <form class="space-y-3">
          <input type="text" placeholder="Марка и модель" class="w-full border rounded p-3" />
          <input type="tel" placeholder="Телефон" class="w-full border rounded p-3" />
          <select class="w-full border rounded p-3">
            <option>Выберите услугу — ТО, Шиномонтаж, Ремонт под ключ</option>
            <option>Техническое обслуживание (ТО)</option>
            <option>Шиномонтаж</option>
            <option>Замена тормозных колодок</option>
          </select>
          <div class="flex gap-2">
            <input type="date" class="w-1/2 border rounded p-3" />
            <input type="time" class="w-1/2 border rounded p-3" />
          </div>
          <button class="w-full bg-blue-600 text-white py-3 rounded font-medium">Отправить заявку</button>
          <p class="text-xs text-gray-500">Мы вышлем подтверждение в Telegram / SMS.</p>
        </form>
      </div>
    </div>
  </section>

  <!-- Features -->
  <section class="max-w-6xl mx-auto px-4 py-12">
    <h2 class="text-2xl font-bold text-center mb-8">Что даёт AvtoMaster24</h2>
    <div class="grid md:grid-cols-3 gap-6">
      <div class="bg-white p-6 rounded-xl shadow">
        <div class="text-3xl mb-3">🔎</div>
        <h4 class="font-semibold mb-2">Поиск СТО</h4>
        <p class="text-gray-600 text-sm">Найди ближайшие автосервисы с отзывами, ценами и доступными окнами записи.</p>
      </div>
      <div class="bg-white p-6 rounded-xl shadow">
        <div class="text-3xl mb-3">📅</div>
        <h4 class="font-semibold mb-2">Управление расписанием</h4>
        <p class="text-gray-600 text-sm">СТО получают удобную панель для приёма и планирования заявок.</p>
      </div>
      <div class="bg-white p-6 rounded-xl shadow">
        <div class="text-3xl mb-3">💬</div>
        <h4 class="font-semibold mb-2">Коммуникации</h4>
        <p class="text-gray-600 text-sm">Уведомления клиентам, чат с мастером и статус-отчёты по ремонту.</p>
      </div>
    </div>
  </section>

  <!-- For garages -->
  <section id="for-garages" class="bg-blue-50 py-12">
    <div class="max-w-6xl mx-auto px-4 grid md:grid-cols-2 gap-8 items-center">
      <div>
        <h3 class="text-2xl font-bold mb-4">Для автосервисов</h3>
        <ul class="list-disc ml-5 text-gray-700 space-y-2">
          <li>Подключение без технических сложностей — регистрация и профиль.</li>
          <li>Получение заявок, управление очередью и календарём.</li>
          <li>Аналитика и отчёты по заявкам и выручке.</li>
        </ul>
        <div class="mt-6 flex gap-3">
          <a href="#signup-garage" class="px-5 py-3 bg-orange-400 text-white rounded-full font-semibold">Подключить СТО</a>
          <a href="#contacts" class="px-5 py-3 border border-blue-600 rounded-full text-blue-600">Связаться с менеджером</a>
        </div>
      </div>
      <div class="bg-white p-6 rounded-xl shadow">
        <h4 class="font-semibold mb-2">Простой профиль СТО</h4>
        <p class="text-gray-600 text-sm">Добавляйте услуги, рабочие окна и сотрудников. Приходите в систему — получайте первых клиентов уже в день подключения.</p>
        <div class="mt-4">
          <img src="https://images.unsplash.com/photo-1518459031867-a89b944bffe2?auto=format&fit=crop&w=800&q=60" alt="garage" class="rounded-md w-full" />
        </div>
      </div>
    </div>
  </section>

  <!-- How it works -->
  <section id="how" class="max-w-6xl mx-auto px-4 py-12">
    <h3 class="text-2xl font-bold text-center mb-8">Как это работает — 3 шага</h3>
    <div class="grid md:grid-cols-3 gap-6">
      <div class="bg-white p-6 rounded-xl shadow text-center">
        <div class="text-4xl mb-3">1</div>
        <h4 class="font-semibold mb-2">Клиент создаёт заявку</h4>
        <p class="text-gray-600 text-sm">Через сайт или Telegram-бот указывает марку авто, услугу и удобное время.</p>
      </div>
      <div class="bg-white p-6 rounded-xl shadow text-center">
        <div class="text-4xl mb-3">2</div>
        <h4 class="font-semibold mb-2">СТО подтверждает</h4>
        <p class="text-gray-600 text-sm">Сотрудник сервиса принимает заявку и назначает мастера.</p>
      </div>
      <div class="bg-white p-6 rounded-xl shadow text-center">
        <div class="text-4xl mb-3">3</div>
        <h4 class="font-semibold mb-2">Ремонт и отчёт</h4>
        <p class="text-gray-600 text-sm">Клиент получает уведомления о статусе и фото-отчёт после выполнения работ.</p>
      </div>
    </div>
  </section>

  <!-- Signup garage (simple form) -->
  <section id="signup-garage" class="bg-gray-100 py-12">
    <div class="max-w-4xl mx-auto px-4">
      <h3 class="text-2xl font-bold mb-4">Подключить СТО</h3>
      <p class="text-gray-700 mb-4">Оставьте заявку — наш менеджер свяжется и поможет настроить профиль.</p>
      <form class="grid md:grid-cols-2 gap-4 bg-white p-6 rounded-xl shadow">
        <input type="text" placeholder="Название СТО" class="border rounded p-3" />
        <input type="tel" placeholder="Контактный телефон" class="border rounded p-3" />
        <input type="text" placeholder="Город" class="border rounded p-3" />
        <input type="email" placeholder="Email менеджера" class="border rounded p-3" />
        <textarea placeholder="Комментарий / услуги" class="border rounded p-3 md:col-span-2"></textarea>
        <button class="md:col-span-2 bg-orange-400 text-white py-3 rounded font-semibold">Оставить заявку</button>
      </form>
    </div>
  </section>

  <!-- Contacts -->
  <section id="contacts" class="max-w-6xl mx-auto px-4 py-12 text-center">
    <h3 class="text-2xl font-bold mb-4">Контакты</h3>
    <p class="text-gray-700 mb-2">Телефон: <a href="tel:+77001112233" class="text-blue-600 hover:underline">+7 (700) 111-22-33</a></p>
    <p class="text-gray-700 mb-4">Email: <a href="mailto:hello@avtomaster24.kz" class="text-blue-600 hover:underline">hello@avtomaster24.kz</a></p>
    <div class="mt-4 flex justify-center gap-3">
      <a href="#" class="px-4 py-2 border rounded-full">Telegram</a>
      <a href="#" class="px-4 py-2 border rounded-full">WhatsApp</a>
      <a href="#" class="px-4 py-2 border rounded-full">Instagram</a>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-900 text-gray-400 py-6">
    <div class="max-w-6xl mx-auto px-4 text-center">
      <div class="mb-2">© 2025 AvtoMaster24 — Все права защищены</div>
      <div class="text-sm">Разработка и поддержка: <span class="text-white font-medium">AvtoMaster24 Team</span></div>
    </div>
  </footer>
</body>
</html>
