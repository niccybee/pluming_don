<template>
  <div class="wrapper bg-img">
    <Header />
    <nuxt />
    <ColorModePicker />
  </div>
</template>
<style scoped>
.bg-img {
  background-image: url('http://picsum.photos/1200/1500');
  background-size: cover;
}
</style>