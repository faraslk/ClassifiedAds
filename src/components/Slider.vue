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
      <v-carousel show-arrows="hover" height="315" class="carousel-container">
        <v-carousel-item src="@/assets/Consumer Electronics.jpg">
          <p>
            It is a long established fact that a reader will be distracted by the
            readable content of a page when looking at its layout. The point of
            using Lorem Ipsum is that it has a more-or-less normal distribution
            of letters, as opposed to using 'Content here, content here',
          </p>
        </v-carousel-item>

        <v-carousel-item
          src="@/assets/house.jpg"
        ></v-carousel-item>

        <v-carousel-item
          src="@/assets/Home&Garden.jpg"
        ></v-carousel-item>
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
  background-color: #d9d9d9; /* Light gray background */
  margin: 0; /* Ensure no external margins */
  padding: 0; /* Ensure no internal padding */

}

iframe {
  max-width: 100%;
  height: 315;
}

.carousel-container{
    background-color: #d9d9d9; /* Light gray background */

    width: 100%;
    margin: 0; /* Ensure no external margins */
    padding: 0; /* Ensure no internal padding */
}
</style>
