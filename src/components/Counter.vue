<script>

    export default {
        data() {
            return {
                count: 0
            }
        },
        methods: {
            increment() {
                this.count++
            },
            decrement() {
                this.count--
            }
        }
    }
</script>

<template>
    <div>
        <h1>{{ count }}</h1>
        <button v-on:click="increment">+</button>
        <button v-on:click="decrement">-</button>
    </div>
</template>