<script setup></script>

<template>
    <section id="description">
        <img class="description-image" src="/selfie.jpeg">
        <div class="description-text">
            <h1 class="heading description-title">Hello there! 👋</h1>
            <p>My name is Yang Yi Shen. I'm 16 years old, homeschooled, and like to learn and create things. While I currently specialize in frontend web development, I plan to progress onto full-stack development in the future.</p>
            <p>When I'm not making websites, I do Brazillian Jiu-Jitsu, play the piano, and read a lot of books. I also do side projects that extend beyond the frontend from time to time.</p>
            <p>I presently reside in the lovely port city of Kaohsiung, Taiwan.</p>
        </div>
    </section>
</template>

<style scoped>
#description {
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 50px;
    background-color: #FAFFFD;
    padding: 0px 15%;
}

.description-text {
    color: black;
}

.description-title {
    font-size: 48px;
    margin-top: 0px;
}

.description-image {
    height: 250px;
    width: 250px;
    object-fit: cover;
}
</style>