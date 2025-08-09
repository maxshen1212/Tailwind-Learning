<template>
  <div class="text-gray-600">
    <header class="mb-5">
      <div class="bg-gray-700 p-4 text-white">Hello Tailwind CSS.</div>
    </header>
    <main class="container mx-auto">
      <h1 class="text-2xl">Max learn Tailwind CSS</h1>
      <!-- 程式碼區 Start -->
      <ul>
        <li v-for="fontsize in list">
          <div :class="fontsize">Tailwind CSS</div>
        </li>
      </ul>
      <!-- 程式碼區 End -->
    </main>
    <footer class="mt-5">
      <div class="bg-gray-300 p-4 text-black">Goodbye Tailwind CSS.</div>
    </footer>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      list: [
        "text-xs",
        "text-sm",
        "text-base",
        "text-lg",
        "text-xl",
        "text-2xl",
        "text-3xl",
        "text-4xl",
        "text-5xl",
        "text-6xl",
        "text-7xl",
        "text-8xl",
        "text-9xl",
      ],
    };
  },
};
</script>
