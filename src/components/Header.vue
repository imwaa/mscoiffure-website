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
                        <button class="btn btn-light" type="submit">Reserver</button>
                    </div>
                </div>
            </div>
        </nav>

        <div class="header-content">
            <img src="../assets/logo.png">
            <div>
                <button class="btn btn-lg btn-light" type="submit">Prendre un rendez-vous</button>
            </div>
        </div>
    </div>
</template>

<style scoped>
.header-container {
    background-image: url("../assets/pexels-nikolaos-dimou-1319459.jpg");
    height: 100vh;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

.header-content {
    margin-top: 100px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}
</style>