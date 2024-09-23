<script setup>
import { ref, inject } from "vue";
import todoService from "@/services/todo";

const $modals = inject("$modals");
const _filter = ref("");
const _item = ref(todoService.getDefault());
const _items = ref([]);
</script>

<template>
  <div></div>
</template>


<style lang="scss" scoped>
</style>