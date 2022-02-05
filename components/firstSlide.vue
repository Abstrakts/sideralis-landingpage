<template>
  <div class="firstSlide">
    <v-container>
      <v-row>
        <v-col cols="12" class="text-center">
          <h1 class="logo">Sideralis</h1>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12" class="text-center">
          <p class="subtitle">La guerre des astres !</p>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>

export default {
  name: "firstSlide"
};
</script>

<style>
@import url("https://fonts.googleapis.com/css?family=Audiowide&display=swap");
@import url("https://fonts.googleapis.com/css?family=Odibee+Sans&display=swap");

.logo {
  font-family: "Audiowide", cursive;
  font-size: 5rem;
  font-weight: inherit;
  text-shadow: 10px 6px 0.1em #000;
}
.subtitle {
  font-family: "Odibee Sans", cursive;
  font-weight: inherit;
  font-size: 1.5rem;
  text-shadow: 2px 3px 0.1em #000;
}
.firstSlide {
  background-image: url("../assets/img/first_background.jpg");
  background-size: cover;
  height: 100vh;
  width: 100%;
  justify-content: center;
  align-items: center;
  display: flex;
}

</style>