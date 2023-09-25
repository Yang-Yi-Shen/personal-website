<script setup></script>

<template>
    <header>
        <p class="logo heading">&lt;yyshen></p>
        <ul class="header-contacts">
            <li class="header-contacts-item"><a class="header-contacts-link" href="github.com"><i
                        class="header-contacts-icon fa fa-github"></i></a></li>
            <li class="header-contacts-item"><a class="header-contacts-link" href="github.com"><i
                        class="header-contacts-icon fa fa-github"></i></a></li>
            <li class="header-contacts-item"><a class="header-contacts-link" href="github.com"><i
                        class="header-contacts-icon fa fa-github"></i></a></li>
            <li class="header-contacts-item"><a class="header-contacts-link" href="github.com"><i
                        class="header-contacts-icon fa fa-github"></i></a></li>
        </ul>
    </header>
</template>

<style scoped>
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0px 10%;
}

.logo {
    font-size: 24px;
    font-weight: 600;
}

.header-contacts {
    padding-inline-start: 0px;
    list-style: none;
    display: flex;
    gap: 15px;
}

.header-contacts-link {
    text-decoration: none;
    color: white;
}

.header-contacts-icon {
    font-size: 36px;
}</style>