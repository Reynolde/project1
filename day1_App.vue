<script setup>
import { ref } from "vue";

const soLuong = ref(11);
const Price = ref(12344)
const name = ref("ghahahahah")

</script>
<template>
    <div>
        <h1>{{ soLuong }}</h1>
        <h1>{{ name }}</h1>
        <h1>{{ Price }}</h1>
    </div>
</template>