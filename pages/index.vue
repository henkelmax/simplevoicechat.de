<template>
  <body class="min-h-screen bg-gray-900 flex items-center justify-center text-white font-sans overflow-hidden">
  <div class="text-center">
    <h1 class="text-5xl font-bold mb-4 animate-fade-in-up">
      Simple Voice Chat
    </h1>
    <p class="text-xl mb-8 animate-fade-in-up animation-delay-1">
      Enhance your in-game experience with immersive voice communication.</p>
    <div class="flex justify-center space-x-4 animate-fade-in-up animation-delay-2">
      <a href="https://modrinth.com/plugin/simple-voice-chat/versions" class="px-6 py-3 bg-blue-500 hover:bg-blue-700 rounded-md transition-all duration-300">
        Download
      </a>
      <a href="https://modrepo.de/minecraft/voicechat/wiki/installation" class="px-6 py-3 bg-gray-700 hover:bg-gray-500 rounded-md transition-all duration-300">
        Setup Guide
      </a>
    </div>
  </div>
  </body>
</template>

<style scoped>
@keyframes fadeInUp {
  0% {
    opacity: 0;
    transform: translateY(40px);
  }
  100% {
    opacity: 1;
    transform: translateY(0px);
  }
}

.animate-fade-in-up {
  opacity: 0;
  animation-fill-mode: forwards;
  animation: fadeInUp 1s ease-out forwards;
}

.animation-delay-1 {
  animation-delay: 0.5s;
}

.animation-delay-2 {
  animation-delay: 1s;
}
</style>

<script setup lang="ts">
useHead({
  title: "Simple Voice Chat"
});
</script>