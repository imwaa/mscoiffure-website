<template>
    <div class="services-section">
        <div class="service-container container d-flex flex-column">
            <h1 class="text-center">Nos Services</h1>
            <p class="text-center">Notre principale preocupation est de prendre soins de nos clients en leur proposons
                des services variés
                et de qualités. </p>

            <div class="services-list justify-content-between flex-wrap mt-3">

                <div class="card">
                    <img :src="image1" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Coupe de Cheveux</h5>
                        <p class="card-text">Venez donner un style propre et élégant à vos cheveux. Que ça soit une
                            coupe classique ou un dégradé, nous maitrisons les siceaux et la tondeuse.</p>
                    </div>
                </div>

                <div class="card">
                    <img :src="image2" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Coupe Barbe & Rasage</h5>
                        <p class="card-text">Restez à votre meilleur avec une taille de barbe régulière ou un rasage
                            complet de ce dernier. Nous maitrisons la lame à la perfection.</p>
                    </div>
                </div>


                <div class="card">
                    <img :src="image3" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Shampoing & Soins de cheveux</h5>
                        <p class="card-text">Prenez soin de vos cheveux avec nos produits specialement améliorer votre
                            cuire chevelu.</p>
                    </div>
                </div>

                <div class="card">
                    <img :src="image4" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Soins pour le visage & Massages</h5>
                        <p class="card-text">Venez passer un moment de détente dans notre salon. Nous vous proposerons
                            des soins pour le visage ainsi qu'un massage.</p>
                    </div>
                </div>

            </div>

        </div>
    </div>
</template>


<style scoped>
.services-section {
    margin: 120px 0px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.services-list {
    display: flex;
    gap: 15px;
}

.card {
    width: 18rem;
}

@media only screen and (max-width: 767px) {
    .card {
        width: 100%;
    }
}
</style>

<script setup>
import image1 from '../../public/images/pexels-photo-12464840.jpeg'
import image2 from '../../public/images/pexels-mídia-897251.jpg'
import image3 from '../../public/images/arkadiy barbershop shampoo.png'
import image4 from '../../public/images/The-best-essential-facial-services-for-men-Best-Barbershop.jpg'

</script>