<template>
    <nav>
        <RouterLink to="/">Home</RouterLink>
    </nav>

    <RouterView class="grid-container" />
</template>

<script setup>
import { RouterLink, RouterView } from 'vue-router';
</script>

<style lang="scss" scoped>
nav {
    text-align: center;
    margin-top: 1rem;

    a {
        padding: 0 1rem;

        &.router-link-exact-active {
            color: #333;
        }
    }
}
</style>
