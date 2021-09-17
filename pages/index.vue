<template>
  <main>
    <section class="flex flex-col items-start self-start justify-center flex-1">
      <h1 class="text-left text-7xl ">The Plumbing Don</h1>
      <h2 class="text-4xl font-thin text-left uppercase">Melbourne Plumber</h2>
    </section>

    <section class="mt-8">
      <h3 class="max-w-5xl mx-auto text-primary-600 dark:text-primary-400">Latest blog post</h3>
      <posts post-type="blog" :amount="1" />
    </section>
  </main>
</template>
<style scoped>

</style>