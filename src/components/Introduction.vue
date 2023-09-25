<script setup></script>

<template>
    <section id="introduction">
        <div class="intro-text">
            <h1 class="heading">Yang Yi Shen</h1>
            <p>Frontend web developer</p>
        </div>
        <img class="intro-image" src="/src/assets/blank.jpg">
    </section>
</template>

<style scoped>
#introduction {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 50px;
    padding: 40px 0px 100px;
}

.intro-image {
    height: 450px;
    width: 278px;
    object-fit: cover;
}
</style>