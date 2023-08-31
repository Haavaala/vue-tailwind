<template>
  <nav class="bg-blue-500 py-4">
    <ul class="flex justify-center space-x-16">
      <li>
        <nuxt-link to="/" class="text-white hover:underline">Halla</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/wallah" class="text-white hover:underline">Wallah</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/inshallah" class="text-white hover:underline">Inshallah</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/bro" class="text-white hover:underline">Bro</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/wakkaflow" class="text-white hover:underline">Wakkaflow</nuxt-link>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: 'Navbar'
};
</script>

