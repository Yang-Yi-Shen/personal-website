<script setup></script>

<template>
    <section id="introduction">
        <div class="intro-text">
            <h1 class="heading intro-title">Yang Yi Shen</h1>
            <p class="intro-subtitle">A Taiwanese frontend web developer</p>
        </div>
        <img class="intro-image" src="/saigon.jpg">
    </section>
</template>

<style scoped>
#introduction {
    height: calc(100vh - 80px);
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 50px;
}

.intro-text {
    width: 300px;
}

.intro-title {
    font-size: 48px;
}

.intro-subtitle {
    font-size: 20px;
}

.intro-image {
    height: 432px;
    width: 300px;
    object-fit: cover;
}
</style>