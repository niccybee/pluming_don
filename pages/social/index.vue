<template>
  <main>
    <section v-if="posts" class="w-full max-w-5xl mx-auto">
      <h1 class="title">I Am The Social Page</h1>
      <posts post-type="projects" :amount="10" />
    </section>
  </main>
</template>

<script>
export default {

}
</script>
