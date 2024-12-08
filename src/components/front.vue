<template>
 <Headertop />
  <Secondtop />

  <slider />
 
  <classifiedsection />
</template>


<script>
import Headertop from "@/components/headertop.vue";
import Secondtop from "@/components/scondtop.vue";
import Slider from "@/components/Slider.vue";
import classifiedsection from "@/components/classifiedsection.vue";


export default {
  components: {
    Secondtop,
    Slider,
    classifiedsection,
    Headertop,
  },
};
</script>
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Irish+Grover&display=swap");

.clssified-section {
  background-color: #d6d6e1;
  padding: 20px; /* Optional spacing */
}

.first-letter {
  font-family: "Irish Grover", cursive;
  font-size: 45px;
  color: #edf17f;
}
.container {
  background-color: #0837ad;
  padding: 20px; /* Optional, adds some spacing inside the div */
}

.custom-text-field .v-input__control::placeholder {
  color: #83aaff; /* Placeholder text color */
}
.custom-text-field .v-input {
  background-color: #b0d378; /* Background color */
  border-radius: 10px; /* Rounded corners */
}

.custom-text-field .v-label {
  color: #edf17f; /* Label color */
}
.custom-text-field .v-input__control::placeholder {
  color: #83aaff; /* Placeholder color */
}

.header-menu {
  display: flex;
  gap: 20px; /* Add space between links */
  font-family: "Irish Grover", cursive;
  font-size: 18px;
  color: #fff;
}

.header-menu p {
  margin: 0;
  cursor: pointer;
}

.header-menu p:hover {
  text-decoration: underline; /* Hover effect */
}
</style>
