<template>Hello {{ counter }}!


    <div class="text-dark-800 mt-20">hello</div>
</template>

<script setup>
import { ref } from "vue";
const counter = ref(0);
setInterval(() => counter.value++, 1000);
</script>
