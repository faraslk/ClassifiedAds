<template>
      <div class="clssified-section">
    <div class="image-container">
      <v-row no-gutters>
        <v-col>
          <div class="image-and-text">
            <img
              src="@/assets/house.jpg"
              alt="Description"
              class="custom-image"
            />
            <p class="classifiedfont">House</p>
            <br>
            <br>
            <br>
          </div>
        </v-col>
        <v-col>
          <div class="image-and-text">
            <img
              src="@/assets/furniture.jpg"
              alt="Description"
              class="custom-image"
            />
            <p class="classifiedfont">Furniture</p>
          </div></v-col
        >
        <v-col>
          <div class="image-and-text">
          <img
            src="@/assets/Consumer Electronics.jpg"
            alt="Description"
            class="custom-image"/>
            <p class="classifiedfont">Electronics</p>
          </div>
      </v-col>
      <v-col>
          <div class="image-and-text">
          <img
            src="@/assets/phone.jpg"
            alt="Description"
            class="custom-image"/>
            <p class="classifiedfont">Mobile</p>
          </div>
      </v-col>
      <v-col>
          <div class="image-and-text">
          <img
            src="@/assets/Consumer Electronics.jpg"
            alt="Description"
            class="custom-image"/>
            <p class="classifiedfont">House Hold</p>
          </div>
      </v-col>
      </v-row>
      <v-row no-gutters>
        <v-col
          >
          <div class="image-and-text">
          <img
            src="@/assets/Groceries.jpg"
            alt="Description"
            class="custom-image"
        />
        <p class="classifiedfont">Groceries</p>
        </div>
      </v-col>
        <v-col
          >
          <div class="image-and-text">
          
          <img
            src="@/assets/Home&Garden.jpg"
            alt="Description"
            class="custom-image"
        /> <p class="classifiedfont">Home & Garden</p>
      </div>
      
      </v-col>
        <v-col></v-col>
        <v-col></v-col>
        <v-col></v-col>
      </v-row>
    </div>
  </div>
</template>

<script>

</script>
<style scoped>

.clssified-section {
  background-color: #F5D9C0;
  padding: 20px; /* Optional spacing */
}
.classifiedfont {
  display: flex;
  gap: 20px; /* Add space between links */
  font-family: "Irish Grover", cursive;
  font-size: 30px;
  color: #000000;
  align-items: center;
}

.image-and-text {
  display: flex;
  flex-direction: column; /* Stack image and text vertically */
  align-items: center; /* Center content horizontally */
  text-align: center; /* Center text within its container */
}

.image-container {
  position: relative; /* Set the parent as the positioning context */
  height: 1200px; /* Optional height for the container */
  width: 100%; /* Optional width for the container */
}

.custom-image {
  top: 50px; /* Distance from the top of the viewport */
  left: 150px; /* Distance from the left of the viewport */
  width: 150px; /* Optional: Resize the image */
  height: 180px; /* Maintain aspect ratio */
}
</style>
