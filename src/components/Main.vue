<script>
import { ref } from 'vue'

export default {
    props: {
        cards: Array
    }
}
</script>

<template>
    <main class="container">
        <ul>
            <li>
                <App v-for="(card, index) in cards" :key="index" :details="card" />
            </li>
        </ul>
    </main>

</template>

<style lang="scss" scoped>
main {
    padding-top: 50px;
    padding-bottom: 50px;
    color: white;
    background-color: black;
}
</style>
