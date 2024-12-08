<template>
  <div class="container">
    <v-app-bar :elevation="0" color="#0837ad">
      <v-row align="center" justify="space-between">
        <v-col>
          <p class="header">
            <span style="color: #edf17f">C</span>lassified
            <span style="color: #edf17f">A</span>ds
          </p>
        </v-col>
        <v-col cols="12" md="6" lg="4">
          <v-text-field
            append-inner-icon="mdi-magnify"
            density="compact"
            label="Search ClassifiedAds"
            variant="solo"
            hide-details
            single-line
           
            class="custom-text-field"
          />
        </v-col>
        <v-col>
          <div class="icon-and-text">
            <img src="@/assets/User.jpg" class="header-customer-icon" />
            <img src="@/assets/cart.jpg" class="header-customer-icon" />
          </div>
        </v-col>
      </v-row>
    </v-app-bar>
  </div>
</template>

<style scoped>
.header {
  padding: 20px;
  font-family: "Irish Grover", cursive;
  font-size: 45px;
  margin: 0;
}

.container {
  background-color: #0837ad;
  padding: 50px;
  position: relative;
  align-items: center;
}

.header-customer-icon {
  margin: 0 10px;
  width: 40px;
  height: 40px;
}

.icon-and-text {
  display: flex;
  align-items: center;
}

.custom-text-field {
  background-color: #ffffff;
  
  max-width: 800px;
  width: 100%;
}
</style>
