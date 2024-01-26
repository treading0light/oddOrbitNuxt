<template>
  <div class="container">

    <nav class="sidebar">
      <h1>warpTunnel</h1>
      <ul>
          <li><NuxtLink  to="/">Home</NuxtLink></li>
          <li><NuxtLink  to="#about">About</NuxtLink></li>
          <li><NuxtLink  to="#applications">Applications</NuxtLink></li>
          <li><NuxtLink  to="#contact">Contact</NuxtLink></li>
          <li><NuxtLink  to="/alienArt">alienArt</NuxtLink></li>
      </ul>
    </nav>

    <NuxtPage />

  </div>
</template>

<script setup>

// This is where you can access the head. All other imports 
// from original project are uneeded.
  useHead({
    title: 'oddOrbit',
  })
</script>

<style>
/* External CSS assets/css/styles.css is imported in the nuxt.config */

/* This CSS is copied right from your index.html. I think there is a lot of
duplicate code between this and your external css. I would recommend picking here
or assets/css/style.css for your global styles but not both. */
body {
    margin: 0;
    font-family: 'Arial', sans-serif;
    background-image: url('images/Leonardo_Diffusion_XL_Visualize_a_serene_alien_creature_its_bo_3.jpg');
    background-size: cover; /* Adjust based on your preferences */
    background-position: center; /* Adjust based on your preferences */
    background-repeat: no-repeat;
    background-attachment: fixed; /* Keeps the background fixed while scrolling */
}

        .container {
            display: flex;
        }

        .sidebar {
            width: 250px;
            height: 100%;
            background-color: #333;
            color: #ffffff;
            padding: 20px;
            box-sizing: border-box;
        }

        .sidebar h1 {
            font-size: 1.5rem;
            margin-bottom: 20px;
        }

        .sidebar ul {
            list-style: none;
            padding: 0;
        }

        .sidebar li {
            margin-bottom: 10px;
        }
  
        .sidebar a {
            text-decoration: none;
            color: #e3d807;
            font-weight: bold;
            font-size: 1rem;
            transition: 0.3s;
        }

        .sidebar a:hover {
            color: #e98e06;
        }

        .main-content {
            flex: 1;
            padding: 20px;
        }
</style>
