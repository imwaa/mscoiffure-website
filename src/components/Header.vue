<template>
    <div class="header-container">
        <!-- NAVBAR -->
        <nav class="navbar navbar-dark navbar-expand-lg">
            <div class="container">
                <a class="navbar-brand text-light" href="#">MS COIFFURE</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                    data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
                    aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse justify-content-end" id="navbarSupportedContent">
                    <div class="" role="search">
                        <button class="btn btn-sm btn-outline-light mx-3" type="submit">Instagram</button>
                        <button class="btn btn-sm btn-outline-danger" type="submit">Tiktok</button>
                    </div>
                </div>
            </div>
        </nav>

        <div class="header-content">
            <img src="../assets/logo.png">
            <div>
                <button class="btn btn-lg btn-outline-light" type="submit">Prendre
                    un rendez-vous</button>
            </div>
        </div>
    </div>
</template>

<style scoped>
.header-container {
    background-image: url("../assets/images/allef-vinicius-IvQeAVeJULw-unsplash.jpg");
    height: 100vh;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

.header-content {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}
</style>