<template>
    <p>Hello World</p>
    {{ data }}
    <input type="text" v-model="text" />
    <p>{{ text }}</p>
</template>

<script setup>
import { ref } from "@vue/reactivity";

const data = "Hello Vue";
const text = ref("123");
</script>

<style></style>
