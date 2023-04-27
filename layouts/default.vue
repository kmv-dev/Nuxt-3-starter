<template>
  <div class="primary flex flex-col justify-between bg-gray-900 text-white">
    <TheHeader />
    <NuxtPage class="primary__content grow" />
    <TheFooter />
  </div>
</template>

<style lang="scss">
.primary {
  min-height: 100vh;
}
</style>
