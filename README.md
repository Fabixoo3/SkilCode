<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sklep z usługami Discord & Minecraft</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-950 text-white font-sans">
  <!-- HEADER -->
  <header class="bg-gray-900 p-6 shadow-md">
    <div class="container mx-auto flex justify-between items-center">
      <h1 class="text-2xl font-bold text-blue-400">TwojeUsługi.pl</h1>
      <nav class="space-x-4">
        <a href="#dlaczego" class="hover:text-blue-400">Dlaczego?</a>
        <a href="#zakup" class="hover:text-blue-400">Jak kupić</a>
        <a href="#admin" class="hover:text-blue-400">Administracja</a>
      </nav>
    </div>
  </header>

  <!-- HERO -->
  <section class="text-center py-20 bg-gradient-to-b from-gray-900 to-gray-800">
    <h2 class="text-4xl font-bold mb-4">Profesjonalne usługi Discord & Minecraft</h2>
    <p class="text-gray-300 mb-6">Boty, pluginy, paczki – wszystko, czego potrzebujesz, w jednym miejscu.</p>
    <a href="#zakup" class="bg-blue-500 hover:bg-blue-600 text-white px-6 py-2 rounded-xl transition">Zamów teraz</a>
  </section>

  <!-- DLACZEGO -->
  <section id="dlaczego" class="p-10 max-w-4xl mx-auto">
    <h3 class="text-3xl font-bold mb-6 text-center">Dlaczego warto kupować?</h3>
    <ul class="space-y-4 text-lg">
      <li>✅ Oszczędzasz czas i nerwy – wszystko działa od razu.</li>
      <li>✅ Wysoka jakość – testowane i aktualizowane przez nasz zespół.</li>
      <li>✅ Wsparcie techniczne – nie zostajesz sam z problemami.</li>
      <li>✅ Indywidualne rozwiązania – tworzymy też na zamówienie.</li>
    </ul>
  </section>

  <!-- JAK ZAKUPIĆ -->
  <section id="zakup" class="bg-gray-800 p-10 max-w-4xl mx-auto rounded-xl my-10">
    <h3 class="text-3xl font-bold mb-6 text-center">Jak zakupić usługę?</h3>
    <ol class="list-decimal list-inside text-lg space-y-3">
      <li>Wejdź na nasz serwer Discord (link poniżej).</li>
      <li>Otwórz ticket lub napisz do administracji.</li>
      <li>Ustal szczegóły – co potrzebujesz i na kiedy.</li>
      <li>Dokonaj płatności (PayPal, Blik, Przelew, PSC).</li>
      <li>Otrzymujesz gotowy produkt w ustalonym czasie.</li>
    </ol>
    <div class="text-center mt-6">
      <a href="https://discord.gg/twojlink" target="_blank" class="text-blue-400 underline">Dołącz do Discorda</a>
    </div>
  </section>

  <!-- ADMINISTRACJA -->
  <section id="admin" class="p-10 max-w-4xl mx-auto">
    <h3 class="text-3xl font-bold mb-6 text-center">Administracja</h3>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6 text-lg">
      <div class="bg-gray-900 p-4 rounded-xl shadow-md">
        <h4 class="text-xl font-bold text-blue-400">WizaDev</h4>
        <p>Główny programista, twórca botów i pluginów.</p>
      </div>
      <div class="bg-gray-900 p-4 rounded-xl shadow-md">
        <h4 class="text-xl font-bold text-blue-400">Zielonka</h4>
        <p>Wsparcie klienta, konfiguracje, kontakt Discord.</p>
      </div>
      <!-- Dodaj więcej administratorów w podobnym stylu -->
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="bg-gray-900 text-center py-6 mt-10 text-gray-500 text-sm">
    &copy; 2025 TwojeUsługi.pl – Wszystkie prawa zastrzeżone | <a href="https://discord.gg/twojlink" class="underline">Discord</a>
  </footer>
</body>
</html>
