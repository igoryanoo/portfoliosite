<template>
  <nav class="bg-zinc-800 text-white py-4 px-8 flex justify-between items-center font-bold">
    <h1 class="text-4xl">&lt;igor/&gt;</h1>
    <ul class="flex gap-6 text-xl">
      <li><router-link to="/" class="hover:underline">Home</router-link></li>
      <li><router-link to="/about" class="hover:underline">Sobre</router-link></li>
      <li><router-link to="/contact" class="hover:underline">Contato</router-link></li>
    </ul>
    <div class="flex space-x-6 justify-end text-2xl">
      <a href="https://www.linkedin.com/in/igor-yano-8624b5312/" class="text-white hover:text-blue-400"><i class="fab fa-linkedin"></i></a>
      <a href="https://github.com/igoryanoo" class="text-white hover:text-gray-300"><i class="fab fa-github"></i></a>
      <a href="mailto:igoryano248@gmail.com" class="text-white hover:text-red-400"><i class="fas fa-envelope"></i></a>
    </div>
  </nav>
</template>
