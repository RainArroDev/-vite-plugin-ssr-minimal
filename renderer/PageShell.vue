<template>
  <div class="layout">
    <div class="content"><slot /></div>
  </div>
</template>

<script lang="ts" setup>
import Link from "./Link.vue";
</script>

<style>
.layout {
  width: 1000px;
  margin: auto;
}
</style>
