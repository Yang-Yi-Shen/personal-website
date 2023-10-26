<script setup></script>

<template>
    <section id="projects">
        <h1 class="heading projects-title">My Projects</h1>
        <p class="projects-subtitle">Check out some of the work I've done!</p>
        <div class="projects-gallery">
            <div class="project">
                <a class="project-image-link" href="https://patroklos.yyshen.com" target="_blank">
                    <img src="/patroklos.png" class="project-image">
                </a>
                <div class="project-content">
                    <h2 class="heading project-name">Patroklos</h2>
                    <p class="project-description">A webpage for an imaginary Greek restaurant</p>
                    <div class="project-links">
                        <a class="project-link" href="https://patroklos.yyshen.com" target="_blank"><i class="project-link-icon fa-solid fa-globe"></i></a>
                        <a class="project-link" href="https://github.com/yang-yi-shen/patroklos" target="_blank"><i class="project-link-icon fa fa-github"></i></a>
                    </div>
                </div>
            </div>
            <div class="project">
                <a class="project-image-link" href="https://muguo.yyshen.com" target="_blank">
                    <img src="/muguo.png" class="project-image">
                </a>
                <div class="project-content">
                    <h2 class="heading project-name">Muguo</h2>
                    <p class="project-description">The website for my cousin's moon cake business</p>
                    <div class="project-links">
                        <a class="project-link" href="https://muguo.yyshen.com" target="_blank"><i class="project-link-icon fa-solid fa-globe"></i></a>
                        <a class="project-link" href="https://github.com/yang-yi-shen/muguo" target="_blank"><i class="project-link-icon fa fa-github"></i></a>
                    </div>
                </div>
            </div>
            <div class="project">
                <a class="project-image-link" href="https://book-browser.yyshen.com" target="_blank">
                    <img src="/book-browser.png" class="project-image">
                </a>
                <div class="project-content">
                    <h2 class="heading project-name">Book Browser</h2>
                    <p class="project-description">A tool that helps you find great book deals</p>
                    <div class="project-links">
                        <a class="project-link" href="https://book-browser.yyshen.com" target="_blank"><i class="project-link-icon fa-solid fa-globe"></i></a>
                        <a class="project-link" href="https://github.com/yang-yi-shen/book-browser" target="_blank"><i class="project-link-icon fa fa-github"></i></a>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
#projects {
    background-color: #CAD8DE;
    color: black;
    padding: 50px 250px 100px;
}

.projects-title {
    font-size: 48px;
    margin: 0px;
    color: black;
}

.projects-gallery {
    display: flex;
    gap: 30px;
    margin-top: 40px;
}

.project {
    background-color: #FAFFFD;
    flex: 1;
    transition: 0.1s all ease-in-out;
}

.project:hover {
    transform: scale(1.03);
}

.project-image {
    width: 100%;
}

.project-content {
    padding: 0px 20px 30px;
}

.project-links {
    display: flex;
    gap: 10px;
}

.project-link {
    text-decoration: none;
    color: #FA824C;
    font-size: 18px;
}

.project-link:hover {
    color: #c6673c;
}

@media (max-width: 768px) {
    #projects {
        padding: 50px;
    }

    .projects-title {
        font-size: 32px;
    }

    .projects-gallery {
        flex-direction: column;
    }

    .project {
        display: flex;
        flex-direction: column;
    }
}
</style>