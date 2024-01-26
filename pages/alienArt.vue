<template>
    <div class="gallery-container" id="gallery-container">
        <!-- Image Gallery -->
        <div class="gallery">
            <a href="#" @click="openImage('/images/Leonardo_Diffusion_XL_Visualize_a_serene_alien_creature_its_bo_3.jpg')">
                <img src="/images/Leonardo_Diffusion_XL_Visualize_a_serene_alien_creature_its_bo_3.jpg" alt="Artwork 1">
            </a>
            <a href="#" @click="openImage('/images/Leonardo_Diffusion_XL_Visualize_a_serene_alien_creature_its_bo_2.jpg')">
                <img src="/images/Leonardo_Diffusion_XL_Visualize_a_serene_alien_creature_its_bo_2.jpg" alt="Artwork 2">
            </a>
            <a href="#" @click="openImage('/images/Leonardo_Diffusion_XL_Visualize_a_serene_alien_creature_its_bo_1.jpg')">
                <img src="/images/Leonardo_Diffusion_XL_Visualize_a_serene_alien_creature_its_bo_1.jpg" alt="Artwork 3">
            </a>
            <a href="#" @click="openImage('/images/Leonardo_Diffusion_XL_Visualize_a_serene_alien_creature_its_bo_0.jpg')">
                <img src="/images/Leonardo_Diffusion_XL_Visualize_a_serene_alien_creature_its_bo_0.jpg" alt="Artwork 4">
            </a>
            <a href="#" @click="openImage('/images/Leonardo_Diffusion_XL_Picture_a_tranquil_and_otherworldly_crea_3.jpg')">
                <img src="/images/Leonardo_Diffusion_XL_Picture_a_tranquil_and_otherworldly_crea_3.jpg" alt="Artwork 18">
            </a>
            <a href="#" @click="openImage('/images/Leonardo_Diffusion_XL_Picture_a_tranquil_and_otherworldly_crea_2.jpg')">
                <img src="/images/Leonardo_Diffusion_XL_Picture_a_tranquil_and_otherworldly_crea_2.jpg" alt="Artwork 19">
            </a>
            <a href="#" @click="openImage('/images/Leonardo_Diffusion_XL_Picture_a_tranquil_and_otherworldly_crea_1.jpg')">
                <img src="/images/Leonardo_Diffusion_XL_Picture_a_tranquil_and_otherworldly_crea_1.jpg" alt="Artwork 20">
            </a>
            <a href="#" @click="openImage('/images/Leonardo_Diffusion_XL_Picture_a_tranquil_and_otherworldly_crea_0.jpg')">
                <img src="/images/Leonardo_Diffusion_XL_Picture_a_tranquil_and_otherworldly_crea_0.jpg" alt="Artwork 21">
            </a>
            <a href="#" @click="openImage('/images/Leonardo_Diffusion_XL_Imagine_a_tranquil_extraterrestrial_bein_3.jpg')">
                <img src="/images/Leonardo_Diffusion_XL_Imagine_a_tranquil_extraterrestrial_bein_3.jpg" alt="Artwork 22">
            </a>
            <a href="#" @click="openImage('/images/Leonardo_Diffusion_XL_Imagine_a_tranquil_extraterrestrial_bein_3 (1).jpg')">
                <img src="/images/Leonardo_Diffusion_XL_Imagine_a_tranquil_extraterrestrial_bein_3 (1).jpg" alt="Artwork 23">
            </a>
            <a href="#" @click="openImage('/images/Leonardo_Diffusion_XL_Imagine_a_tranquil_extraterrestrial_bein_2.jpg')">
                <img src="/images/Leonardo_Diffusion_XL_Imagine_a_tranquil_extraterrestrial_bein_2.jpg" alt="Artwork 24">
            </a>
            <a href="#" @click="openImage('/images/Leonardo_Diffusion_XL_Imagine_a_tranquil_extraterrestrial_bein_2 (2).jpg')">
                <img src="/images/Leonardo_Diffusion_XL_Imagine_a_tranquil_extraterrestrial_bein_2 (2).jpg" alt="Artwork 25">
            </a>
            <a href="#" @click="openImage('/images/Leonardo_Diffusion_XL_Imagine_a_tranquil_extraterrestrial_bein_1.jpg')">
                <img src="/images/Leonardo_Diffusion_XL_Imagine_a_tranquil_extraterrestrial_bein_1.jpg" alt="Artwork 26">
            </a>
            <a href="#" @click="openImage('/images/Leonardo_Diffusion_XL_Imagine_a_tranquil_extraterrestrial_bein_1 (3).jpg')">
                <img src="/images/Leonardo_Diffusion_XL_Imagine_a_tranquil_extraterrestrial_bein_1 (3).jpg" alt="Artwork 27">
            </a>
            <a href="#" @click="openImage('/images/Leonardo_Diffusion_XL_Imagine_a_tranquil_extraterrestrial_bein_1 (2).jpg')">
                <img src="/images/Leonardo_Diffusion_XL_Imagine_a_tranquil_extraterrestrial_bein_1 (2).jpg" alt="Artwork 28">
            </a>
            <a href="#" @click="openImage('/images/Leonardo_Diffusion_XL_Imagine_a_tranquil_extraterrestrial_bein_1 (1).jpg')">
                <img src="/images/Leonardo_Diffusion_XL_Imagine_a_tranquil_extraterrestrial_bein_1 (1).jpg" alt="Artwork 29">
            </a>
            <a href="#" @click="openImage('/images/Leonardo_Diffusion_XL_Imagine_a_tranquil_extraterrestrial_bein_0.jpg')">
                <img src="/images/Leonardo_Diffusion_XL_Imagine_a_tranquil_extraterrestrial_bein_0.jpg" alt="Artwork 30">
            </a>
            <a href="#" @click="openImage('/images/Leonardo_Diffusion_XL_Imagine_a_tranquil_extraterrestrial_bein_0 (1).jpg')">
                <img src="/images/Leonardo_Diffusion_XL_Imagine_a_tranquil_extraterrestrial_bein_0 (1).jpg" alt="Artwork 31">
            </a>
            <!-- Image Gallery (Continued) -->
            <a href="#" @click="openImage('/images/Leonardo_Diffusion_XL_Envision_a_peaceful_and_ethereal_alien_b_3.jpg')">
                <img src="/images/Leonardo_Diffusion_XL_Envision_a_peaceful_and_ethereal_alien_b_3.jpg" alt="Artwork 36">
            </a>
            <a href="#" @click="openImage('/images/Leonardo_Diffusion_XL_Envision_a_peaceful_and_ethereal_alien_b_2.jpg')">
                <img src="/images/Leonardo_Diffusion_XL_Envision_a_peaceful_and_ethereal_alien_b_2.jpg" alt="Artwork 37">
            </a>
            <a href="#" @click="openImage('/images/Leonardo_Diffusion_XL_Envision_a_peaceful_and_ethereal_alien_b_1.jpg')">
                <img src="/images/Leonardo_Diffusion_XL_Envision_a_peaceful_and_ethereal_alien_b_1.jpg" alt="Artwork 38">
            </a>
            <a href="#" @click="openImage('/images/Leonardo_Diffusion_XL_Envision_a_peaceful_and_ethereal_alien_b_0.jpg')">
                <img src="/images/Leonardo_Diffusion_XL_Envision_a_peaceful_and_ethereal_alien_b_0.jpg" alt="Artwork 39">
            </a>

        </div>
    </div>
