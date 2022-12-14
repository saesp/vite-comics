<script>
import { ref } from 'vue'

export default {
    name: "Card",
    props: {
        thumb: String,
        price: String,
        series: String,
        type: String
    }
}

</script>

<template>
    <li class="card">
        <img :src="thumb" alt="">
        <h3>{{ series }}</h3>
    </li>
</template>

<style lang="scss" scoped>
.card {
    width: calc(100%/6 - 20px);
    margin-bottom: 40px;
    list-style-type: none;

    img {
        width: 100%;
        height: 200px;
    }
}
</style>