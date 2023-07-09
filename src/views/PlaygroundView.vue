<template>
  <div class="about">
    <h1>Playground</h1>
    <div>Count is: {{ count }}</div>
    <div v-bind="attrs">Binding</div>

    <div></div>
  </div>
</template>
<script lang="ts">
export default {
  data() {
    return {
      attrs: {
        id: "container",
        class: "wrapper",
      },
      count: 1,
    };
  },

  mounted() {
    console.log(this.count);
    this.count = 2;
  },
};
</script>
<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
