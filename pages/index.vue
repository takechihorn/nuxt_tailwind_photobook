<template>
  <div class="wrapper">
    <div class="card">
      <h1 class="title">
        <span class="text-emerald-800">NUXT</span>JS & TailwindCss v2.0
      </h1>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.wrapper {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
.card {
  @apply p-10 rounded-lg text-emerald-500 bg-emerald-100 shadow-lg;
  .title {
    @apply text-6xl font-bold;
  }
}
</style>
