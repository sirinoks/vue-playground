<template>
  <div>
    ParentComp

    <ChildComp :title="'aa'"></ChildComp>
  </div>
</template>
<script setup lang="ts">
import ChildComp from "./ChildComp.vue";
</script>
<style></style>
