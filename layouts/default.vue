<template>
  <div>
    <nav>
      <NuxtLink to="/">Home</NuxtLink>
      <NuxtLink to="/about">About</NuxtLink>
    </nav>
    <Nuxt />
  </div>
</template>
<script>
export default {
  head: {
    title: 'Nuxt Mission',
  },
}
</script>
