<template>
  <v-row class=".carousel-container" no-gutters>
    <v-col>
      <div class="video-container">
        <iframe
          width="560"
          height="315"
          src="https://www.youtube.com/embed/Jl2Fbo7npOA?si=FUgHQyPCgZwQ11UF"
          title="YouTube video player"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
          referrerpolicy="strict-origin-when-cross-origin"
          allowfullscreen
        ></iframe>
      </div>
    </v-col>
    <v-col>
      <v-carousel show-arrows="hover" height="315" class="carousel-container" hide-delimiters cycle interval="3000">
        <v-carousel-item src="@/assets/Consumer Electronics.jpg">
        </v-carousel-item>

        <v-carousel-item src="@/assets/house.jpg"></v-carousel-item>

        <v-carousel-item src="@/assets/Home&Garden.jpg"></v-carousel-item>
      </v-carousel>
    </v-col>
  </v-row>
</template>
<script>
</script>
<style scoped>
.video-container {
  display: flex;
  justify-content: center; /* Centers the video horizontally */
  align-items: center; /* Centers the video vertically */
  width: 100%;
  background-color: #F5D9C0; /* Light gray background */
  margin: 0; /* Ensure no external margins */
  padding: 0; /* Ensure no internal padding */
}

iframe {
  max-width: 100%;
  height: 315;
}

.carousel-container {
  background-color: #F5D9C0; /* Light gray background */


  width: 100%;
  margin: 0; /* Ensure no external margins */
  padding: 0; /* Ensure no internal padding */
}
</style>
