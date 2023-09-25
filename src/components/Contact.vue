<script setup></script>

<template>
    <section id="contacts">
        <h1 class="heading contacts-title">Let's get in touch!</h1>
        <ul class="contacts-list">
            <li class="contacts-item">
                <a class="contacts-link" href="github.com"><i class="fa fa-github contacts-icon"></i></a>
                <p class="contacts-label">Github</p>
                <p class="contacts-text">I'm very active on Github, and you can find my coolest projects there</p>
            </li>
            <li class="contacts-item">
                <a class="contacts-link" href="github.com"><i class="fa fa-github contacts-icon"></i></a>
                <p class="contacts-label">Github</p>
                <p class="contacts-text">I'm very active on Github, and you can find my coolest projects there</p>
            </li>
            <li class="contacts-item">
                <a class="contacts-link" href="github.com"><i class="fa fa-github contacts-icon"></i></a>
                <p class="contacts-label">Github</p>
                <p class="contacts-text">I'm very active on Github, and you can find my coolest projects there</p>
            </li>
            <li class="contacts-item">
                <a class="contacts-link" href="github.com"><i class="fa fa-github contacts-icon"></i></a>
                <p class="contacts-label">Github</p>
                <p class="contacts-text">I'm very active on Github, and you can find my coolest projects there</p>
            </li>
        </ul>
    </section>
</template>

<style scoped>
#contacts {
    padding: 40px 0px 100px;
}

.contacts-title {
    text-align: center;
    padding: 0px 0px 40px;
}

.contacts-list {
    list-style: none;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 40px;
    padding-inline-start: 0px;
}

.contacts-item {
    display: flex;
    flex-direction: column;
    align-items: center;
    max-width: 200px;
    background: #FAFFFD;
    padding: 20px;
}

.contacts-link {
    text-decoration: none;
    color: black;
    display: flex;
}

.contacts-icon {
    font-size: 72px;
}

.contacts-label {
    font-weight: 600;
    color: black;
}

.contacts-text {
    color: black;
}
</style>