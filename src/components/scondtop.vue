<template>
    <div class="container">
    <div class="header-container">
      <p class="header">
        <span style="color: #edf17f">C</span>lassified
        <span style="color: #edf17f">A</span>ds
      </p>

      <v-text-field
        :loading="loading"
        append-inner-icon="mdi-magnify"
        density="compact"
        label="Search"
        variant="solo"
        hide-details
        single-line
        rounded
        class="custom-text-field"
        @click:append-inner="onClick"
      />

  
      <div class="header-menu">
        <p><span style="color: #edf17f">S</span>ign Up</p>
        <p><span style="color: #edf17f">S</span>ign In</p>
      </div>
    </div>

    <br /><br />
  </div>
</template>
<script>


</script>
<style scoped>

.container {
  background-color: #0837ad;
  padding: 20px; /* Optional spacing */
  position: relative;
}

.header-container {
  display: flex;
  align-items: center; /* Vertically align items */
  justify-content: space-between; /* Space between elements */
  flex-wrap: wrap; /* Wrap items if screen is small */
  max-width: 1200px; /* Center the content */
  margin: 0 auto;
}

.header {
  font-family: "Irish Grover", cursive;
  font-size: 45px;
  margin: 0; /* Remove default margin */
}

.custom-text-field {
  flex: 1; /* Allows the text field to grow if needed */
  max-width: 400px; /* Adjust as necessary */
}

.header-menu {
  font-family: "Irish Grover",cursive;
  font-size: 18px;
}

</style>
