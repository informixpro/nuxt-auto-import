<template>
  <div class="relative flex items-top justify-center min-h-screen bg-gray-100 sm:items-center sm:pt-0">
    <div class="max-w-4xl mx-auto sm:px-6 lg:px-8">

      <h2 class="text-3xl font-bold mb-6">Nuxt auto import</h2>
      <p class="mb-6">
        In Nuxt 2.13+ we have <a class="underline" href="https://www.npmjs.com/package/@nuxt/components">module</a> to scan and auto import components. It automatically scan components/ directory. No need anymore to manually import components in the script section!
      </p>
      <p class="mb-10">
        We can use the same way for icons. To do this we need to wrap the svg code in a template tag:
      </p>

      <div class="flex my-8 gap-x-8">
        <IconTwitter class="text-blue-500 w-12"/>
        <IconTwitter class="text-green-500 w-12"/>
        <IconTwitter class="text-yellow-500 w-12"/>
      </div>

      <div class="flex my-8 gap-x-8">
        <IconYoutube class="text-red-500 w-4"/>
        <IconYoutube class="text-red-500 w-8"/>
        <IconYoutube class="text-red-500 w-12"/>
      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'NuxtTutorial',
}
</script>
