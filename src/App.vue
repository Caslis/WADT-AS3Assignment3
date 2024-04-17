<script setup lang="ts">
import Amirul from "./assets/Amirul.jpg";
</script>

<template>
  <main class="py-6 px-4 sm:p-6 md:py-10 md:px-8">
    <div
      class="max-w-4xl mx-auto grid grid-cols-1 lg:max-w-5xl lg:gap-x-20 lg:grid-cols-2"
    >
      <div
        class="relative p-3 col-start-1 row-start-1 flex flex-col-reverse rounded-lg bg-gradient-to-t from-black/75 via-black/0 sm:bg-none sm:row-start-2 sm:p-0 lg:row-start-1"
      >
        <h1
          class="mt-1 text-lg font-semibold text-white sm:text-slate-900 md:text-2xl dark:sm:text-white"
        >
          Mirul's Profile
        </h1>
        <p
          class="text-sm leading-4 font-medium text-white sm:text-slate-500 dark:sm:text-slate-400"
        >
          Mohammad Amirul Syafie😎
        </p>
      </div>
      <div
        class="grid gap-4 col-start-1 col-end-3 row-start-1 sm:mb-6 sm:grid-cols-4 lg:gap-6 lg:col-start-2 lg:row-end-6 lg:row-span-6 lg:mb-0"
      >
      <img :src="Amirul" alt="Student Image" />
      </div>
      <p
        class="mt-4 text-sm leading-6 col-start-1 sm:col-span-2 lg:mt-6 lg:row-start-4 lg:col-span-1 dark:text-slate-400"
      >
My name is Mohammad Amirul Syafie, and I am a student at Politeknik Brunei, specializing in Web Development. Outside of academics, I enjoy playing games, particularly Valorant. I have a keen interest in continuous learning and am always eager to gain new experiences.    </p>
    </div>
  </main>
</template>

<style scoped>
</style>
