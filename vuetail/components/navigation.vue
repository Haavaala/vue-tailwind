<template>
  <nav class="bg-blue-500 py-4">
    <ul class="flex justify-center space-x-16">
      <li>
        <nuxt-link to="/" class="text-white hover:underline">Hjem</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/arnes" class="text-white hover:underline"
          >Årnes</nuxt-link
        >
      </li>
      <li>
        <nuxt-link to="/holmis" class="text-white hover:underline"
          >Holmestrand</nuxt-link
        >
      </li>
      <li>
        <nuxt-link to="/sandnes" class="text-white hover:underline"
          >Sandnes</nuxt-link
        >
      </li>
      <li>
        <nuxt-link to="/stavanger" class="text-white hover:underline"
          >Stavanger</nuxt-link
        >
      </li>
      <li>
        <nuxt-link to="/frekk" class="text-white hover:underline"
          >Fredrikstad</nuxt-link
        >
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

