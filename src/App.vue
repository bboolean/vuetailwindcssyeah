<template>
  <div class="m-10">
    <h1 class="text-4xl font-bold mb-5">What is this?</h1>

    <div class="my-5">Hello {{ name }}!</div>

    <button class="button bg-sky-500">12</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'Vue',
    };
  },
};
</script>
