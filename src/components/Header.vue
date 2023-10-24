<script setup>
function discord() {
    navigator.clipboard.writeText('yangyishen')

    alert("Discord ID copied! (yangyishen)")
}
</script>

<template>
    <header>
        <p class="logo heading">&lt;yyshen></p>
        <ul class="header-contacts">
            <li class="header-contacts-item"><a class="header-contacts-link" target="_blank"
                    href="https://github.com/yang-yi-shen"><i class="header-contacts-icon fa fa-github"></i></a></li>
            <li class="header-contacts-item"><a class="header-contacts-link" @click="discord()"><i
                        class="header-contacts-icon fa-brands fa-discord"></i></a></li>
            <li class="header-contacts-item"><a class="header-contacts-link" target="_blank"
                    href="https://www.linkedin.com/in/yang-yi-shen-1b3226220/"><i class="header-contacts-icon fa-brands fa-linkedin"></i></a></li>
            <li class="header-contacts-item"><a class="header-contacts-link" href="mailto:mrshenyangyi@gmail.com"><i
                        class="header-contacts-icon fa fa-envelope"></i></a></li>
        </ul>
    </header>
</template>

<style scoped>
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0px 10%;
    border-bottom: 2px solid #FAFFFD;
}

.logo {
    font-size: 24px;
    font-weight: 600;
}

.header-contacts {
    padding-inline-start: 0px;
    list-style: none;
    display: flex;
    gap: 30px;
}

.header-contacts-link {
    text-decoration: none;
    color: white;
}

.header-contacts-icon {
    font-size: 24px;
}

.header-contacts-icon:hover {
    color: #e0e0e0;
}

@media (max-width: 480px) {
    header {
        padding: 0px 7%;
    }

    .header-contacts {
        gap: 20px;
    }
}
</style>