</template>

<script setup>
import { onMounted } from 'vue';

    // these are called arrow functions and they only LOOK scary.
    // They are a JS feature not a Vue feature.
    const openImage = (imagePath) => {
        // There is a way to do this using NuxtLink instead of <a>
        window.open(imagePath, '_blank');
    }

    // Function to check if the gallery container is in the viewport
    const isInViewport = (element) => {
        const rect = element.getBoundingClientRect();
        return (
            rect.top >= 0 &&
            rect.left >= 0 &&
            rect.bottom <= (window.innerHeight || document.documentElement.clientHeight) &&
            rect.right <= (window.innerWidth || document.documentElement.clientWidth)
        );
    }

    // Function to handle scroll events
    const handleScroll = () => {
        const galleryContainer = document.getElementById('gallery-container');

        if (isInViewport(galleryContainer)) {
            // Show the gallery when it's in the viewport
            galleryContainer.style.opacity = 1;
        }
    }

    // Because Nuxt is Server Side Rendered, we need to wait for the page to load
    // before referencing anything in the document or window objects.
    onMounted(() => {
        // Attach the scroll event listener
        window.addEventListener('scroll', handleScroll);
        // Initial check for visibility on page load
        handleScroll();
    });


    

</script>


<style scoped>
/* This special "scoped" attribute ensures that this CSS applies only to this page or component.
I would reccomend setting the background image of index.vue in a similar fasion,
because currently it's set globally. */
    body {
        background-image: url('/images/Leonardo_Diffusion_XL_Imagine_a_tranquil_extraterrestrial_bein_0 (1).jpg');
    }

    .gallery-container {
            opacity: 1; /* Initially hide the gallery */
            transition: opacity 0.5s ease-in-out; /* Smooth transition effect */
        }

        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 20px;
        }

        .gallery img {
            width: 300px;
            height: auto;
            margin: 10px;
            border: 2px solid #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
</style>