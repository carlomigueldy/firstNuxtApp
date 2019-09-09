<template>
  <div class="flex flex-col min-h-screen mx-auto text-center justify-center items-center">
    <div class="font-mono text-white">
      <div class="card p-10 bg-green-500 border-blue-800
      border-2 rounded mb-3">
          <p class="text-6xl">Hello Nuxtjs</p>
          <p>I love TailwindCSS</p>
          <a href="/users" class="no-underline hover:underline text-blue-500 text-lg">Go to Users</a>
      </div>
      <div class="card p-10 bg-gray-800 border-2
      border-green-500 rounded">
        <p>I really think that Nuxtjs and TailwindCSS is just really amazing!</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
</style>
