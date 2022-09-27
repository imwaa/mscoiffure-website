<template>
    <div class="infos-section">
        <h1 class="text-center">Informations pratiques</h1>
        <p class="text-center">
            Vous trouverez ci-dessous des informations essentiels concernant notre salon de coiffure MS Coiffure.
        </p>
        <div class="infos-container">
            <div class="horaire-container">
                <h2 class="text-secondary">Horaires d'ouvertures</h2>
                <ul class="list-group mt-4">
                    <li class="list-group-item d-flex fs-5 justify-content-between align-items-center">
                        Lundi
                        <span class="badge bg-danger rounded-pill">Fermé</span>
                    </li>
                    <li class="list-group-item d-flex fs-5 justify-content-between align-items-center">
                        Mardi
                        <span class="badge bg-primary rounded-pill">9h - 19h</span>
                    </li>
                    <li class="list-group-item d-flex fs-5 justify-content-between align-items-center">
                        Mercredi
                        <span class="badge bg-primary rounded-pill">9h - 19h</span>
                    </li>
                    <li class="list-group-item d-flex fs-5 justify-content-between align-items-center">
                        Jeudi
                        <span class="badge bg-primary rounded-pill">9h - 19h</span>
                    </li>
                    <li class="list-group-item d-flex fs-5 justify-content-between align-items-center">
                        Vendredi
                        <span class="badge bg-primary rounded-pill">9h - 19h</span>
                    </li>
                    <li class="list-group-item d-flex fs-5 justify-content-between align-items-center">
                        Samedi
                        <span class="badge bg-primary rounded-pill">9h - 19h</span>
                    </li>
                    <li class="list-group-item d-flex fs-5 justify-content-between align-items-center">
                        Dimanche
                        <span class="badge bg-primary rounded-pill">9h - 19h</span>
                    </li>
                </ul>
            </div>
            <div class="tarif-container">
                <h2 class="text-secondary">Nos tarifs</h2>
                <ul class="list-group mt-4">
                    <li class="list-group-item d-flex fs-5 justify-content-between align-items-center">
                        Coupe de cheveux adultes
                        <span class="badge bg-primary rounded-pill">12€</span>
                    </li>
                    <li class="list-group-item d-flex fs-5 justify-content-between align-items-center">
                        Coupe de cheveux enfants
                        <span class="badge bg-primary rounded-pill">10€</span>
                    </li>
                    <li class="list-group-item d-flex fs-5 justify-content-between align-items-center">
                        Barbe & Rasage
                        <span class="badge bg-primary rounded-pill">8€</span>
                    </li>
                    <li class="list-group-item d-flex fs-5 justify-content-between align-items-center">
                        Lissage & défrisage
                        <span class="badge bg-primary rounded-pill">15€</span>
                    </li>
                    <li class="list-group-item d-flex fs-5 justify-content-between align-items-center">
                        Coloration & décoloration
                        <span class="badge bg-primary rounded-pill">20€</span>
                    </li>
                    <li class="list-group-item d-flex fs-5 justify-content-between align-items-center">
                        Soins botox
                        <span class="badge bg-primary rounded-pill">20€</span>
                    </li>
                    <li class="list-group-item d-flex fs-5 justify-content-between align-items-center">
                        Permanente
                        <span class="badge bg-primary rounded-pill">18€</span>
                    </li>
                    <li class="list-group-item d-flex fs-5 justify-content-between align-items-center">
                        Soins visages & massages
                        <span class="badge bg-primary rounded-pill">10€</span>
                    </li>
                    <li class="list-group-item d-flex fs-5 justify-content-between align-items-center">
                        Epilation au fil & cire
                        <span class="badge bg-primary rounded-pill">5€</span>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<style scoped>
.infos-section {
    margin: 120px 0px;
    display: flex;
    flex-direction: column;
}

.infos-container {
    margin-top: 70px;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 100px;
}

.horaire-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 450px;

}

.tarif-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 450px;
}

.list-group {
    width: 100%;
}
</style>