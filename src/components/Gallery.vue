<template>
    <div class="gallery-section">
        <div class="gallery-container d-flex">
            <div class="card">
                <img class="img-fluid" :src="image1" alt="">

            </div>
            <div class="card">
                <img class="img-fluid" :src="image2" alt="">

            </div>
            <div class="card">
                <img class="img-fluid" :src="image3" alt="">

            </div>
            <div class="card">
                <img class="img-fluid" :src="image4" alt="">

            </div>



        </div>
    </div>
</template>

<script setup>
import image1 from '../assets/images/tete1.jpg'
import image2 from '../assets/images/tete2.jpg'
import image3 from '../assets/images/tete3.jpg'
import image4 from '../assets/images/tete4.jpg'


</script>

<style scoped>
.gallery-container {
    width: 100%;
}
</style>