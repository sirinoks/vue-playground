<template>
  <div class="about">
    <h1>ChildComp</h1>


    <div>
        {{ title }}
    </div>
  </div>
</template>
<script setup lang="ts">
const props = defineProps({
  title: {
    type: String,
    required: true,
  },
  text: {
    type: String,
    required: false,
  }
});

</script>
<style></style>
