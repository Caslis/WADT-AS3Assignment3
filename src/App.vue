<script setup lang="ts">
import HelloWorld from "./components/HelloWorld.vue";
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
          Mohammad Amirul Syafie
        </p>
      </div>
      <div
        class="grid gap-4 col-start-1 col-end-3 row-start-1 sm:mb-6 sm:grid-cols-4 lg:gap-6 lg:col-start-2 lg:row-end-6 lg:row-span-6 lg:mb-0"
      >
      <img :src="Amirul" alt="Student Image" />
      </div>
      <dl
        class="mt-4 text-xs font-medium flex items-center row-start-2 sm:mt-1 sm:row-start-3 md:mt-2.5 lg:row-start-2"
      >
        <dd class="text-indigo-600 flex items-center dark:text-indigo-400">
            <path
              d="m12 5 2 5h5l-4 4 2.103 5L12 16l-5.103 3L9 14l-4-4h5l2-5Z"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            />
        </dd>
      </dl>
      <div
        class="mt-4 col-start-1 row-start-3 self-center sm:mt-0 sm:col-start-2 sm:row-start-2 sm:row-span-2 lg:mt-6 lg:col-start-1 lg:row-start-3 lg:row-end-4"
      >
      </div>
      <p
        class="mt-4 text-sm leading-6 col-start-1 sm:col-span-2 lg:mt-6 lg:row-start-4 lg:col-span-1 dark:text-slate-400"
      >
        I am a student at the Politeknik Brunei, majoring in Web Development.
    </p>
    </div>
  </main>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
