<template>
    <div>
    <p class="red">Vue says: {{msg}}</p>
    </div>
</template>

<script setup>
    defineProps({
        msg: String
    })
</script>

<style lang="scss" scoped>
    p.red {
        color: red;
    }
</style>
