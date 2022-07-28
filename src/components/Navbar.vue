<template>
    <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container">
            <a href="/home" class="navbar-brand text-uppercase" style="color: rgb(204, 214, 246); font-size: 20px" >Khairat</a>
            <button aria-controls="responsive-navbar-nav" type="button" aria-label="Toggle navigation" class="navbar-toggler collapsed" > <span class="navbar-toggler-icon"></span> </button>

            <div class="justify-content-end text-light navbar-collapse collapse" >
                <ul class="navbar-nav">
                    <ul class="nav-item">
                        <a class="nav-link" href="/home" style="color: rgb(204, 214, 246); font-size: 20px">  Home</a></ul>
                    <ul class="nav-item">
                        <a class="nav-link" href="/home#about" style="color: rgb(204, 214, 246); font-size: 20px">About</a>
                    </ul>
                    <ul class="nav-item">
                        <a class="nav-link" href="/allProjects" style="color: rgb(204, 214, 246); font-size: 20px" > Projects</a>
                    </ul>
                    <ul class="nav-item">
                        <a class="nav-link" href="/home#blogs" style="color: rgb(204, 214, 246); font-size: 20px">Blogs</a>
                    </ul>
                    <ul class="nav-item">
                        <a class="nav-link" href="/home#contact" style="color: rgb(204, 214, 246); font-size: 20px">Contact</a>
                    </ul>
                    <ul class="nav-item">
                        <a target="_blank" rel="noreferrer" href="https://drive.google.com/file/d/1KR3w87f6pvvwsPcxPDCNnvK-fi0qveBX/view?usp=sharing"><button type="button" class="btn btn-outline-success" style="font-size: 20px">Resume</button> </a>
                    </ul>
                </ul>
            </div>
        </div>
    </nav>
</template>

<script>
export default {
    name: "Navbar",
};
</script>

<style scoped>
</style>