<script setup>

import { PlayIcon } from '@heroicons/vue/24/solid';

</script>

<template>
    <section>
        <div>
            <h1>Easy to setup.</h1>
            <p>Easy to maintain</p>
            <p>Bootstrap is a widely-used, sleek, intuitive and powerful front-end framework for faster and easier web
                development.</p>
        </div>
        <div class="buttons">
            <PlayIcon
                style="width: 25px; background-color: red; padding: 10px; border-radius: 50%; color: white; cursor: pointer;" />
            <button>Get Started</button>
        </div>
    </section>
</template>


<style scoped>
section {
    background-image: url('../images/Background.png');
    background-size: cover;
    background-position: center;
    height: 400px;
}
</style>
