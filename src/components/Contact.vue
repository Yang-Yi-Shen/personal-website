<script setup>
function discord() {
    navigator.clipboard.writeText('yangyishen')

    alert("Discord ID copied! (yangyishen)")
}
</script>

<template>
    <section id="contacts">
        <h1 class="heading contacts-title">Let's get in touch!</h1>
        <ul class="contacts-list">
            <li class="contacts-item">
                <a class="contacts-link" href="https://github.com/yang-yi-shen" target="_blank"><i class="fa fa-github contacts-icon"></i></a>
                <p class="contacts-label">Github</p>
                <p class="contacts-text">I'm very active on Github, and you can find my coolest projects there</p>
            </li>
            <li class="contacts-item">
                <a class="contacts-link" @click="discord"><i class="fa-brands fa-discord contacts-icon"></i></a>
                <p class="contacts-label">Discord</p>
                <p class="contacts-text">Feel free to message me, although I might take a while to answer</p>
            </li>
            <li class="contacts-item">
                <a class="contacts-link" href="https://www.linkedin.com/in/yang-yi-shen-1b3226220/" target="_blank"><i class="fa-brands fa-linkedin contacts-icon"></i></a>
                <p class="contacts-label">LinkedIn</p>
                <p class="contacts-text">I'm not an avid LinkedIn user, but you can check out my certifications here</p>
            </li>
            <li class="contacts-item">
                <a class="contacts-link" href="mailto:mrshenyangyi@gmail.com"><i class="fa fa-envelope contacts-icon"></i></a>
                <p class="contacts-label">Email</p>
                <p class="contacts-text">Send me an email anytime, I'll be sure to see it within 3 business days</p>
            </li>
        </ul>
    </section>
</template>

<style scoped>
#contacts {
    padding: 50px 20% 200px;
}

.contacts-title {
    font-size: 48px;
    text-align: center;
    padding: 0px 0px 40px;
}

.contacts-list {
    list-style: none;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 25px;
    padding-inline-start: 0px;
}

.contacts-item {
    height: 230px;
    width: 180px;
    flex-shrink: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    background: #FAFFFD;
    padding: 35px 20px 0px;
    transition: 0.1s all ease-in-out;
}

.contacts-item:hover {
    transform: scale(1.05);
}

.contacts-link {
    text-decoration: none;
    color: black;
    display: flex;
}

.contacts-icon {
    font-size: 48px;
}

.contacts-label {
    font-weight: 600;
    color: black;
}

.contacts-text {
    color: black;
}

@media (max-width: 768px) {
    #contacts {
        padding: 40px 0px;
    }

    .contacts-title {
        margin: 0px;
        padding-bottom: 20px;
        font-size: 32px;
    }

    .contacts-list {
        flex-direction: column;
        padding: 0px 50px;
    }

    .contacts-item {
        width: auto;
        height: 120px;
        padding: 0px;
        padding-right: 20px;
        align-items: center;
        justify-content: baseline;
        flex-direction: row;
    }

    .contacts-icon {
        width: 100px;
        display: flex;
        justify-content: center;
    }

    .contacts-label {
        display: none;
    }
}
</style>