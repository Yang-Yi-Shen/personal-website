<script setup></script>

<template>
    <section id="introduction">
        <img class="intro-image-mobile" src="/saigon.jpg">
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

.intro-image-mobile {
    display: none;
}

@media (max-width: 768px) {
    #introduction {
        height: auto;
        width: 100vw;
        flex-direction: column;
        justify-content: baseline;
        align-items: baseline;
        padding: 50px;
        gap: 0px;
    }

    .intro-title {
        white-space: nowrap;
        width: calc(100vw - 100px);
    }

    .intro-image {
        display: none;
    }

    .intro-image-mobile {
        width: calc(100vw - 100px);
        display: block;
    }
}
</style>