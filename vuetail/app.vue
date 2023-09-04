<template>
  <div>
    <Navbar />
    <NuxtLayout>
    <NuxtPage></NuxtPage>
    </NuxtLayout>

  </div>
</template>

<script>
import Navbar from '@/components/navigation.vue'


export default {
  components: {
    Navbar
  }
};
</script>