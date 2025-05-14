<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Habilita Fácil</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-white text-gray-800">
  <!-- Navbar -->
  <header class="bg-blue-600 text-white p-4 shadow-md sticky top-0 z-50">
    <div class="container mx-auto flex justify-between items-center">
      <h1 class="text-2xl font-bold">Habilita Fácil</h1>
      <nav class="space-x-4">
        <a href="#home" class="hover:underline">Home</a>
        <a href="#sobre" class="hover:underline">Sobre</a>
        <a href="#contato" class="hover:underline">Contato</a>
      </nav>
    </div>
  </header>

  <!-- Home -->
  <section id="home" class="min-h-screen flex items-center justify-center bg-blue-100 p-8">
    <div class="text-center max-w-xl">
      <h2 class="text-4xl font-bold mb-4">Facilitamos sua CNH de forma rápida e segura!</h2>
      <p class="text-lg mb-6">O Habilita Fácil é o seu aliado na conquista da carteira de motorista com menos burocracia e mais agilidade.</p>
      <a href="#contato" class="bg-blue-600 text-white px-6 py-3 rounded-xl shadow hover:bg-blue-700 transition">Fale Conosco</a>
    </div>
  </section>

  <!-- Sobre -->
  <section id="sobre" class="py-20 px-6 bg-white">
    <div class="max-w-3xl mx-auto text-center">
      <h2 class="text-3xl font-bold mb-6">Sobre o Habilita Fácil</h2>
      <p class="text-lg text-gray-700">Somos uma plataforma dedicada a simplificar o processo de habilitação no Brasil. Trabalhamos com consultoria, acompanhamento e suporte personalizado para quem deseja tirar ou regularizar a CNH.</p>
    </div>
  </section>

  <!-- Contato -->
  <section id="contato" class="py-20 px-6 bg-gray-100">
    <div class="max-w-xl mx-auto">
      <h2 class="text-3xl font-bold mb-6 text-center">Entre em Contato</h2>
      <form class="space-y-4">
        <input type="text" placeholder="Seu nome" class="w-full p-3 rounded border border-gray-300" required />
        <input type="email" placeholder="Seu e-mail" class="w-full p-3 rounded border border-gray-300" required />
        <textarea placeholder="Sua mensagem" class="w-full p-3 rounded border border-gray-300 h-32" required></textarea>
        <button type="submit" class="bg-blue-600 text-white px-6 py-3 rounded-xl hover:bg-blue-700 transition w-full">Enviar</button>
      </form>
    </div>
  </section>

  <!-- Rodapé -->
  <footer class="bg-blue-600 text-white text-center p-4">
    <p>&copy; 2025 Habilita Fácil. Todos os direitos reservados.</p>
  </footer>
</body>
</html>
