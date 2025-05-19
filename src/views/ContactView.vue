<template>
  <div class="flex items-center justify-center">
    <div class="container mx-auto px-4 py-8 grid grid-cols-1 md:grid-cols-2 gap-8 text-white">
      <div class="flex flex-col space-y-4">
        <h2 class="text-4xl font-bold mb-4">Entre em Contato</h2>  
        <form action="#" method="POST" class="space-y-4">
          <div class="flex flex-col">
            <label for="name" class="text-xl mb-2">Nome:</label>
            <input id="name" type="text" placeholder="Digite seu nome" class="bg-transparent border-b-2 border-white focus:outline-none text-white py-2 px-4" required/>
          </div>
          <div class="flex flex-col">
            <label for="email" class="text-xl mb-2">Email:</label>
            <input id="email" type="email" placeholder="Digite seu email" class="bg-transparent border-b-2 border-white focus:outline-none text-white py-2 px-4"/>
          </div>
          <div class="flex flex-col">
            <label for="message" class="text-xl mb-2">Mensagem:</label>
            <input id="email" type="email" placeholder="Digite sua mensagem" class="bg-transparent border-b-2 border-white focus:outline-none text-white py-2 px-4" required/>
          </div>
          <button type="submit" class="w-40 bg-blue-400 py-3 text-white rounded-md">Enviar</button>
        </form>
      </div>

      <div class="flex flex-col space-y-4">
        <h2 class="text-4xl font-bold mb-4">Redes Sociais</h2>
        <div class="flex flex-col space-y-3">
          <a href="https://www.instagram.com/igor_yano/" class="flex items-center space-x-3 text-lg text-pink-800">
            <i class="fab fa-instagram"></i><span>Instagram</span></a>

          <a href="https://www.facebook.com/igor.yanomaraci.3?locale=pt_BR" class="flex items-center space-x-3 text-lg text-blue-500">
            <i class="fab fa-facebook"></i><span>Facebook</span>
          </a>
          <a href="https://wa.me/5514988085465" class="flex items-center space-x-3 text-lg text-lime-500">
            <i class="fa-brands fa-whatsapp"></i>
            <span>WhatsApp</span>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>
