<script setup></script>

<template>
    <section id="description">
        <div class="description-text">
            <h1 class="heading">Hello there!</h1>
            <p>My name is Yang Yi Shen, and I like to learn and create things. I'm 16 years old and hoomeschooled. I am currently specialized in frontend web development, but plan to progress onto full-stack development in the future.</p>
            <p>When I'm not making websites, I like to practice Brazillian Jiu-Jitsu, play the piano, and read a lot of books. I also do side projects that extend beyond the frontend from time to time.</p>
            <p>As of now I reside in the lovely port city of Kaohsiung, Taiwan, although I plan to go to ollege in America.</p>
        </div>
        <img class="description-image" src="/src/assets/blank_black.jpg">
    </section>
</template>

<style scoped>
#description {
    display: flex;
    align-content: start;
    justify-content: center;
    gap: 50px;
    padding: 100px 10%;
    background-color: #FAFFFD;
}

.description-text {
    color: black;
}

.description-image {
    height: 350px;
    width: 350px;
    object-fit: cover;
}
</style>