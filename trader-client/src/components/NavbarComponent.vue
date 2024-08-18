<script setup>

import { RouterLink } from 'vue-router'

</script>

<template>
    <div class="navbar">
        <nav>
            <RouterLink class="nav-items" to="/">Home</RouterLink>
            <RouterLink class="nav-items" to="/about">About</RouterLink>
        </nav>
    </div>
</template>